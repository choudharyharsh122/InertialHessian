# InertialHessian

The code contains three notebook files.

1) test_algos_synth_reg_quad : A comparison for three first order algorithms for a quadratic loss function for a regression problem. The features are generated with a given mean and covariance. The true underlying relationship to learn is Y = MX, the results are compared over Populaton loss

2) test_algos_synth_class_quad : A comparison for three first order algorithms for a quadratic loss function for a classification problem. The features are generated with a given mean and covariance. There are two class labels 0 and 1 and the results are compared over population loss.

3) test_hessian_synth : The file has plots depicting the convergence rates over 25 randomly initialized weight vectors.
