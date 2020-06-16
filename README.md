# Kikuch-SLE
Distinguishing lupus lymphadenitis from Kikuchi disease based on clinicopathological features and C4d immunohistochemistry

# Prediction of unknown cases
unknown_case.ipynb
Data normalization: sc.pkl
The model recommended: SVMsigmoid.pkl

Please fill in the clinical, histological, C4d IHC parameters in "unknown case2.csv" and upload the csv file for prediction.
G: diagnosis (which should be empty)
C1: Age (years)
C2: Sex (M: 1; F: 0)
C3: Biopsy site (neck: 1; axillary: 2; inguinal: 3; mediastinal: 4; abdominal: 5; pelvic: 6; other site: 7)
C4: Biopsy method (excision: 1; incisional biopsy: 2; excision: 3)
C5: Fever (presence: 1; absence: 0)
C6: Extent of lymphadenopathy (localized: 1; generalized, confined to one side of the diaphragm: 2; generalized, across the diaphragm: 3)
H1: Area involved (%)
H2: Pattern (interfollicular: 1; patchy or confluent: 2)
H3: Hematoxylin bodies (presence: 1; absence: 0)
H4: Azzopardi effect (presence: 1; absence: 0)
H5: Necrosis (presence: 1; absence: 0)
H6: Histiocytic infiltrates in the necrotic area (+/–: 1;+: 2;++: 3)
H7: Germinal centers (presence: 1; absence: 0)
H8: Foamy cell infiltrates (–: 0; +: 1; ++: 2)
H9: Neutrophils (presence: 1; absence: 0)
H10: Plasma cell infiltrates (–: 0; +: 1; ++: 2)
I1: Endothelial staining in necrotic area, positive number (0-3)
I2: Endothelial staining in necrotic area, intensity (0-3)
I3: Perivascular staining in necrotic area (0-1)
I4: Background staining in necrotic area (0-3)
I5: Endothelial staining of capillaries/venules in viable area, positive number (0-3)
I6: Endothelial staining of capillaries/venules in viable area, intensity (0-3)
I7: Endothelial staining of hilar/trabecular vessels, positive number (0-3)
I8: Endothelial staining of hilar/trabecular vessels, intensity (0-3)
I9: Mural staining of hilar/trabecular vessels (0-1)
I10: Endothelial staining of perinodal vessels, positive number (0-3)
I11: Endothelial staining of perinodal vessels, intensity (0-3)
I12: Mural staining of perinodal vessels (0-1)
I13: Staining at germinal centers, positive number (0-3)
I14: Staining at germinal centers, positive rate (0-3)
I15: Staining at germinal centers, intensity (0-3)
I16: Staining at adipocytes (0-1)
