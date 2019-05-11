# Probabilistic Graphical Models
A Simple PGM for Medical Decision-Making &amp; Risk

In this project, I create a Bayesian decision theoretic approach to medical diagnosis. I make use of the python library pgmpy, which is a python library for working with Probabilistic Graphical Models. The scenario I imagine is one in which a patient is taking a medication that has certain potential side effects:
1. Rash
2. Hives
3. xerostomia (dry mouth)

Since xerostomia can also be caused by anxiety and the patient suffers from seasonal allergies, we need to determine if the medication is causing her symptoms.