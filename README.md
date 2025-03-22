# Integrating Black Scholes Framework with Deep Learning Network Architecture for Enhanced Options Pricing
The work presents a hybrid approach that integrates the classical Black–Scholes model with deep learning methods. By incorporating Black–Scholes outputs as additional features in a neural network model, the research demonstrates improvements in option pricing accuracy—offering a robust alternative to both the traditional analytical method and stand-alone deep learning approaches.

This is an individual research done by Aaditya Raj Trivedee through Gerald and Carol Vovis Center for Research and Advanced Study under the guidance of Prof. Petko Kitanov (PhD), Mathematics Faculty, Knox College.

---

## Repository Structure
```
├── PDF
│   ├── blsc.pdf
│   ├── blsc_architecture_call.pdf
│   ├── blsc_architecture_put.pdf
│   ├── extract_data.pdf
│   ├── general_architecture_call.pdf
│   └── general_architecture_put.pdf
├── Models
│   ├── generalarch_call.h5
│   ├── generalarch_put.h5
│   ├── hybrid_call.h5
│   └── hybrid_put.h5
├── blsc.ipynb
├── blsc_architecture_call.ipynb
├── blsc_architecture_put.ipynb
├── extract_data.ipynb
├── general_architecture_call.ipynb
└── general_architecture_put.ipynb
```
---
### Key Findings

- The deep learning model achieves lower MAE compared to the traditional Black–Scholes method.
- The hybrid model, incorporating Black–Scholes outputs, further reduces pricing errors, though gains are modest due to inherent approximation errors in the classical model.
- The approach is effective for both call and put option pricing while maintaining computational efficiency.

---
**Clone the Repository:**

   ```bash
   git clone https://github.com/AadityaTrivedee/research-blackscholes-dnn.git
   cd research-blackscholes-dnn
 ```
---
### Usage
***Data Extraction:***
Execute extract_data.ipynb to collect and clean the options data.

***Model Evaluation:***
- Run blsc.ipynb for baseline Black–Scholes model evaluation.
- Use general_architecture_call.ipynb and general_architecture_put.ipynb for normal deep neural network architectures.
- Use blsc_architecture_call.ipynb and blsc_architecture_put.ipynb to evaluate the hybrid model for call and put options.

---
### Contact
**Aaditya Raj Trivedee**  
Knox College  
Email: [artrivedee@knox.edu](mailto:artrivedee@knox.edu)
