# Facial Age Estimation Datasets

## Dataset Characteristics Table

| Dataset | Size | Age Range | Image Format | Label Format | MAE (years) | Diversity/Nationality | Ground Truth Quality | Pose Variations | Expression Handling | Access |
|---------|------|-----------|--------------|--------------|-------------|-----------------------|----------------------|-----------------|---------------------|--------|
| **IMDB-Cleaned** | \~250k images | 0-100+ years | JPEG, various resolutions | Real age (years) | 4.8-6.2 | Mainly celebrities, Western bias | High - cleaned from IMDB-WIKI using clustering | Limited, mostly frontal | Some variation | GitHub |
| **UTKFace** | 23,707 images | 0-116 years | JPEG, cropped faces | Age, gender, ethnicity | 3.2-5.2 | 5 ethnicities: White (42%), Black (19%), Asian (14%), Indian, Others | High - manually verified | Large variation in pose, expression, illumination | Good expression diversity | Kaggle, GitHub |
| **MORPH-II** | 55,134 images | 16-77 years | High resolution JPEG | Real age (years) | 2.0-3.6 | Unbalanced - African American majority, some Caucasian | Very High - controlled collection | Limited, mostly frontal | Limited expressions | Research license |
| **FG-NET** | 1,002 images | 0-69 years | Color & grayscale | Real age (years) | 2.8-4.7 | Small size, mainly Caucasian | High - longitudinal data | Some pose variation | Natural expressions | Research access |
| **AFAD** | 165,501 images | 15-40 years | JPEG, uncontrolled | Real age (years) | 3.2-4.9 | Asian focus, limited diversity | High - social network verified | Large pose variations | Good expression coverage | GitHub, Research |
| **CACD** | 163,446 images | 14-62 years | Variable quality JPEG | Estimated age from timestamps | 4.9-6.5 | Celebrity bias, mixed ethnicities | Medium - estimated from photos | Variable poses | Celebrity expressions | Research access |
| **FairFace** | 108,501 images | 0-70+ years | High quality JPEG | Age groups (7 ranges) | N/A (classification) | **Excellent** - 7 balanced ethnic groups | High - balanced collection | Good pose variation | Diverse expressions | GitHub |
| **APPA-REAL** | 7,591 images | 0-95 years | JPEG with face crops | Real + apparent age | 3.6-4.2 | Mainly European/Western | Very High - crowdsourced apparent age | Limited pose variation | Natural expressions | Research license |
| **AgeDB** | 16,488 images | 1-101 years | JPEG, manually collected | Real age (years) | 4.5-5.8 | Celebrity bias (actors, writers, scientists, politicians) | Very High - manually annotated, noise-free | Variable poses and expressions | Natural expressions | Research access |
| **LAGENDA** | 67,159 images (84,192 persons) | 0-95 years | JPEG from Open Images | Real age (years) | 3.8-4.2 | **Excellent** - minimal celebrity, real-world diversity | Very High - crowdsourced with strict controls | Large pose variations | Diverse real-world expressions | Research access |
| **WebFace** | 494,414 images | 1-80 years | Variable quality | Age labels | 5.0-7.0 | Global collection, good diversity | Medium - web scraped | Large variation | Mixed quality | Web scraping |
| **YGA** | 8,000 images | 0-93 years | Outdoor photos | Real age (approximate) | 4.5-6.0 | Asian majority | Medium - outdoor collection | Natural poses | Natural expressions | Limited access |

## Dataset Relationships and Derived Datasets

**Datasets Built from Other Datasets:**

- **IMDB-Cleaned**: Derived from IMDB-WIKI using constrained clustering to remove noisy labels
- **LAGENDA**: Built from Open Images Dataset with additional age/gender annotations
- **UTKFace**: Ground truth estimated using DEX algorithm (from IMDB-WIKI) and manually verified
- **FaceAge (Medical Research)**: Uses both IMDB-WIKI and UTKFace for training