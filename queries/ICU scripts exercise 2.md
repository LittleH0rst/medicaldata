SELECT itemid, label, abbreviation, linksto, category, param_type 
FROM d_items 
WHERE label ILIKE '% age %' OR label ILIKE 'age %' OR label ILIKE '% age' OR label ILIKE 'age'
   OR abbreviation ILIKE '% age %' OR abbreviation ILIKE 'age %' OR abbreviation ILIKE '% age' OR abbreviation ILIKE 'age';

   
- 226984	Apache IV Age	Apache IV Age	chartevents	Scores - APACHE IV (2)	Numeric


SELECT itemid, label, abbreviation, linksto, category, param_type 
FROM d_items 
WHERE label ILIKE '% gender %' OR label ILIKE 'gender %' OR label ILIKE '% gender' OR label ILIKE 'gender'
   OR label ILIKE '% sex %' OR label ILIKE 'sex %' OR label ILIKE '% sex' OR label ILIKE 'sex'
   OR abbreviation ILIKE '% gender %' OR abbreviation ILIKE 'gender %' OR abbreviation ILIKE '% gender' OR abbreviation ILIKE 'gender'
   OR abbreviation ILIKE '% sex %' OR abbreviation ILIKE 'sex %' OR abbreviation ILIKE '% sex' OR abbreviation ILIKE 'sex';

- 226228	Gender	Gender	chartevents	ADT	Text


SELECT itemid, label, abbreviation, linksto, category, param_type 
FROM d_items 
WHERE label ILIKE '% nursing home %' OR label ILIKE 'nursing home %' OR label ILIKE '% nursing home' OR label ILIKE 'nursing home'
   OR label ILIKE '% nursing home resident %' OR label ILIKE 'nursing home resident %' OR label ILIKE '% nursing home resident' OR label ILIKE 'nursing home resident'
   OR abbreviation ILIKE '% nursing home %' OR abbreviation ILIKE 'nursing home %' OR abbreviation ILIKE '% nursing home' OR abbreviation ILIKE 'nursing home'
   OR abbreviation ILIKE '% nursing home resident %' OR abbreviation ILIKE 'nursing home resident %' OR abbreviation ILIKE '% nursing home resident' OR abbreviation ILIKE 'nursing home resident';

- no result
- admission location, discharge location 

SELECT itemid, label, abbreviation, linksto, category, param_type 
FROM d_items 
WHERE label ILIKE '% confusion %' OR label ILIKE 'confusion %' OR label ILIKE '% confusion' OR label ILIKE 'confusion'
   OR label ILIKE '% mental instability %' OR label ILIKE 'mental instability %' OR label ILIKE '% mental instability' OR label ILIKE 'mental instability'
   OR abbreviation ILIKE '% confusion %' OR abbreviation ILIKE 'confusion %' OR abbreviation ILIKE '% confusion' OR abbreviation ILIKE 'confusion'
   OR abbreviation ILIKE '% mental instability %' OR abbreviation ILIKE 'mental instability %' OR abbreviation ILIKE '% mental instability' OR abbreviation ILIKE 'mental instability';

- no result

SELECT itemid, label, abbreviation, linksto, category, param_type 
FROM d_items 
WHERE label ILIKE '% respiratory rate %' OR label ILIKE 'respiratory rate %' OR label ILIKE '% respiratory rate' OR label ILIKE 'respiratory rate'
   OR label ILIKE '% breathing rate %' OR label ILIKE 'breathing rate %' OR label ILIKE '% breathing rate' OR label ILIKE 'breathing rate'
   OR label ILIKE '% respiratory %' OR label ILIKE 'respiratory %' OR label ILIKE '% respiratory' OR label ILIKE 'respiratory'
   OR label ILIKE '% breathing %' OR label ILIKE 'breathing %' OR label ILIKE '% breathing' OR label ILIKE 'breathing'
   OR abbreviation ILIKE '% respiratory rate %' OR abbreviation ILIKE 'respiratory rate %' OR abbreviation ILIKE '% respiratory rate' OR abbreviation ILIKE 'respiratory rate'
   OR abbreviation ILIKE '% breathing rate %' OR abbreviation ILIKE 'breathing rate %' OR abbreviation ILIKE '% breathing rate' OR abbreviation ILIKE 'breathing rate'
   OR abbreviation ILIKE '% respiratory %' OR abbreviation ILIKE 'respiratory %' OR abbreviation ILIKE '% respiratory' OR abbreviation ILIKE 'respiratory'
   OR abbreviation ILIKE '% breathing %' OR abbreviation ILIKE 'breathing %' OR abbreviation ILIKE '% breathing' OR abbreviation ILIKE 'breathing';


- 230040	Paradoxical breathing	Paradoxical breathing	chartevents	RDOS	Text

SELECT itemid, label, abbreviation, linksto, category, param_type 
FROM d_items 
WHERE 
    label ILIKE '% systolic blood pressure %' OR label ILIKE 'systolic blood pressure %' OR label ILIKE '% systolic blood pressure' OR label ILIKE 'systolic blood pressure' 
    OR label ILIKE '% systolic BP %' OR label ILIKE 'systolic BP %' OR label ILIKE '% systolic BP' OR label ILIKE 'systolic BP'
    OR label ILIKE '% blood pressure %' OR label ILIKE 'blood pressure %' OR label ILIKE '% blood pressure' OR label ILIKE 'blood pressure'
    OR label ILIKE '% BP %' OR label ILIKE 'BP %' OR label ILIKE '% BP' OR label ILIKE 'BP'
    OR abbreviation ILIKE '% systolic blood pressure %' OR abbreviation ILIKE 'systolic blood pressure %' OR abbreviation ILIKE '% systolic blood pressure' OR abbreviation ILIKE 'systolic blood pressure'
    OR abbreviation ILIKE '% systolic BP %' OR abbreviation ILIKE 'systolic BP %' OR abbreviation ILIKE '% systolic BP' OR abbreviation ILIKE 'systolic BP'
    OR abbreviation ILIKE '% blood pressure %' OR abbreviation ILIKE 'blood pressure %' OR abbreviation ILIKE '% blood pressure' OR abbreviation ILIKE 'blood pressure'
    OR abbreviation ILIKE '% BP %' OR abbreviation ILIKE 'BP %' OR abbreviation ILIKE '% BP' OR abbreviation ILIKE 'BP';



227539	ART Blood Pressure Alarm Source	ART BP Alarm Source	chartevents	Alarms	Text
224317	ABI Ankle BP R	ABI Ankle BP R	chartevents	IABP	Numeric
228146	ABI Brachial BP R	ABI Brachial BP R 	chartevents	IABP	Numeric
224315	ABI Brachial BP L	ABI Brachial BP L	chartevents	IABP	Numeric
228145	ABI Ankle BP L	ABI Ankle BP L 	chartevents	IABP	Numeric
220058	Arterial Blood Pressure Alarm - High	ABP Alarm - High	chartevents	Alarms	Numeric
220056	Arterial Blood Pressure Alarm - Low	ABP Alarm - Low	chartevents	Alarms	Numeric
223752	Non-Invasive Blood Pressure Alarm - Low	NBP Alarm - Low	chartevents	Alarms	Numeric
227538	ART Blood Pressure Alarm - Low	ART BP Alarm - Low	chartevents	Alarms	Numeric
227537	ART Blood Pressure Alarm - High	ART BP Alarm - High	chartevents	Alarms	Numeric
223751	Non-Invasive Blood Pressure Alarm - High	NBP Alarm - High	chartevents	Alarms	Numeric
228149	ABI Brachial BP L (Impella)	ABI Brachial BP L (Impella)	chartevents	Impella	Numeric
228148	ABI Ankle BP R (Impella)	ABI Ankle BP R (Impella)	chartevents	Impella	Numeric
224314	ABI Brachial BP R (Impella)	ABI Brachial BP R (Impella)	chartevents	Impella	Numeric
224318	ABI Ankle BP L (Impella)	ABI Ankle BP L (Impella)	chartevents	Impella	Numeric
229827	Mean BP (VAD)	Mean BP (VAD)	chartevents	Durable VAD	Numeric
228872	HM II- Mean BP	HM II- Mean BP	chartevents	Hemodynamics	Numeric
224166	Doppler BP	Doppler BP	chartevents	Routine Vital Signs	Numeric
225309	ART BP Systolic	ART BP Systolic	chartevents	Routine Vital Signs	Numeric
220052	Arterial Blood Pressure mean	ABPm	chartevents	Routine Vital Signs	Numeric
227242	Manual Blood Pressure Diastolic Right	Manual BPd R	chartevents	Routine Vital Signs	Numeric
220180	Non Invasive Blood Pressure diastolic	NBPd	chartevents	Routine Vital Signs	Numeric
227243	Manual Blood Pressure Systolic Right	Manual BPs R	chartevents	Routine Vital Signs	Numeric
220051	Arterial Blood Pressure diastolic	ABPd	chartevents	Routine Vital Signs	Numeric
220181	Non Invasive Blood Pressure mean	NBPm	chartevents	Routine Vital Signs	Numeric
225310	ART BP Diastolic	ART BP Diastolic	chartevents	Routine Vital Signs	Numeric
224643	Manual Blood Pressure Diastolic Left	Manual BPd L	chartevents	Routine Vital Signs	Numeric
220179	Non Invasive Blood Pressure systolic	NBPs	chartevents	Routine Vital Signs	Numeric
220050	Arterial Blood Pressure systolic	ABPs	chartevents	Routine Vital Signs	Numeric
225312	ART BP Mean	ART BP Mean	chartevents	Routine Vital Signs	Numeric
224167	Manual Blood Pressure Systolic Left	Manual BPs L	chartevents	Routine Vital Signs	Numeric

SELECT itemid, label, abbreviation, linksto, category, param_type 
FROM d_items 
WHERE label ILIKE '% temperature %' OR label ILIKE 'temperature %' OR label ILIKE '% temperature' OR label ILIKE 'temperature'
   OR abbreviation ILIKE '% temperature %' OR abbreviation ILIKE 'temperature %' OR abbreviation ILIKE '% temperature' OR abbreviation ILIKE 'temperature';


224674	Changes in Temperature	Changes in Temperature	chartevents	Toxicology	Text
224027	Skin Temperature	Skin Temp	chartevents	Skin - Assessment	Text
224642	Temperature Site	Temp Site	chartevents	Routine Vital Signs	Text
228242	Pt. Temperature (BG) (SOFT)	Pt. Temperature (BG) (SOFT)	chartevents	Labs	Numeric
229236	Cerebral Temperature (C)	Cerebral T (C)	chartevents	Hemodynamics	Numeric
223761	Temperature Fahrenheit	Temperature F	chartevents	Routine Vital Signs	Numeric
223762	Temperature Celsius	Temperature C	chartevents	Routine Vital Signs	Numeric
226329	Blood Temperature CCO (C)	Blood Temp CCO (C)	chartevents	Routine Vital Signs	Numeric

SELECT itemid, label, abbreviation, linksto, category, param_type 
FROM d_items 
WHERE label ILIKE '% pulse %' OR label ILIKE 'pulse %' OR label ILIKE '% pulse' OR label ILIKE 'pulse'
   OR abbreviation ILIKE '% pulse %' OR abbreviation ILIKE 'pulse %' OR abbreviation ILIKE '% pulse' OR abbreviation ILIKE 'pulse';

229770	Resting Pulse Rate (COWS)	Resting Pulse Rate	chartevents	Toxicology	Text
223942	Graft/Flap Pulse	Graft/Flap Pulse	chartevents	Cardiovascular	Text
223936	Radial Pulse R	Radial Pulse R	chartevents	Cardiovascular (Pulses)	Text
223948	Radial Pulse L	Radial Pulse L	chartevents	Cardiovascular (Pulses)	Text
223941	Popliteal Pulse R	Popliteal Pulse R	chartevents	Cardiovascular (Pulses)	Text
223946	Popliteal Pulse L	Popliteal Pulse L	chartevents	Cardiovascular (Pulses)	Text
223949	Ulnar Pulse L	Ulnar Pulse L	chartevents	Cardiovascular (Pulses)	Text
223945	Femoral Pulse L	Femoral Pulse L	chartevents	Cardiovascular (Pulses)	Text
223939	Brachial Pulse R	Brachial Pulse R	chartevents	Cardiovascular (Pulses)	Text
223944	Brachial Pulse L	Brachial Pulse L	chartevents	Cardiovascular (Pulses)	Text
223940	Femoral Pulse R	Femoral Pulse R	chartevents	Cardiovascular (Pulses)	Text
223938	Ulnar Pulse R	Ulnar Pulse R	chartevents	Cardiovascular (Pulses)	Text

SELECT itemid, label, abbreviation, linksto, category, param_type 
FROM d_items 
WHERE label ILIKE '% blood urea nitrogen %' OR label ILIKE 'blood urea nitrogen %' OR label ILIKE '% blood urea nitrogen' OR label ILIKE 'blood urea nitrogen'
   OR label ILIKE '% BUN %' OR label ILIKE 'BUN %' OR label ILIKE '% BUN' OR label ILIKE 'BUN'
   OR abbreviation ILIKE '% blood urea nitrogen %' OR abbreviation ILIKE 'blood urea nitrogen %' OR abbreviation ILIKE '% blood urea nitrogen' OR abbreviation ILIKE 'blood urea nitrogen'
   OR abbreviation ILIKE '% BUN %' OR abbreviation ILIKE 'BUN %' OR abbreviation ILIKE '% BUN' OR abbreviation ILIKE 'BUN';
   
225624	BUN	BUN	chartevents	Labs	Numeric

SELECT itemid, label, abbreviation, linksto, category, param_type 
FROM d_items 
WHERE label ILIKE '% pH measurement %' OR label ILIKE 'pH measurement %' OR label ILIKE '% pH measurement' OR label ILIKE 'pH measurement'
   OR label ILIKE '% arterial pH %' OR label ILIKE 'arterial pH %' OR label ILIKE '% arterial pH' OR label ILIKE 'arterial pH'
   OR label ILIKE '% pH %' OR label ILIKE 'pH %' OR label ILIKE '% pH' OR label ILIKE 'pH'
   OR abbreviation ILIKE '% pH measurement %' OR abbreviation ILIKE 'pH measurement %' OR abbreviation ILIKE '% pH measurement' OR abbreviation ILIKE 'pH measurement'
   OR abbreviation ILIKE '% arterial pH %' OR abbreviation ILIKE 'arterial pH %' OR abbreviation ILIKE '% arterial pH' OR abbreviation ILIKE 'arterial pH'
   OR abbreviation ILIKE '% pH %' OR abbreviation ILIKE 'pH %' OR abbreviation ILIKE '% pH' OR abbreviation ILIKE 'pH';

   
220274	PH (Venous)	PH (Venous)	chartevents	Labs	Numeric
228243	PH (SOFT)	PH (SOFT)	chartevents	Labs	Numeric
220734	PH (dipstick)	PH (dipstick)	chartevents	Labs	Numeric
223830	PH (Arterial)	PH (Arterial)	chartevents	Labs	Numeric
227586	GI pH	GI pH	chartevents	GI/GU	Numeric

SELECT itemid, label, abbreviation, linksto, category, param_type 
FROM d_items 
WHERE label ILIKE '% sodium measurement %' OR label ILIKE 'sodium measurement %' OR label ILIKE '% sodium measurement' OR label ILIKE 'sodium measurement'
   OR label ILIKE '% sodium %' OR label ILIKE 'sodium %' OR label ILIKE '% sodium' OR label ILIKE 'sodium'
   OR abbreviation ILIKE '% sodium measurement %' OR abbreviation ILIKE 'sodium measurement %' OR abbreviation ILIKE '% sodium measurement' OR abbreviation ILIKE 'sodium measurement'
   OR abbreviation ILIKE '% sodium %' OR abbreviation ILIKE 'sodium %' OR abbreviation ILIKE '% sodium' OR abbreviation ILIKE 'sodium';

220645	Sodium (serum)	Sodium (serum)	chartevents	Labs	Numeric
226534	Sodium (whole blood)	Sodium (whole blood)	chartevents	Labs	Numeric
229061	Ertapenem sodium (Invanz)	Ertapenem sodium (Invanz)	inputevents	Antibiotics	Solution
220995	Sodium Bicarbonate 8.4%	Sodium Bicarbonate 8.4%	inputevents	Medications	Solution
225152	Heparin Sodium	Heparin Sodium	inputevents	Medications	Solution
230044	Heparin Sodium (CRRT-Prefilter)	Heparin Sodium (CRRT-Prefilter)	inputevents	Medications	Solution
229597	Heparin Sodium (Impella)	Heparin Sodium (Impella)	inputevents	Medications	Solution
225975	Heparin Sodium (Prophylaxis)	Heparin Sodium (Prophylaxis)	inputevents	Medications	Solution
229861	Sodium Acetate.	Sodium Acetate.	inputevents	Medications	Solution
227533	Sodium Bicarbonate 8.4% (Amp)	Sodium Bicarbonate 8.4% (Amp)	inputevents	Fluids/Intake	Solution
225926	Sodium ACEtate	Sodium ACEtate	inputevents	Nutrition - Supplements	Solution
221211	Sodium Bicarbonate 1,4%	NaBic 1,4%	inputevents	Fluids - Other (Not In Use)	Solution
220467	Sodium (ingr)	Na (ingr)	ingredientevents	Ingredients - general (Not In Use)	Ingredient
228389	Sodium (serum) (soft)	Sodium (serum) (soft)	chartevents	Labs	Numeric with tag
228390	Sodium (whole blood) (soft)	Sodium (whole blood) (soft)	chartevents	Labs	Numeric with tag

SELECT itemid, label, abbreviation, linksto, category, param_type 
FROM d_items 
WHERE label ILIKE '% glucose measurement %' OR label ILIKE 'glucose measurement %' OR label ILIKE '% glucose measurement' OR label ILIKE 'glucose measurement'
   OR label ILIKE '% glucose %' OR label ILIKE 'glucose %' OR label ILIKE '% glucose' OR label ILIKE 'glucose'
   OR abbreviation ILIKE '% glucose measurement %' OR abbreviation ILIKE 'glucose measurement %' OR abbreviation ILIKE '% glucose measurement' OR abbreviation ILIKE 'glucose measurement'
   OR abbreviation ILIKE '% glucose %' OR abbreviation ILIKE 'glucose %' OR abbreviation ILIKE '% glucose' OR abbreviation ILIKE 'glucose';

228692	Glucose Control - Prophy	Glucose Control - Prophy	chartevents	MD Progress Note	Text
226537	Glucose (whole blood)	Glucose (whole blood)	chartevents	Labs	Numeric
225664	Glucose finger stick (range 70-100)	Glucose FS (range 70 -100)	chartevents	Labs	Numeric
220621	Glucose (serum)	Glucose (serum)	chartevents	Labs	Numeric
227978	Boost Glucose Control (3/4)	Boost Glucose Control (3/4)	inputevents	Nutrition - Enteral	Solution
227976	Boost Glucose Control (1/4)	Boost Glucose Control (1/4)	inputevents	Nutrition - Enteral	Solution
227979	Boost Glucose Control (Full)	Boost Glucose Control (Full)	inputevents	Nutrition - Enteral	Solution
227977	Boost Glucose Control (1/2)	Boost Glucose Control (1/2)	inputevents	Nutrition - Enteral	Solution
220395	Glucose (ingr)	Glucose (ingr)	ingredientevents	Ingredients - general (Not In Use)	Ingredient
228388	Glucose (whole blood) (soft)	Glucose (whole blood) (soft)	chartevents	Labs	Numeric with tag


SELECT itemid, label, abbreviation, linksto, category, param_type 
FROM d_items 
WHERE label ILIKE '% hematocrit measurement %' OR label ILIKE 'hematocrit measurement %' OR label ILIKE '% hematocrit measurement' OR label ILIKE 'hematocrit measurement'
   OR label ILIKE '% hematocrit %' OR label ILIKE 'hematocrit %' OR label ILIKE '% hematocrit' OR label ILIKE 'hematocrit'
   OR abbreviation ILIKE '% hematocrit measurement %' OR abbreviation ILIKE 'hematocrit measurement %' OR abbreviation ILIKE '% hematocrit measurement' OR abbreviation ILIKE 'hematocrit measurement'
   OR abbreviation ILIKE '% hematocrit %' OR abbreviation ILIKE 'hematocrit %' OR abbreviation ILIKE '% hematocrit' OR abbreviation ILIKE 'hematocrit';

226540	Hematocrit (whole blood - calc)	Hematocrit (whole blood - calc)	chartevents	Labs	Numeric
220545	Hematocrit (serum)	Hematocrit (serum)	chartevents	Labs	Numeric

SELECT itemid, label, abbreviation, linksto, category, param_type 
FROM d_items 
WHERE 
    label ILIKE '% partial pressure of arterial oxygen %' OR label ILIKE 'partial pressure of arterial oxygen %' OR label ILIKE '% partial pressure of arterial oxygen' OR label ILIKE 'partial pressure of arterial oxygen'
    OR label ILIKE '% oxygen saturation %' OR label ILIKE 'oxygen saturation %' OR label ILIKE '% oxygen saturation' OR label ILIKE 'oxygen saturation'
    OR label ILIKE '% O2 saturation %' OR label ILIKE 'O2 saturation %' OR label ILIKE '% O2 saturation' OR label ILIKE 'O2 saturation'
    OR label ILIKE '% SpO2 %' OR label ILIKE 'SpO2 %' OR label ILIKE '% SpO2' OR label ILIKE 'SpO2'
    OR label ILIKE '% PaO2 %' OR label ILIKE 'PaO2 %' OR label ILIKE '% PaO2' OR label ILIKE 'PaO2'
    OR label ILIKE '% arterial oxygen pressure %' OR label ILIKE 'arterial oxygen pressure %' OR label ILIKE '% arterial oxygen pressure' OR label ILIKE 'arterial oxygen pressure'
    OR label ILIKE '% oxygen partial pressure %' OR label ILIKE 'oxygen partial pressure %' OR label ILIKE '% oxygen partial pressure' OR label ILIKE 'oxygen partial pressure'
    OR label ILIKE '% FiO2 %' OR label ILIKE 'FiO2 %' OR label ILIKE '% FiO2' OR label ILIKE 'FiO2'
    OR abbreviation ILIKE '% partial pressure of arterial oxygen %' OR abbreviation ILIKE 'partial pressure of arterial oxygen %' OR abbreviation ILIKE '% partial pressure of arterial oxygen' OR abbreviation ILIKE 'partial pressure of arterial oxygen'
    OR abbreviation ILIKE '% oxygen saturation %' OR abbreviation ILIKE 'oxygen saturation %' OR abbreviation ILIKE '% oxygen saturation' OR abbreviation ILIKE 'oxygen saturation'
    OR abbreviation ILIKE '% O2 saturation %' OR abbreviation ILIKE 'O2 saturation %' OR abbreviation ILIKE '% O2 saturation' OR abbreviation ILIKE 'O2 saturation'
    OR abbreviation ILIKE '% SpO2 %' OR abbreviation ILIKE 'SpO2 %' OR abbreviation ILIKE '% SpO2' OR abbreviation ILIKE 'SpO2'
    OR abbreviation ILIKE '% PaO2 %' OR abbreviation ILIKE 'PaO2 %' OR abbreviation ILIKE '% PaO2' OR abbreviation ILIKE 'PaO2'
    OR abbreviation ILIKE '% arterial oxygen pressure %' OR abbreviation ILIKE 'arterial oxygen pressure %' OR abbreviation ILIKE '% arterial oxygen pressure' OR abbreviation ILIKE 'arterial oxygen pressure'
    OR abbreviation ILIKE '% oxygen partial pressure %' OR abbreviation ILIKE 'oxygen partial pressure %' OR abbreviation ILIKE '% oxygen partial pressure' OR abbreviation ILIKE 'oxygen partial pressure'
    OR abbreviation ILIKE '% FiO2 %' OR abbreviation ILIKE 'FiO2 %' OR abbreviation ILIKE '% FiO2' OR abbreviation ILIKE 'FiO2';


229239	FiO2 Challenge Result	FiO2 Challenge Result	chartevents	Hemodynamics	Text
229238	FiO2 Challenge	FiO2 Challenge	chartevents	Hemodynamics	Text
229280	FiO2 (ECMO)	FiO2 (ECMO)	chartevents	ECMO	Numeric
229841	FiO2 (CH)	FiO2 (CH)	chartevents	ECMO	Numeric
220227	Arterial O2 Saturation	SaO2	chartevents	Labs	Numeric
223770	O2 Saturation Pulseoxymetry Alarm - Low	SpO2 Alarm - Low	chartevents	Alarms	Numeric
223769	O2 Saturation Pulseoxymetry Alarm - High	SpO2 Alarm - High	chartevents	Alarms	Numeric
226253	SpO2 Desat Limit	SpO2 Desat Limit	chartevents	Alarms	Numeric
220277	O2 saturation pulseoxymetry	SpO2	chartevents	Respiratory	Numeric
223835	Inspired O2 Fraction	FiO2	chartevents	Respiratory	Numeric
229862	Forehead SpO2 Sensor in Place	Forehead SpO2 Sensor in Place	chartevents	Routine Vital Signs	Checkbox

SELECT itemid, label, abbreviation, linksto, category, param_type 
FROM d_items 
WHERE 
    label ILIKE '% pleural effusion on x-ray %' OR label ILIKE 'pleural effusion on x-ray %' OR label ILIKE '% pleural effusion on x-ray' OR label ILIKE 'pleural effusion on x-ray'
    OR label ILIKE '% pleural effusion %' OR label ILIKE 'pleural effusion %' OR label ILIKE '% pleural effusion' OR label ILIKE 'pleural effusion'
    OR label ILIKE '% fluid on x-ray %' OR label ILIKE 'fluid on x-ray %' OR label ILIKE '% fluid on x-ray' OR label ILIKE 'fluid on x-ray'
    OR label ILIKE '% pleural fluid %' OR label ILIKE 'pleural fluid %' OR label ILIKE '% pleural fluid' OR label ILIKE 'pleural fluid'
    OR label ILIKE '% fluid collection %' OR label ILIKE 'fluid collection %' OR label ILIKE '% fluid collection' OR label ILIKE 'fluid collection'
    OR label ILIKE '% effusion %' OR label ILIKE 'effusion %' OR label ILIKE '% effusion' OR label ILIKE 'effusion'
    OR abbreviation ILIKE '% pleural effusion on x-ray %' OR abbreviation ILIKE 'pleural effusion on x-ray %' OR abbreviation ILIKE '% pleural effusion on x-ray' OR abbreviation ILIKE 'pleural effusion on x-ray'
    OR abbreviation ILIKE '% pleural effusion %' OR abbreviation ILIKE 'pleural effusion %' OR abbreviation ILIKE '% pleural effusion' OR abbreviation ILIKE 'pleural effusion'
    OR abbreviation ILIKE '% fluid on x-ray %' OR abbreviation ILIKE 'fluid on x-ray %' OR abbreviation ILIKE '% fluid on x-ray' OR abbreviation ILIKE 'fluid on x-ray'
    OR abbreviation ILIKE '% pleural fluid %' OR abbreviation ILIKE 'pleural fluid %' OR abbreviation ILIKE '% pleural fluid' OR abbreviation ILIKE 'pleural fluid'
    OR abbreviation ILIKE '% fluid collection %' OR abbreviation ILIKE 'fluid collection %' OR abbreviation ILIKE '% fluid collection' OR abbreviation ILIKE 'fluid collection'
    OR abbreviation ILIKE '% effusion %' OR abbreviation ILIKE 'effusion %' OR abbreviation ILIKE '% effusion' OR abbreviation ILIKE 'effusion';

225818	Pleural Fluid Culture	Pleural Fluid Culture	procedureevents	6-Cultures	Processes
