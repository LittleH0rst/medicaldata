SELECT itemid, label, fluid, category
FROM d_labitems
WHERE label ILIKE '% age %' OR label ILIKE 'age %' OR label ILIKE '% age' OR label ILIKE 'age';

SELECT itemid, label, fluid, category
FROM d_labitems
WHERE label ILIKE '% gender %' OR label ILIKE 'gender %' OR label ILIKE '% gender' OR label ILIKE 'gender'
   OR label ILIKE '% sex %' OR label ILIKE 'sex %' OR label ILIKE '% sex' OR label ILIKE 'sex';

50982	Sex Hormone Binding Globulin	Blood	Chemistry

SELECT itemid, label, fluid, category
FROM d_labitems
WHERE label ILIKE '% nursing home %' OR label ILIKE 'nursing home %' OR label ILIKE '% nursing home' OR label ILIKE 'nursing home'
   OR label ILIKE '% nursing home resident %' OR label ILIKE 'nursing home resident %' OR label ILIKE '% nursing home resident' OR label ILIKE 'nursing home resident';

SELECT itemid, label, fluid, category
FROM d_labitems
WHERE label ILIKE '% mental status %' OR label ILIKE 'mental status %' OR label ILIKE '% mental status' OR label ILIKE 'mental status'
   OR label ILIKE '% level of consciousness %' OR label ILIKE 'level of consciousness %' OR label ILIKE '% level of consciousness' OR label ILIKE 'level of consciousness'
   OR label ILIKE '% LOC %' OR label ILIKE 'LOC %' OR label ILIKE '% LOC' OR label ILIKE 'LOC'
   OR label ILIKE '% alertness %' OR label ILIKE 'alertness %' OR label ILIKE '% alertness' OR label ILIKE 'alertness'
   OR label ILIKE '% orientation %' OR label ILIKE 'orientation %' OR label ILIKE '% orientation' OR label ILIKE 'orientation'
   OR label ILIKE '% confusion %' OR label ILIKE 'confusion %' OR label ILIKE '% confusion' OR label ILIKE 'confusion'
   OR label ILIKE '% delirium %' OR label ILIKE 'delirium %' OR label ILIKE '% delirium' OR label ILIKE 'delirium'
   OR label ILIKE '% stupor %' OR label ILIKE 'stupor %' OR label ILIKE '% stupor' OR label ILIKE 'stupor'
   OR label ILIKE '% coma %' OR label ILIKE 'coma %' OR label ILIKE '% coma' OR label ILIKE 'coma'
   OR label ILIKE '% Glasgow Coma Scale %' OR label ILIKE 'Glasgow Coma Scale %' OR label ILIKE '% Glasgow Coma Scale' OR label ILIKE 'Glasgow Coma Scale'
   OR label ILIKE '% GCS %' OR label ILIKE 'GCS %' OR label ILIKE '% GCS' OR label ILIKE 'GCS'
   OR label ILIKE '% cognitive status %' OR label ILIKE 'cognitive status %' OR label ILIKE '% cognitive status' OR label ILIKE 'cognitive status';

- no result, search in diagnoses:

SELECT icd_code, icd_version, long_title
FROM d_icd_diagnoses
WHERE long_title ILIKE '% mental status %' OR long_title ILIKE 'mental status %' OR long_title ILIKE '% mental status' OR long_title ILIKE 'mental status'
   OR long_title ILIKE '% level of consciousness %' OR long_title ILIKE 'level of consciousness %' OR long_title ILIKE '% level of consciousness' OR long_title ILIKE 'level of consciousness'
   OR long_title ILIKE '% LOC %' OR long_title ILIKE 'LOC %' OR long_title ILIKE '% LOC' OR long_title ILIKE 'LOC'
   OR long_title ILIKE '% alertness %' OR long_title ILIKE 'alertness %' OR long_title ILIKE '% alertness' OR long_title ILIKE 'alertness'
   OR long_title ILIKE '% orientation %' OR long_title ILIKE 'orientation %' OR long_title ILIKE '% orientation' OR long_title ILIKE 'orientation'
   OR long_title ILIKE '% confusion %' OR long_title ILIKE 'confusion %' OR long_title ILIKE '% confusion' OR long_title ILIKE 'confusion'
   OR long_title ILIKE '% delirium %' OR long_title ILIKE 'delirium %' OR long_title ILIKE '% delirium' OR long_title ILIKE 'delirium'
   OR long_title ILIKE '% stupor %' OR long_title ILIKE 'stupor %' OR long_title ILIKE '% stupor' OR long_title ILIKE 'stupor'
   OR long_title ILIKE '% coma %' OR long_title ILIKE 'coma %' OR long_title ILIKE '% coma' OR long_title ILIKE 'coma'
   OR long_title ILIKE '% Glasgow Coma Scale %' OR long_title ILIKE 'Glasgow Coma Scale %' OR long_title ILIKE '% Glasgow Coma Scale' OR long_title ILIKE 'Glasgow Coma Scale'
   OR long_title ILIKE '% GCS %' OR long_title ILIKE 'GCS %' OR long_title ILIKE '% GCS' OR long_title ILIKE 'GCS'
   OR long_title ILIKE '% cognitive status %' OR long_title ILIKE 'cognitive status %' OR long_title ILIKE '% cognitive status' OR long_title ILIKE 'cognitive status';

 0701   	9	Viral hepatitis A without mention of hepatic coma
07022  	9	Chronic viral hepatitis B with hepatic coma without hepatitis delta
2510   	9	Hypoglycemic coma
07033  	9	Chronic viral hepatitis B without mention of hepatic coma with hepatitis delta
2930   	9	Delirium due to conditions classified elsewhere
2903   	9	Senile dementia with delirium
07023  	9	Chronic viral hepatitis B with hepatic coma with hepatitis delta
0709   	9	Unspecified viral hepatitis without mention of hepatic coma
3020   	9	Ego-dystonic sexual orientation
0706   	9	Unspecified viral hepatitis with hepatic coma
07052  	9	Hepatitis delta without mention of active hepatitis B disease or hepatic coma
2931   	9	Subacute delirium
07044  	9	Chronic hepatitis C with hepatic coma
07051  	9	Acute hepatitis C without mention of hepatic coma
07059  	9	Other specified viral hepatitis without mention of hepatic coma
2982   	9	Reactive confusion
07041  	9	Acute hepatitis C with hepatic coma
07032  	9	Chronic viral hepatitis B without mention of hepatic coma without mention of hepatitis delta
07049  	9	Other specified viral hepatitis with hepatic coma
07042  	9	Hepatitis delta without mention of active hepatitis B disease with hepatic coma
07043  	9	Hepatitis E with hepatic coma
29281  	9	Drug-induced delirium
29011  	9	Presenile dementia with delirium
07070  	9	Unspecified viral hepatitis C without hepatic coma
2910   	9	Alcohol withdrawal delirium
07054  	9	Chronic hepatitis C without mention of hepatic coma
78001  	9	Coma
07053  	9	Hepatitis E without mention of hepatic coma
0700   	9	Viral hepatitis A with hepatic coma
78097  	9	Altered mental status
07071  	9	Unspecified viral hepatitis C with hepatic coma
29041  	9	Vascular dementia, with delirium
B1920  	10	Unspecified viral hepatitis C without hepatic coma
R402144	10	Coma scale, eyes open, spontaneous, 24 hours or more after hospital admission
R402221	10	Coma scale, best verbal response, incomprehensible words, in the field [EMT or ambulance]
R402340	10	Coma scale, best motor response, flexion withdrawal, unspecified time
R40242 	10	Glasgow coma scale score 9-12
R402442	10	Other coma, without documented Glasgow coma scale score, or with partial score reported, at arrival to emergency department
E1311  	10	Other specified diabetes mellitus with ketoacidosis with coma
F19121 	10	Other psychoactive substance abuse with intoxication delirium
R402123	10	Coma scale, eyes open, to pain, at hospital admission
R402242	10	Coma scale, best verbal response, confused conversation, at arrival to emergency department
R402351	10	Coma scale, best motor response, localizes pain, in the field [EMT or ambulance]
R402431	10	Glasgow coma scale score 3-8, in the field [EMT or ambulance]
E0910  	10	Drug or chemical induced diabetes mellitus with ketoacidosis without coma
F12921 	10	Cannabis use, unspecified with intoxication delirium
K7110  	10	Toxic liver disease with hepatic necrosis, without coma
R402211	10	Coma scale, best verbal response, none, in the field [EMT or ambulance]
E10641 	10	Type 1 diabetes mellitus with hypoglycemia with coma
F11221 	10	Opioid dependence with intoxication delirium
Z703   	10	Counseling related to combined concerns regarding sexual attitude, behavior and orientation
B199   	10	Unspecified viral hepatitis without hepatic coma
E035   	10	Myxedema coma
E15    	10	Nondiabetic hypoglycemic coma
K7211  	10	Chronic hepatic failure with coma
R402230	10	Coma scale, best verbal response, inappropriate words, unspecified time
R402312	10	Coma scale, best motor response, none, at arrival to emergency department
F19921 	10	Other psychoactive substance use, unspecified with intoxication with delirium
F442   	10	Dissociative stupor
R402   	10	Coma
R40243 	10	Glasgow coma scale score 3-8
F10221 	10	Alcohol dependence with intoxication delirium
R402112	10	Coma scale, eyes open, never, at arrival to emergency department
R402323	10	Coma scale, best motor response, extension, at hospital admission
R402330	10	Coma scale, best motor response, abnormal flexion, unspecified time
E11641 	10	Type 2 diabetes mellitus with hypoglycemia with coma
R4021  	10	Coma scale, eyes open
E1300  	10	Other specified diabetes mellitus with hyperosmolarity without nonketotic hyperglycemic-hyperosmolar coma (NKHHC)
K7200  	10	Acute and subacute hepatic failure without coma
K7201  	10	Acute and subacute hepatic failure with coma
K7290  	10	Hepatic failure, unspecified without coma
R402210	10	Coma scale, best verbal response, none, unspecified time
R402322	10	Coma scale, best motor response, extension, at arrival to emergency department
B1711  	10	Acute hepatitis C with hepatic coma
E08649 	10	Diabetes mellitus due to underlying condition with hypoglycemia without coma
F11921 	10	Opioid use, unspecified with intoxication delirium
F15121 	10	Other stimulant abuse with intoxication delirium
F18921 	10	Inhalant use, unspecified with intoxication with delirium
R402352	10	Coma scale, best motor response, localizes pain, at arrival to emergency department
R402360	10	Coma scale, best motor response, obeys commands, unspecified time
R402444	10	Other coma, without documented Glasgow coma scale score, or with partial score reported, 24 hours or more after hospital admission
E0800  	10	Diabetes mellitus due to underlying condition with hyperosmolarity without nonketotic hyperglycemic-hyperosmolar coma (NKHHC)
E1111  	10	Type 2 diabetes mellitus with ketoacidosis with coma
E1301  	10	Other specified diabetes mellitus with hyperosmolarity with coma
F13931 	10	Sedative, hypnotic or anxiolytic use, unspecified with withdrawal delirium
R40224 	10	Coma scale, best verbal response, confused conversation
R402243	10	Coma scale, best verbal response, confused conversation, at hospital admission
R402362	10	Coma scale, best motor response, obeys commands, at arrival to emergency department
F14921 	10	Cocaine use, unspecified with intoxication delirium
F16121 	10	Hallucinogen abuse with intoxication with delirium
F18221 	10	Inhalant dependence with intoxication delirium
R40212 	10	Coma scale, eyes open, to pain
R402222	10	Coma scale, best verbal response, incomprehensible words, at arrival to emergency department
R402310	10	Coma scale, best motor response, none, unspecified time
R402343	10	Coma scale, best motor response, flexion withdrawal, at hospital admission
R402420	10	Glasgow coma scale score 9-12, unspecified time
Z701   	10	Counseling related to patient's sexual behavior and orientation
K7040  	10	Alcoholic hepatic failure without coma
R40211 	10	Coma scale, eyes open, never
R40232 	10	Coma scale, best motor response, extension
R402350	10	Coma scale, best motor response, localizes pain, unspecified time
E0901  	10	Drug or chemical induced diabetes mellitus with hyperosmolarity with coma
K7210  	10	Chronic hepatic failure without coma
R402232	10	Coma scale, best verbal response, inappropriate words, at arrival to emergency department
R40244 	10	Other coma, without documented Glasgow coma scale score, or with partial score reported
F10121 	10	Alcohol abuse with intoxication delirium
F19221 	10	Other psychoactive substance dependence with intoxication delirium
R402313	10	Coma scale, best motor response, none, at hospital admission
R40236 	10	Coma scale, best motor response, obeys commands
R402364	10	Coma scale, best motor response, obeys commands, 24 hours or more after hospital admission
R402443	10	Other coma, without documented Glasgow coma scale score, or with partial score reported, at hospital admission
R40225 	10	Coma scale, best verbal response, oriented
R402251	10	Coma scale, best verbal response, oriented, in the field [EMT or ambulance]
R402333	10	Coma scale, best motor response, abnormal flexion, at hospital admission
R40235 	10	Coma scale, best motor response, localizes pain
E0900  	10	Drug or chemical induced diabetes mellitus with hyperosmolarity without nonketotic hyperglycemic-hyperosmolar coma (NKHHC)
R402422	10	Glasgow coma scale score 9-12, at arrival to emergency department
F13121 	10	Sedative, hypnotic or anxiolytic abuse with intoxication delirium
F19231 	10	Other psychoactive substance dependence with withdrawal delirium
R40214 	10	Coma scale, eyes open, spontaneous
R40234 	10	Coma scale, best motor response, flexion withdrawal
R402424	10	Glasgow coma scale score 9-12, 24 hours or more after hospital admission
R402432	10	Glasgow coma scale score 3-8, at arrival to emergency department
E09641 	10	Drug or chemical induced diabetes mellitus with hypoglycemia with coma
E1010  	10	Type 1 diabetes mellitus with ketoacidosis without coma
F12121 	10	Cannabis abuse with intoxication delirium
K7111  	10	Toxic liver disease with hepatic necrosis, with coma
R402361	10	Coma scale, best motor response, obeys commands, in the field [EMT or ambulance]
R402363	10	Coma scale, best motor response, obeys commands, at hospital admission
F14221 	10	Cocaine dependence with intoxication delirium
R402314	10	Coma scale, best motor response, none, 24 hours or more after hospital admission
P915   	10	Neonatal coma
R402111	10	Coma scale, eyes open, never, in the field [EMT or ambulance]
F14121 	10	Cocaine abuse with intoxication with delirium
R402133	10	Coma scale, eyes open, to sound, at hospital admission
E0811  	10	Diabetes mellitus due to underlying condition with ketoacidosis with coma
E11649 	10	Type 2 diabetes mellitus with hypoglycemia without coma
R402121	10	Coma scale, eyes open, to pain, in the field [EMT or ambulance]
R402141	10	Coma scale, eyes open, spontaneous, in the field [EMT or ambulance]
R402231	10	Coma scale, best verbal response, inappropriate words, in the field [EMT or ambulance]
R402353	10	Coma scale, best motor response, localizes pain, at hospital admission
R40222 	10	Coma scale, best verbal response, incomprehensible words
E08641 	10	Diabetes mellitus due to underlying condition with hypoglycemia with coma
K7041  	10	Alcoholic hepatic failure with coma
R402311	10	Coma scale, best motor response, none, in the field [EMT or ambulance]
B150   	10	Hepatitis A with hepatic coma
E1100  	10	Type 2 diabetes mellitus with hyperosmolarity without nonketotic hyperglycemic-hyperosmolar coma (NKHHC)
R40213 	10	Coma scale, eyes open, to sound
R402130	10	Coma scale, eyes open, to sound, unspecified time
R402224	10	Coma scale, best verbal response, incomprehensible words, 24 hours or more after hospital admission
B1921  	10	Unspecified viral hepatitis C with hepatic coma
E160   	10	Drug-induced hypoglycemia without coma
F10231 	10	Alcohol dependence with withdrawal delirium
F16221 	10	Hallucinogen dependence with intoxication with delirium
R402223	10	Coma scale, best verbal response, incomprehensible words, at hospital admission
R402122	10	Coma scale, eyes open, to pain, at arrival to emergency department
E0810  	10	Diabetes mellitus due to underlying condition with ketoacidosis without coma
F13921 	10	Sedative, hypnotic or anxiolytic use, unspecified with intoxication delirium
F19931 	10	Other psychoactive substance use, unspecified with withdrawal delirium
R402110	10	Coma scale, eyes open, never, unspecified time
R402142	10	Coma scale, eyes open, spontaneous, at arrival to emergency department
R402220	10	Coma scale, best verbal response, incomprehensible words, unspecified time
R402321	10	Coma scale, best motor response, extension, in the field [EMT or ambulance]
E1310  	10	Other specified diabetes mellitus with ketoacidosis without coma
F10921 	10	Alcohol use, unspecified with intoxication delirium
F15921 	10	Other stimulant use, unspecified with intoxication delirium
R40    	10	Somnolence, stupor and coma
R401   	10	Stupor
R40231 	10	Coma scale, best motor response, none
Z702   	10	Counseling related to sexual behavior and orientation of third party
E1110  	10	Type 2 diabetes mellitus with ketoacidosis without coma
F18121 	10	Inhalant abuse with intoxication delirium
K7291  	10	Hepatic failure, unspecified with coma
R402120	10	Coma scale, eyes open, to pain, unspecified time
R402410	10	Glasgow coma scale score 13-15, unspecified time
F13221 	10	Sedative, hypnotic or anxiolytic dependence with intoxication delirium
F15221 	10	Other stimulant dependence with intoxication delirium
R402132	10	Coma scale, eyes open, to sound, at arrival to emergency department
R402440	10	Other coma, without documented Glasgow coma scale score, or with partial score reported, unspecified time
R402332	10	Coma scale, best motor response, abnormal flexion, at arrival to emergency department
R402213	10	Coma scale, best verbal response, none, at hospital admission
R402250	10	Coma scale, best verbal response, oriented, unspecified time
E0801  	10	Diabetes mellitus due to underlying condition with hyperosmolarity with coma
R402134	10	Coma scale, eyes open, to sound, 24 hours or more after hospital admission
R402344	10	Coma scale, best motor response, flexion withdrawal, 24 hours or more after hospital admission
B161   	10	Acute hepatitis B with delta-agent without hepatic coma
R4020  	10	Unspecified coma
R402212	10	Coma scale, best verbal response, none, at arrival to emergency department
R402320	10	Coma scale, best motor response, extension, unspecified time
R402411	10	Glasgow coma scale score 13-15, in the field [EMT or ambulance]
E10649 	10	Type 1 diabetes mellitus with hypoglycemia without coma
F13231 	10	Sedative, hypnotic or anxiolytic dependence with withdrawal delirium
B162   	10	Acute hepatitis B without delta-agent with hepatic coma
E0911  	10	Drug or chemical induced diabetes mellitus with ketoacidosis with coma
R402241	10	Coma scale, best verbal response, confused conversation, in the field [EMT or ambulance]
R402412	10	Glasgow coma scale score 13-15, at arrival to emergency department
E1011  	10	Type 1 diabetes mellitus with ketoacidosis with coma
F16921 	10	Hallucinogen use, unspecified with intoxication with delirium
R402433	10	Glasgow coma scale score 3-8, at hospital admission
E1101  	10	Type 2 diabetes mellitus with hyperosmolarity with coma
R402114	10	Coma scale, eyes open, never, 24 hours or more after hospital admission
R40221 	10	Coma scale, best verbal response, none
R402131	10	Coma scale, eyes open, to sound, in the field [EMT or ambulance]
R402140	10	Coma scale, eyes open, spontaneous, unspecified time
R40223 	10	Coma scale, best verbal response, inappropriate words
R402252	10	Coma scale, best verbal response, oriented, at arrival to emergency department
B169   	10	Acute hepatitis B without delta-agent and without hepatic coma
R402240	10	Coma scale, best verbal response, confused conversation, unspecified time
R402254	10	Coma scale, best verbal response, oriented, 24 hours or more after hospital admission
R4023  	10	Coma scale, best motor response
R402334	10	Coma scale, best motor response, abnormal flexion, 24 hours or more after hospital admission
R402441	10	Other coma, without documented Glasgow coma scale score, or with partial score reported, in the field [EMT or ambulance]
B1910  	10	Unspecified viral hepatitis B without hepatic coma
F12221 	10	Cannabis dependence with intoxication delirium
R402113	10	Coma scale, eyes open, never, at hospital admission
R40233 	10	Coma scale, best motor response, abnormal flexion
R402413	10	Glasgow coma scale score 13-15, at hospital admission
Z70    	10	Counseling related to sexual attitude, behavior and orientation
B159   	10	Hepatitis A without hepatic coma
B1710  	10	Acute hepatitis C without hepatic coma
R402124	10	Coma scale, eyes open, to pain, 24 hours or more after hospital admission
R402143	10	Coma scale, eyes open, spontaneous, at hospital admission
R40241 	10	Glasgow coma scale score 13-15
E13641 	10	Other specified diabetes mellitus with hypoglycemia with coma
F11121 	10	Opioid abuse with intoxication delirium
R402341	10	Coma scale, best motor response, flexion withdrawal, in the field [EMT or ambulance]
R402354	10	Coma scale, best motor response, localizes pain, 24 hours or more after hospital admission
R4024  	10	Glasgow coma scale, total score
R402430	10	Glasgow coma scale score 3-8, unspecified time
R402414	10	Glasgow coma scale score 13-15, 24 hours or more after hospital admission
B190   	10	Unspecified viral hepatitis with hepatic coma
R4022  	10	Coma scale, best verbal response
R402244	10	Coma scale, best verbal response, confused conversation, 24 hours or more after hospital admission
R402421	10	Glasgow coma scale score 9-12, in the field [EMT or ambulance]
R402434	10	Glasgow coma scale score 3-8, 24 hours or more after hospital admission
B160   	10	Acute hepatitis B with delta-agent with hepatic coma
B1911  	10	Unspecified viral hepatitis B with hepatic coma
E09649 	10	Drug or chemical induced diabetes mellitus with hypoglycemia without coma
E13649 	10	Other specified diabetes mellitus with hypoglycemia without coma
R402214	10	Coma scale, best verbal response, none, 24 hours or more after hospital admission
R402253	10	Coma scale, best verbal response, oriented, at hospital admission
R402233	10	Coma scale, best verbal response, inappropriate words, at hospital admission
R402234	10	Coma scale, best verbal response, inappropriate words, 24 hours or more after hospital admission
R402324	10	Coma scale, best motor response, extension, 24 hours or more after hospital admission
R402331	10	Coma scale, best motor response, abnormal flexion, in the field [EMT or ambulance]
R402342	10	Coma scale, best motor response, flexion withdrawal, at arrival to emergency department
R402423	10	Glasgow coma scale score 9-12, at hospital admission
F05    	10	Delirium due to known physiological condition

SELECT itemid, label, fluid, category
FROM d_labitems
WHERE label ILIKE '% respiratory rate %' OR label ILIKE 'respiratory rate %' OR label ILIKE '% respiratory rate' OR label ILIKE 'respiratory rate'
   OR label ILIKE '% breathing rate %' OR label ILIKE 'breathing rate %' OR label ILIKE '% breathing rate' OR label ILIKE 'breathing rate'
   OR label ILIKE '% respiratory %' OR label ILIKE 'respiratory %' OR label ILIKE '% respiratory' OR label ILIKE 'respiratory'
   OR label ILIKE '% breathing %' OR label ILIKE 'breathing %' OR label ILIKE '% breathing' OR label ILIKE 'breathing';
   
53113	Rapid Respiratory Syncytial Virus	Other Body Fluid	Chemistry

SELECT itemid, label, fluid, category
FROM d_labitems
WHERE label ILIKE '% systolic blood pressure %' OR label ILIKE 'systolic blood pressure %' OR label ILIKE '% systolic blood pressure' OR label ILIKE 'systolic blood pressure' 
   OR label ILIKE '% systolic BP %' OR label ILIKE 'systolic BP %' OR label ILIKE '% systolic BP' OR label ILIKE 'systolic BP'
   OR label ILIKE '% blood pressure %' OR label ILIKE 'blood pressure %' OR label ILIKE '% blood pressure' OR label ILIKE 'blood pressure'
   OR label ILIKE '% BP %' OR label ILIKE 'BP %' OR label ILIKE '% BP' OR label ILIKE 'BP';

SELECT itemid, label, fluid, category
FROM d_labitems
WHERE label ILIKE '% temperature %' OR label ILIKE 'temperature %' OR label ILIKE '% temperature' OR label ILIKE 'temperature';

50825	Temperature	Blood	Blood Gas

SELECT itemid, label, fluid, category
FROM d_labitems
WHERE label ILIKE '% pulse %' OR label ILIKE 'pulse %' OR label ILIKE '% pulse' OR label ILIKE 'pulse';

SELECT itemid, label, fluid, category
FROM d_labitems
WHERE label ILIKE '% blood urea nitrogen %' OR label ILIKE 'blood urea nitrogen %' OR label ILIKE '% blood urea nitrogen' OR label ILIKE 'blood urea nitrogen'
   OR label ILIKE '% BUN %' OR label ILIKE 'BUN %' OR label ILIKE '% BUN' OR label ILIKE 'BUN';

51842	Bun	Other Body Fluid	Chemistry

SELECT itemid, label, fluid, category
FROM d_labitems
WHERE label ILIKE '% pH measurement %' OR label ILIKE 'pH measurement %' OR label ILIKE '% pH measurement' OR label ILIKE 'pH measurement'
   OR label ILIKE '% arterial pH %' OR label ILIKE 'arterial pH %' OR label ILIKE '% arterial pH' OR label ILIKE 'arterial pH'
   OR label ILIKE '% pH %' OR label ILIKE 'pH %' OR label ILIKE '% pH' OR label ILIKE 'pH';

50820	pH	Blood	Blood Gas
52041	pH	Fluid	Blood Gas
50831	pH	Other Body Fluid	Blood Gas
52730	pH	Urine	Chemistry
51094	pH	Urine	Chemistry
51491	pH	Urine	Hematology

SELECT itemid, label, fluid, category
FROM d_labitems
WHERE label ILIKE '% sodium measurement %' OR label ILIKE 'sodium measurement %' OR label ILIKE '% sodium measurement' OR label ILIKE 'sodium measurement'
   OR label ILIKE '% sodium %' OR label ILIKE 'sodium %' OR label ILIKE '% sodium' OR label ILIKE 'sodium';

50983	Sodium	Blood	Chemistry
52623	Sodium	Blood	Chemistry

SELECT itemid, label, fluid, category
FROM d_labitems
WHERE label ILIKE '% glucose measurement %' OR label ILIKE 'glucose measurement %' OR label ILIKE '% glucose measurement' OR label ILIKE 'glucose measurement'
   OR label ILIKE '% glucose %' OR label ILIKE 'glucose %' OR label ILIKE '% glucose' OR label ILIKE 'glucose';

50809	Glucose	Blood	Blood Gas
50931	Glucose	Blood	Chemistry
52569	Glucose	Blood	Chemistry
51981	Glucose	Urine	Chemistry
51478	Glucose	Urine	Hematology

SELECT itemid, label, fluid, category
FROM d_labitems
WHERE label ILIKE '% hematocrit measurement %' OR label ILIKE 'hematocrit measurement %' OR label ILIKE '% hematocrit measurement' OR label ILIKE 'hematocrit measurement'
   OR label ILIKE '% hematocrit %' OR label ILIKE 'hematocrit %' OR label ILIKE '% hematocrit' OR label ILIKE 'hematocrit';

52028	Hematocrit	Blood	Blood Gas
51638	Hematocrit	Blood	Chemistry
51639	Hematocrit	Blood	Chemistry
51221	Hematocrit	Blood	Hematology
51480	Hematocrit	Urine	Hematology

SELECT itemid, label, fluid, category
FROM d_labitems
WHERE label ILIKE '% partial pressure of arterial oxygen %' OR label ILIKE 'partial pressure of arterial oxygen %' OR label ILIKE '% partial pressure of arterial oxygen' OR label ILIKE 'partial pressure of arterial oxygen'
   OR label ILIKE '% oxygen saturation %' OR label ILIKE 'oxygen saturation %' OR label ILIKE '% oxygen saturation' OR label ILIKE 'oxygen saturation'
   OR label ILIKE '% O2 saturation %' OR label ILIKE 'O2 saturation %' OR label ILIKE '% O2 saturation' OR label ILIKE 'O2 saturation';

50817	Oxygen Saturation	Blood	Blood Gas

SELECT itemid, label, fluid, category
FROM d_labitems
WHERE label ILIKE '% pleural effusion on x-ray %' OR label ILIKE 'pleural effusion on x-ray %' OR label ILIKE '% pleural effusion on x-ray' OR label ILIKE 'pleural effusion on x-ray'
   OR label ILIKE '% pleural effusion %' OR label ILIKE 'pleural effusion %' OR label ILIKE '% pleural effusion' OR label ILIKE 'pleural effusion';


no result - but in diagnoses

SELECT icd_code, icd_version, long_title FROM d_icd_diagnoses
WHERE long_title ILIKE '% pleural effusion on x-ray %' OR long_title ILIKE 'pleural effusion on x-ray %' OR long_title ILIKE '% pleural effusion on x-ray' OR long_title ILIKE 'pleural effusion on x-ray' OR long_title ILIKE '% pleural effusion %' OR long_title ILIKE 'pleural effusion %' OR long_title ILIKE '% pleural effusion' OR long_title ILIKE 'pleural effusion';

51181  	9	Malignant pleural effusion
5119   	9	Unspecified pleural effusion
J910   	10	Malignant pleural effusion
J918   	10	Pleural effusion in other conditions classified elsewhere
J91    	10	Pleural effusion in conditions classified elsewhere
