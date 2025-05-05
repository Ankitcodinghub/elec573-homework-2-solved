# elec573-homework-2-solved
**TO GET THIS SOLUTION VISIT:** [ELEC573 Homework 2 Solved](https://www.ankitcodinghub.com/product/elec573-homework-2-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;95089&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;ELEC573 Homework 2 Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 0px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            <span class="kksr-muted">Rate this product</span>
    </div>
    </div>
<div class="page" title="Page 1">
<div class="layoutArea">
<div class="column">
This homework focuses on two applications of networks to very different domains: genetics and epidemics. I co-developed the first exercise with Weiyu Huang and Alejandro Ribeiro and the second one with Michael Schaub and Ali Jadbabaie.

Please hand in all of your work, including executable code. The grading is over 100 points distributed as indicated throughout the document.

2.1) Classification of cancer types [35 points]. Let us begin by analyzing a genetic network describing gene-to-gene interactions. The network was downloaded from the NCI Nature database and it is included in the data folder along with this homework. You might want to use the function scipy.io.loadmat() to load the data geneNetwork rawPCNCI.mat in Python. The network consists of 2458 genes and, loosely speaking, two genes are connected if the proteins encoded by them participate in the same metabolism process.

We are going to study the genetic profiles of 240 patients diagnosed with different subtypes of ovarian cancer. We will see that by interpreting these genetic profiles as graph signals defined on the genetic networks, we will be able to clearly distinguish patients from different subtypes. Load the file signal mutation.mat. You will see the aggregated graph signals X ∈ R240×2458. The i-th row of this matrix represents the genetic profile xi for the i-th patient. The n-th gene for this patient is mutated if the n-th entry of xi is 1 and is not mutated (normal) if the n-th entry is 0. Patients diagnosed with the same disease may exhibit different phenotypes, i.e., different variations of the same disease. The most effective therapies for different phenotypes may differ a lot and, for this reason, it is very beneficial if we can distinguish phenotypes based on the genetic profiles. Load the file histology subtype.mat and you will see a vector y ∈ R240 that describes the patients phenotypes. The i-th element is 1 if patient i has serous subtype ovarian cancer and 2 if the patient has endometrioid subtype ovarian cancer. Our goal is to better differentiate between patients with these two subtypes based on graph Fourier analysis.

a) Distinguishing power [10 points]. Take the graph-shift operator to be the Laplacian S = L = VΛV⊤. We want to find the frequencies vk such that the corresponding Graph Fourier Transform coefficient x ̃(k) differs the most between patients with serous subtype and endometrioid subtype. There are many ways to do this, and we consider the following simple heuristic. First compute the GFTs x ̃i = V⊤xi for all patients. Then for each frequency k, define the distinguishing power of vk as

</div>
</div>
<div class="layoutArea">
<div class="column">
􏰂􏰂

</div>
</div>
<div class="layoutArea">
<div class="column">
􏰀􏰀 i:yi=1 x ̃i(k) DP(vk) = 􏰀􏰂

</div>
<div class="column">
i:yi=2 x ̃i(k)􏰀􏰀 􏰃 − 􏰂 􏰀/

</div>
<div class="column">
|x ̃i(k)|,

</div>
<div class="column">
(2.1)

</div>
</div>
<div class="layoutArea">
<div class="column">
􏰀 i1{yi =1}

</div>
<div class="column">
i1{yi =2}􏰀

</div>
<div class="column">
i

</div>
</div>
<div class="layoutArea">
<div class="column">
where 1{·} is the indicator function. In words, DP(vk) computes the normalized difference between the mean GFT coefficient for vk among patients with serous subtype and the mean GFT coefficient among patients with endometrioid subtype. Generate a plot of DP(vk) versus k for all frequency indices k. Also, generate a boxplot of all the values taken by DP(vk).

b) k-NN for classification [8 points]. Implement a k nearest neighbors (k-NN) classifier and perform leave- one-out cross validation. More precisely, implement the following steps:

1) Compute the pairwise Euclidean distance between all pairs of patients using the original graph signals X. 2) For each patient, compare the most common histology of its k nearest neighbors to its actual diagnosis obtained from y.

3) Compute the accuracy of the classifier by aggregating all the comparisons of the previous step. Report the accuracies for k ∈ {3, 5, 7}.

c) Filtering almost all frequencies [7 points]. Consider a graph filter whose frequency response is to only let pass the frequency with the highest distinguishing power, i.e.

􏰁1, ifk=argmaxkDP(vk),

h ̃1(k) = 0, otherwise. (2.2)

</div>
</div>
<div class="layoutArea">
<div class="column">
2-1

</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
2-2 Homework 2 – Due 10/19/21

</div>
</div>
<div class="layoutArea">
<div class="column">
Denote the filtered GFT as x ̃fi and its inverse GFT as xfi . Form a filtered graph signal matrix Xf with each of its rows representing the filtered genetic profile of each patient. Run the k-NN classifier of the previous point but using Xf as your data. Report your accuracies for k ∈ {3, 5, 7}. What do you observe?

</div>
</div>
<div class="layoutArea">
<div class="column">
d) Filtering most frequencies [10 points]. Consider now the more general filter

􏰁1, if DP(vk) ≥ p-th percentile of the distribution of DP,

</div>
</div>
<div class="layoutArea">
<div class="column">
h ̃p(k) = 0, otherwise, (2.3)

</div>
</div>
<div class="layoutArea">
<div class="column">
where p is any real number between 0 and 100. This family of graph filters keep the information conveyed in frequencies that are distinguishable for two subtypes to some extent. The p here is chosen to select the number of frequencies to keep. Run the k-NN classifier on the filtered signals for different values of p. Report your accuracies for k ∈ {3, 5, 7} and p ∈ {0.75, 0.80, 0.85, 0.90, 0.95}.

2.2) Epidemics across the world [65 points]. In this problem we will consider the issue of epidemic spreading on networks and how to prevent their outbreaks. We will consider theoretical and computational aspects of an epidemic model while focusing on a real-world network of global flight connections as our main dataset.

a) Construct a network from the flight data [10 points]. You have been provided with 2 csv files (named airport Nodes GC.csv and airport Edges GC.csv) that contain all the information of all the airports (nodes), and flights (links)1. The edges are directed and weighted, and are proportional to the number of daily flights from one airport to another. You should construct a network G from this data as follows.

<ul>
<li>Read in the edge data and create an initial (directed) network.</li>
<li>We will work with undirected graphs, so form the undirected graph of this network by symmetrizing
its adjacency matrix as follows

Asym = (A + A⊤)/2.
</li>
<li>If the undirected graph obtained is not connected, keep its giant component as your new graph and
work with it from here onwards.

Hint: Note that command networkx.DiGraph.to undirected returns an undirected graph with the same name and nodes and with edge (u, v, data) if either (u, v, data) or (v, u, data) is in the digraph. If both edges exist in the digraph and their edge data is different, only one edge is created with an arbitrary choice of which edge data to use. You must check and correct for this manually if desired, or use other method to obtain the symmetry operation required above.

b) Plot the airport network [10 points]. Plot the flight network, using some of the extra information for the node files: use the longitude and latitude coordinates provided when drawing the nodes, and scale the node size according to their eigenvector centrality. You should take into account the weights of the edges when computing this centrality. You may find it useful as well to adjust the transparency of the edges for visual clarity. Hint: As a sanity check, the two nodes with highest eigenvector centrality (eigenvector normalized to have unit norm) should have the values approximately 0.179 and 0.170.

We will now study an epidemic model on this network, where every node is in one of two states: it is either infected, or susceptible to being infected. We denote the set of the vertices by V = {v1,…,vn} and the adjacency matrix by A = [aij]. The state of node vi at time t ≥ 0 is a binary random variable Xi(t) ∈ {0,1}. The state Xi(t) = 0 (resp., Xi(t) = 1) indicates that node vi is in the susceptible (resp., infected) state. We define the vector of states as X(t) = [X1(t), . . . , Xn(t)]⊤. The state of a node can experience two possible stochastic transitions:

i) Assume node vi is in the susceptible state at time t. This node can switch to the infected state during the time interval [t, t + ∆) with a probability that depends on: (a) an infection rate β, (b) the probability of

1The original dataset was made available by Tore Opsahl and is discussed in the blog postWhy Anchorage is not (that) important: Binary ties and Sample selection. Available at http://wp.me/poFcY-Vw.
</li>
</ul>
</div>
</div>
</div>
<div class="page" title="Page 3">
<div class="layoutArea">
<div class="column">
Homework 2 – Due 10/19/21 2-3 contact with its neighboring nodes Ni = {j | aij ̸= 0} and their states. We can write the probability of this

transition as

Prob[Xi(t + ∆) = 1|Xi(t) = 0,X(t)] = 1 − Πj∈Ni∧Xj(t)=1(1 − βaij). (2.4) We usually have β ≪ 1. Therefore, instead of (2.4), we use the following first-order approximation:

Prob[Xi(t+∆)=1|Xi(t)=0,X(t)]= 􏰃 βaijXj(t). (2.5) j ∈Ni

ii) Assuming that node vi is infected, the probability of vi recovering back to the susceptible state in the time interval [t, t + ∆) is given by

Prob[Xi(t + ∆) = 0|Xi(t) = 1] = γ, (2.6) c) [5 points] Show that the first-order approximation in (2.5) is in fact an upper bound for the original

</div>
</div>
<div class="layoutArea">
<div class="column">
where 0 ≤ γ ≤ 1 is the curing rate. transition probabilities in (2.4).

</div>
</div>
<div class="layoutArea">
<div class="column">
The spread model characterized by (2.5) and (2.6) may be hard to analyze for large-scale networks. One standard approach is to use a mean-field approximation of the model: define pi(t) = Prob[Xi(t) = 1] = E[Xi(t)], i.e., the marginal probability of node vi being infected at time t. We can use (2.5) and (2.6) to approximate the dynamics of pi(t):

aijpj(t) − γpi(t). (2.7)

This approximation is widely used in the field of epidemic analysis and control, since it performs numerically well for many realistic network topologies.

d) Simulating the spread dynamics using the mean-field approximation [20 points]. Suppose that the first 20 nodes (according to their ids in the dataset) are initially infected. Use (2.7) to simulate the evolution of the expected size of the infection defined as p ̄(t) = 􏰂ni=1 pi(t) over time, assuming a recovery rate γ = 0.1 and

an infection rate β = 0.1. (Hint: you can use dpi(t) ≈ pi(t+∆)−pi(t) where ∆ = 0.05 and time horizon [0,5]). dt ∆

Repeat the experiment for β = 0.05 and β = 0.01. Plot three curves (one for each value of β) showing the evolution of the expected size of the infection over time.

It can be shown that a sufficient condition for virus extinction, that is to ensure that the virus will eventually die out, is to have

λmax(A) &lt; βγ . (2.8)

An immunization strategy is to choose a subset of nodes I ⊆ V and immunizing them against the virus. An immunized node can neither get infected nor pass the infection. We call an immunization strategy “effective” if it results in the eventual extinction of the virus (almost surely), no matter how widespread the initial infection is. A potential idea for designing an effective immunization strategy is to rank the nodes based on some centrality measure and immunize them in order of their centralities until the condition (2.8) is satisfied. Note that immunizing node vi is equivalent to removing the i-th row and column from A.

e) [20 points] Assume that β = 0.01 and γ = 0.4. (i) What is the minimum number of immunizations required to satisfy condition (2.8) if you use (weighted) degree centrality to sort the nodes? (ii) What is this minimum number when you use (weighted) eigenvector centrality instead?

In solving this last point, compute a single ranking for the nodes for the complete network and delete nodes one by one until you satisfy the condition (2.8). No need to recompute the centralities after deleting nodes (although that could be another reasonable heuristic).

</div>
</div>
</div>
