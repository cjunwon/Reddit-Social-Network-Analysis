# Reddit-Social-Network-Analysis

Classifying posts and comments within large graph structures. Project for DataRes Research (UCLA), Winter 2023 - led by Junwon Choi, <em>B.S. Data Theory, 2024</em>.

The presentation explaining the full project structure and results during our Winter 2023 Demo Day can be found [here](https://github.com/cjunwon/Reddit-Social-Network-Analysis/blob/master/DataRes%20Research%20-%20Winter%202023%20Slides%20(Group%204).pdf).


## TABLE OF CONTENTS

* [Background](#background)
* [Objective](#objective)

<hr>

## BACKGROUND
A community on any social network platform or forum can be represented through a network. In the real world, a person's particular affiliation/engagement with certain subcommunity can be determined based on various features (demographic, use of language, activities, interests). A composition of such similar people can be identified as a subcommunity. In this project, we attempt to efficiently discover subcommunities (and their changes) using the pure graph structure of an entire forum platform (Reddit), avoiding the use of language other categorical feature detection models. This project also performs node classification on new posts/comments.

<hr>

## OBJECTIVE

* Collect community data and set up environment
  * Pull in community data using PyTorch Geometric (Reddit dataset)
  * Connect to remote workstation through SSH (sponsored by AI Safety at UCLA)
* Test and validate various community detection models
  * GraphSAGE
  * Graph Attention Networks
  * FlashAttention

## TOOLS
**Language Used:** Python
<table style="width:100%">
  <tr>
    <th>Task</th>
    <th>Technique</th> 
    <th>Tools/Packages Used</th>
  </tr>
  <tr>
    <td>Data Collection</td>
    <td>Pull in Reddit dataset from PyTorch Geometric pacakage, including nodes, edges, features, classes</td> 
    <td>PyTorch Geometric</td>
  </tr>
  <tr>
    <td>Data Pre-processing</td>
    <td>Subset dataset for handling and testing</td> 
    <td>numpy</td>
  </tr>
  <tr>
    <td>Model Implementation</td>
    <td>Extracted objects within cover art using TensorFlow object detection. Implmented Artistic Style Transfer with TensorFlow Lite & OpenAI's DALL-E2 model to generate user-specific cover art.</td> 
    <td>PyTorch, GraphSAGE, Graph Attention Networks, FlashAttention</td>
  </tr>
  <tr>
    <td>Model Evaluation</td>
    <td>Compare model performances for community detection</td> 
    <td>PyTorch, scikit-learn, Matplotlib</td>
  </tr>
</table><br>
