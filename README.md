# Machine-learning-interpretability-Research

I've been working with Aurélia DOLO on "Machine learning Interpretability/Explainability" and here you could find :

- a detailed report about the state of the art of "machine learning interpretability"
- a presentation (in French) which sums up the report and where we also proposed theoretically a novel method going beyond the current state of the art called

CAMEL ( Clustering bAsed Model-agnostic ExpLnations )
where we aimed to tackle the current problems of ML interpretability raising from LIME , DeepLIFT , LRP , SHAP etc .... :

1) gradients based methods suffered from saturation , discontinuities , ReLU could not backprop negative signals (grad = 0)
2) sampling/perturbation based methods problem where we could generate unrealistic datapoints (Ex a house of 9m2 having 50 rooms)
3) drastic interpretability variations for a very small change on a point x

I hope it could help for those who will tackle the ML interpretability/Explainability problem one day !
