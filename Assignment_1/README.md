# Multi-scale-Modeling-of-Biological-Systems
Assignment group 6

Important Note: our submission is under the name "assignment_metabolic_modelling.ipynb", the other ipynb files within the folder were used to avoid merge conflicts.







AI DISCOLSURE: 

ex4 a)
having some issues loading the model

def ensure_model():
    if 'model' in globals() and model is not None:
        return model
   
  try:
        m = io.load_json_model('e_coli_core.json')
        return m
    except Exception as e:
        raise RuntimeError(
            "No in-memory constrained `model` found and failed to load 'e_coli_core.json'. "
            "Re-run your Exercise 2 cell to build the constrained model, or place e_coli_core.json "
            "in the working directory."
        ) from e


        <img width="816" height="627" alt="Screenshot 2025-09-12 at 21 50 34" src="https://github.com/user-attachments/assets/213b0547-9a50-46fe-a233-640dc57381b8" />
