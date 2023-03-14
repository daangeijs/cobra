:html_theme.sidebar_secondary.remove:


COBRA
==============



.. grid:: 1

    .. grid-item::
        :class: sd-text-white sd-bg-primary sd-pt-3

        Classification Of Basal cell carcinoma, Risky skin tumors and Abnormalities

.. grid:: 1

    .. grid-item::


This documentation will give more insights of the COBRA dataset hosted on AWS

- Dataset Size: 0.66TB
- Contact Name: Daan Geijs
- Institution name: Radboud University Medical Center
- Institution URL: www.diagnijmegen.nl
- Download at AWS: https://registry.opendata.aws/cobra/

**Introduction**

This dataset comprises over 6,000 medical images of histopathology whole-slide-images from basal cell carcinoma skin cancer, the most commonly diagnosed cancer. The dataset includes biopsies and excisions and is divided into four groups. The first group contains about 2,500 BCC biopsies with subtype labels, while the second group includes 2,500 non-BCC biopsies with different types of skin dysplasia. The third group has 1,000 labelled risky tumor biopsies, including rare and dangerous types like melanoma, squamous cell carcinoma, and Merkel cell carcinoma. Finally, the fourth group contains 1,000 BCC excisions with or without free tumor margins, with 300 fully annotated. The dataset will be released over the year in stages, starting with the BCC and non-BCC biopsies, followed by BCC excisions, and finally the risky tumor biopsies.

**Optimization**

To optimize this dataset for cloud usage, the highest resolution spacing of 0.24 mu/pixel was removed from the images, and JPEG compression was applied. The images were then stored as .TIF fi les. This optimization significantly reduced the fi le size while preserving the medical data necessary for proper analysis.

This work is licensed under a
[Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License][cc-by-nc-sa].










.. toctree::
    :hidden:

    ./installation/index
    ./dataset/index
    ./tools/index
