# playground

This repository contains basic experimentation with Named Entity Recognition (NER) methods using pretrained models. The notebooks for these experiments can be found in the `playground` directory.

## Overview

The goal is to test various NER models on the same input text to extract the following entities:

- **Monetary value**
- **Gift type**
- **Department**
- **Gift interval**
- **Names**

### Input Text

All models are tested using the following input:

```
Hello,

I want to set up a yearly scholarship that provides a student with $40,000 if they are in the Price Faculty of Engineering as well as a $10,000 scholarship if they are in Computer Science. I would like to know if this is possible.

Thanks,

Bruce
```

### Models Tested

The following NER models are tested:

1. **spaCy**

   - [Website](https://spacy.io/)

2. **Llama**

   - [Website](https://www.llama.com/)

3. **GLiNER**
   - [GitHub Repository](https://github.com/urchade/GLiNER)
