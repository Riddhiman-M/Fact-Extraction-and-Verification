# Fact-Extraction-and-Verification
Given a user query, the relevant facts from the [FEVER](https://fever.ai/dataset/fever.html) dataset, supporting or refuting the claim is extracted and displayed

Overview of the project: [Slides](https://docs.google.com/presentation/d/e/2PACX-1vSnswIecQbgyUyBhz-nVNT6yQ7OGUTlY0IQjaxn7c9qw1pFEs945JCPuS8CoqyCFySrs5hx3h-dFu2w/pub?start=true&loop=true&delayms=30000)

The necessary installations have been added in the [Colab Notebook](https://colab.research.google.com/drive/1vfIKrgQ7jaROns5BAEd_4dk5pKwJgolg) itself. So, it can be run directly.

### Description
Fact or claim verification is a two-step process. First, you retrieve supporting or refuting evidence related to a claim. Then based on the set of evidence snippets, the task is to determine whether the claim is true or false. In this project, we are interested in the first step, i.e., evidence retrieval.

### Observed Improvements in fact extraction result:

<b> Simple String Matching Model</b>:         
 <img src="https://user-images.githubusercontent.com/89708853/207301842-7f8b316c-d8b8-4e4a-99dd-3d9eacceed80.png" width=80% height=80%>
 
<b> Our Model</b>:<br>
 <img src="https://user-images.githubusercontent.com/89708853/207302597-32fb3f27-b441-4959-a37f-14b68e5eb58e.png" width=80% height=80%>
