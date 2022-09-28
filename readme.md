This basic idea spawned in my head when relatively recently, when I watched recent descovery by blue brain folks? that some real biological dendrites fire to axon only when two simultaneous inputs to them fired in the same time. 

I.e they kinda worked like logical and  gate. Plus what is more important there was corelation detection per two dendrite connection in one neuron and one axon/neuron has houndreds of them in 

In reality one neron can be pretty dense state machine ? That would also explai how bio can do so much complex logic with so few neurons/layers ? So I started this repo hoping to create simple nn  but with logic gates behind weights. 

Could this be all they need without the need of any sort of gradient descent and backprop ? 

Can they "learn new things" just by selecting or pruning gates ? 

How?

Well basic observation from those observing biological nerons essetially was one sentence.

"if it fires together then it wires together"

Also recent observation from human brain project was that neurons grow and connect pretty much in random directions and connections form just by bumping to each other.

Perhaps we should grow random connections from time to time and prune those where we are notdetecting firing together.

That we you have high order hierarchical corelation detection, infinite scalability since you keep growing but also pruning locally irrelevant signels

Plus I wanna test this as spiking networks too.

Why?

I feel frequencies and especiially phise/timing play important role in nn inputs. 

I.e gard truth is that in the end 

Recently nerf needed to reintroduce sinuses to input to be actually able to learn and converge. 

Transformers detto. Needed to introduce sinuses as positional encoding also. 

But sadly. Even our best like gpt3 has no idea about time and context, 

I.e what it produced 3s ago.Perhaps transformers need time introduced in positional encoding where mont year day sec will all just be sin frequencies encoding when input happened? In biological neurons we actually observed exactly that ? 

So why not work with frequencies and time as first class cityzens in a first place. after all evolution is not dumb if from all possible just binary spiking networks survived then there must be energy efficiency reason for it. with frequencies you get all the weird and wonderful world of standing reflected absorbed negated waves.

And gradients and vawes are basic building block in 3d biological topology probably for energy conserving ? reason too ?. I.e thats how any living 3d organ is shaped from lowest molecule = 3d gradients and waves. 

As for which gates to use.
It turns out you actually need just one. 

NAND 

And can pretty much create all 7 possible known logical circuits from it just by witing bunch of nands in specific way
![](What-are-basic-logic-gates-figure-3.webp)

Therefore basic building nlock of our new hopefully spiking (but compared to biological ones not limited to just 5khz) network would be this.
Lets call it GateTron
![gatetron?](gatetron.webp)

there is weight also between two inputs in otder to work as negation  by shortcircuiting two nand inputs. 
But this seems stupid perhaps having and or not everywhere is better energy wise better than this stupid aditional switch weight?

Hmm Also...
When you think about it. looking at typical biological neruon with all those hundreds complex dendritic connections no all meeting in one point byt via some kind of structure.

Structure not that different from half of autoencoder.
Isnt dendritic half of neuron actually half of atypical hourglass autoencoder architecture?

Isn't there actually dimensionality reduction happenin in simmilar higher order feature detection way happening too?
Isn't therefore each neuron actially miniature autoencoder too ?

