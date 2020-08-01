<h1>Project 1: Blight payment prediction</h1>
<ul>
  <li>Project type: Classification</li>
  <li>Project goal: Predict if a fine will be payed or not.</li>
  <li>Data shape: 250306x34</li>
  <li>Models: Naive Bayes, Logistic regression, Support vector classifier, Random forest, XGBoost</li>
  <li>Model evaluation: Area Under the ROC Curve</li>
  <li>Course: University of Michigan Applied Data Science</li>
  <li>Notebook path: UMich_applied_machine_learning/fine_payment_prediction</li>
</ul>

<h3>Insights</h3>
<ul><li>Compliance is quite low in general but some agencies (Police department) have higher compliance rates.
  <img src="UMich_applied_machine_learning/fine_payment_prediction/compliance.png" alt="Compiance">
  <img src="UMich_applied_machine_learning/fine_payment_prediction/agency.png" alt="Compiance">
  </li>        
    <li>Getting any form of discount increases compliance</li>
  <img src="UMich_applied_machine_learning/fine_payment_prediction/effect_of_discount.png" alt="Compiance">
</ul>

<h3>Results</h3>
<table>
    <tr>
        <th>Classifier</th>
        <th>ROC area</th>
    </tr>
    <tr>
        <td>Naive Bayes</td>
        <td>0.71</td>
    </tr>
    <tr>
        <td><strong>Logistic Regression</strong></td>
        <td><strong>0.78</strong></td>
    </tr>
    <tr>
        <td>KNN</td>
        <td>0.61</td>
    </tr>
    <tr>
        <td>SVM (linear)</td>
        <td>0.56</td>
    </tr>
    <tr>
        <td>SVM (rbf)</td>
        <td>0.58</td>
    </tr>
    <tr>
        <td>Random Forest</td>
        <td>0.68</td>
    </tr>
    <tr>
        <td>Xtreme Gradient Boosting</td>
        <td>0.61</td>
    </tr>
</table>

