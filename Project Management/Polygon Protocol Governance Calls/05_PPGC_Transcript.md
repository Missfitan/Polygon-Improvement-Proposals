# Polygon Protocol Governance Call (2023-07-13 16:01 GMT+1) - Transcript


### Attendees: 
Alex PFL, Bella Park, Cameron Morris, David Silverman, elouan le grand, Fireflies.ai Notetaker Hyung-K, George Serntedakis, Harry Rook, Harry Rook's Presentation, Jackson Lewis, James Patry-Dodd, John Broadley, Joonkyo Kim, Kasper van der Valk, Lyes Lefgoum, Michael Mugno, Michel Muniz, Mirella Guglielmi, Nimit Bavishi, Pratik Patil, Quentin de Beauchesne, Sandeep Sreenath, Sandeep Sreenath's Presentation, Tanisha Katara, Tiago - Stakin, Tobias Geiger, Tom Murphy, Vaibhav Jindal, Vaibhav Jindal's Presentation, Vedant Patel, WebDev StakeWorks

## Transcript

**This editable transcript was computer generated and might contain errors. People can also change the text after it was created.**

**Harry Rook:** Okay, thank you guys. I think we've got everyone here now, so we can kick it off. Yeah, thank you all for joining. I know a lot of you on different times though. So, yeah, it's nice to see so many faces here again. Yeah, it's on a kick it off by congratulating everyone. All the validators and partners for a successful hard fork on main net on the 11th. So yeah, all validators, run the canonical chain before the hard for block which is good news. So nice, move hard fork. which is always nice. It's always nice to have a boring hard folk.
So, in terms of agenda points for today, we've got David Silverman on a call. Who's gonna be discussing as the proposals that were released for Polygon 2.0. So, that's the CK validium for Pos. And also he's going to touch on the Tokenomics, which were released today. And after this, we're going to jump into a debrief on the Hard fork, that went live on the 11th, a proposed hard fork in the coming months that we called Owlborg
And then we'll finish off by another proposal. That will be voted on by the handle governance module. And, we expect that to take place towards the end of next week.
So yeah, that's a brief of the agenda. And on that I'll hand it over to David's. Do you want to kick it off the 2.0 stuff?
David Silverman: Yeah, thank you so my first time this call, hi all Im I'm from the product team over here at polygon. So a number of weeks, we started off the polygon 2.0 announcements with a pre-pip with the intent of polygon labs. We want to kind of coordinate the community around, upgrading pos to a zk based chain. This being a zk validium which is a type of roll-up technology, very similar to the zke EVM, we are currently running as Zk, EVM with the key difference. That transaction data is not posted to chain in a store with the validators. The only thing post to chain is state roots plus proofs, which allows for incredibly cheap transactional costs.
: over the coming weeks are going to make sure we do proper validator retail, as well as reach out with many other stakeholders. Specifically Oracle providers, s LSTs contract ads that are leveraging. A lot of the existing canonical bridge, contracts to ensure that any initial technical solution, that we put forward for community feedback takes into account. A lot of these steps, the first area we are going to begin looking at for this upgrade is going to be around the bridges themselves. Specifically FX Portal the old POS portal as well as the plasma bridge
Solution uses an entirely different. Bridging interface that is the Lxly bridge for familiarity. We can share documentation it matches with the current specification from zkvm and the first kind of step we see is going to be looking at the upgrade of the bridge itself so that might affect some folks on this the way we kind of are anticipating working with the community is a series of hard forks over the entire course of next year to slowly bring different components of pos to be ready for azk validium upgrade and then conducting. The actual full upgrade to the validium in the back, half of next year, with very much ample testing, This is gonna be a number of steps along the way, the first one that we see coming is just preparing the bridge. Then we will go kind of prepare the validation set from migration to the stakin hub, which is our new kind of a staking mechanism and then there will be a formal migration of the back end consensus.
I'm being intentionally light on technical details, as we kind of want to as the product team, understand, everyone's requirements for their specific role prior to bringing forth the technical solution. And we look forward to working with everyone over the coming weeks, and months to begin the early stages of building out this upgrade and working and testing it. So, that's the very high level again, just for timing perspective. The earliest stages, we will see this go out is in probably, the first hard fork of next year, which will be targeted towards starting to. Again, prepare the plasma POS portal and FX portal bridges for a future upgrade to be compatible with lxl. Why the bridging standard for the ZK world that we are building in the polygon stack?
So that's the high level on zk POS we will be reaching out to many groups directly. I have put for the perform post. Obviously there's a lot of comments from the general community in regard to gas token, etc. However, any specific feedback that you would like to share publicly whether it be on certain direction you wish this to go questions as a validator questions and app developer, we are fully encouraging you to post to the Public Polygon Forum. However, if you wish to reach us at Polygon Labs, please do feel free to reach out either to the governance team or I can even include my own email directly in the product team is always happy to chat and we want to make sure that any initial solution we presentation community, which can be clear will not be the final one takes into account wide feedback. So yeah, that's the opening on Polygon Zkpos. I don't know. Harry anything else you want me to touch on that front?
Harry Rook: Mean it probably a good time for questions. If anyone has any questions? Yeah, probably do. A few quick ones. before we dive into Tokenomics,
Okay cool. Yeah, I mean, David feel free
David Silverman: Yeah, so I'll jump over now to the tokenomic side but just again, the last kind of reminder the first thing that we are explicitly calling out for feedback is if you are a very heavy user of the plasma bridge, that is the oldest bridge on the POS chain. That is the one that actually handles the matic token as well as a few other select tokens. But if you are a heavy user of that, we definitely want to hear from you and talk to you. As that is kind of The first of the three bridges that we are. We are actively looking into again. Our first step is assessing the bridge. Then we will assess the validation migration to staking hub. And then the overall kind of backend consensus change so just a open call out, we're looking for feedback on all of that. But specifically, right now The bridge is starting with plasma. So with that, I'll shift gears to economics
 today several members of the Polygon Labs team posted a proposal for a new foundational token for the polygon ecosystem entitled Pol It Again. I want to be clear. This is a initial proposal upon which we expecting much community feedback and ideally iterations on it. Prior to any development being done in any deployment. I want to be clear that this is not a token that is available today. There is no contract anything, anyone is seeing this token is available or a contract or swap you're being scammed, Please don't lose your apes. let's have some smart Opsec Here. The proposal from these members of Polygon Labs describes a new token poll that is one-to-one peg, two tiago's. A one to one migration. as a inflation schedule of 1% annually for four years. To validators 1% annually.

A community-run treasury for four years. Both of those can be turned off after that four-year mark or they can be continued. I would say it's relatively similar to uniswap in that design the uniswap treasury after four years turns on it has a perpetual 1% or 2%, I forget the exact number permanent annual inflation.
The specifics of that could be read in the white paper. The idea for the poll token is again, it is an ethereum ERC 20 and it is to be the token for the entire ecosystem, of the new 2.0 polygon stock including all Both the two public chains Zeke as well as poss In addition to being The stake token of the staking hub by which any blockchain especially supernets can use to fill different jobs. Whether that be being part of a data availability committee or a DAC, being a sequencer or being part of a decentralized. Prover network, the three main jobs, we believe we will see on the stakin hub. The last main job that will be on the staking hub. Is the interoplayer. This is a zk aggregation layer, that allows for large acceleration on the Lxoi Bridge to give the appearance of unified block space between two connected chains. It works in
Similar form of restaking for those who are familiar with eigen layer, where there is a base condition that you are. Staking matic jobs can be proposed by chains, these jobs can have additional qualifications such as You hold a certain NFT you have a ballot stake balance of some other token. You are on Some job you are supposed to be doing again. We will have templates for DAC, sequencer, prover. And obviously for this interoper layer and then some reward callback. Here's how I'm paying you. We paid out in poly Paid out in other tokens. You can be paid out with delegation included and that allows for you to use your existing polygon steak Across many jobs. Lastly jobs also have slash and criteria to kind of handle negative use cases. So, the kind of purpose of staking Again is just to have a unified place where you can stake once your poll, and then subscribe into the various jobs based as you see fit a clear kind of key thing. I want to make clear about, this is delegation, which is currently a critical point of a part of the existing staking layer. It's actually brought outside the staking layer, is a function of a given job. So there would be some delegation registry that can be done on a per job basis. So, that is a bit of a change from the way existing things operate today. A question. I see any ideas around partial unstickabilities for operators. I don't know if that person wants to unmute and potentially just share more in the chat on their question over there.

**Jackson Lewis:** Yeah, I can jump in the David.
Bring this question. As I know that it's been asked for since Genesis, on pos at the moment,… there's not a partial unstickability, so any validators to self-staking to their node, let's say they self-stake That 10K is locked until they unbond from the network and so on wanting to unstick any amount from their node on that self-stick would unbond them from the network and so was just wondering if there was any chat or ideas around the staking hub, having more of a fluid staking ability where a validated could say, Hey I've had 10K on there for a couple months need to take out two can use it somewhere else etc. Etc.
David Silverman: So as I understand the base, staking hub itself will support that as for whether jobs you subscribe to have additional lockups associated with them, that might be a job by job basis. Definitely want to make sure that we capture that feedback and ensure that's passed along with the team doing initial tech implementation. I would say We are hoping to have a draft implementation of sticking hub, as well. As a few samples of different jobs, probably in the late August period. So definitely would want to make sure that for any validation, let's call we get you access to that as soon as possible. And just already seeing from various thumbs up about the partial on stake. I will bring that back to my team immediately to make sure it's being addressed. Although, I want to confidently, I believe it currently is again.

**David Silverman:** Different jobs can apply different conditions. So this is not like a universal. Yes, or no answer, but we will make sure the base supports this as a concept whether or not the POS validation job or the POS DAC job, or the POS sequence or job supports that will be subject to the community discussion. Given the validators are very strongly support of this feature. if we come to community consensus, I could see that being put in there.
Jackson Lewis: Thank you, this great. And just to confirm there, when you say that individual jobs could have separate rules or lockups, etc. You mean to say from the staking hub, if node, operator was then provide certain services to supernet entities, or certain services in perhaps proving etc, that one or potentially many of those may have separate indications on lockup. Is that what you're referring to them?
David Silverman: Yeah, it's basically each job sets its own requirements. Each job says its own reward structure in its own slashing structure. And so, that's why a you got to don't just default, subscribe to all jobs. There may be conflicting things or at a job can kind of basically say, I want to have some exclusive use of your stake. They're also may require staking of other tokens. So let's say for example, avogachi chain which is a supernet partner and what I'm describing is not, they're staking structure all just using them for purpose of example, Let's say that they said hey in addition to staking a certain amount of all you all need to be staking, a certain amount of ghost through our side contract. That's the way they can assess an additional requirement for a supernetic and potentially be. We are Starbucks. And we are saying that only validators that pass to Kyc check are eligible even in to enter our validation set, regardless of steak size. So before we even start, looking at how much you mistake, you need to clear kyc, or beyond some list, these are very types of state conditions.
They could also require longer lockup because they're slash period is slower. So I would say, the staying ub It's a very generic kind of platform it's designed to be super flexible so I can't speak to what type of jobs may arise. I just want to make it clear to validators. That this is the designs that we are looking for, especially for the public chains, we can make sure our very valuer friendly as the community provides feedback. So that would be my statement on that.
And again to be clear. This is just a proposal from Polygon Labs. this is not the final design or any final answers. I'm speaking exclusively for polygon labs and kind of our ideas. A question from PFL, Can you share some of your thoughts around slashing, the implemented, particularly on the Philidium on the validium where we would see slashing so sequencers. Obviously if the sequencer tries to submit a state route that's invalid that very clearly would be a slashable event. So right, the sequencer provides the ability for applications to kind of if you trust the sequence here you can provide near instantaneous finality. If any of you have used the zka EVM network, the reason most of those apps feel like, I just got confirmation and one or two seconds, even though the actual finality takes about 45 minutes to get the full proof proven on L1.
If all of a sudden the sequence there starts submitting invalid state routes, we're never going to finalize those transactions. And the user effectively is going to have to have the appearance of what's a Reorg. A sequencer should be fully penalized for that. That should be a very slash pull event. And if there's a continued pattern of it, we would probably want to seize the entire stake entirely, right? that is a damaging experience to user. And so, that's a really negative signal that I would look at another one on the data Availability committee situation. If I am a DAC member and I'm just signing saying I'm having data, but users can show that you don't have it or you're a withholding data from users. So they cannot reconstruct Lt State that very clearly should be a slashable event as for approver, If you are taking substantially long times to generate proofs longer than can be reasonably expected, you just start slowing down the network at large slowing down. It's finality that also should be a slashable event. And I think one of the benefits of this new design of staking hub, right? Each of those three rules. I just described DAC, Sequencer and Prover describe three entirely different tech setups, ideally, A DOC just needs to have a dock membership needs to have very good storage capabilities and the ability to serve that storage. Quickly sequencer is a really large complicated box in kind of line with traditional validation and block creation, and Prover needs to have pretty specialized hardware. And so by the other staking hub, If you are an enemy, that's specializes in one of those threes, you could very clearly kind of subscribe to jobs that make sense. So if I'm a, Staker that has a really strong DOC hardware. I can just be on a DAC committee for both public networks and potentially multiple supernets. And just only try to bid on that role because I know I'm gonna do very well there.
Yes, each job and it has affected his its own rules with respect to pos jobs. How do you mention the structure will this? follow the soul away validates with a high stake become active. Do you see current way? we are definitely
Wanting feedback from the value. There's on how we go forward, the initial consensus options we have for each of those sets. Just might be constrained by what is done right now. So for the DAC, it may mean, hey of everyone who has over a certain amount of steak. We periodically elect a small group that small group is the DAC for a given set of epochs almost eat too. In essence, from the overall validation set elect a small group to kind of serve as the people attesting and proposing blocks. It could be a very similar structure for sequencer and for prover as well,
I think we would intend to have it be permissionless standard dpos stake weighted, where it's not just, we're limited to a hundred, we can kind of open that up more. However, I don't want to speak for the community at large. I don't want to speak from a research team, which is coming up with a very much longer paper on a lot of this stuff. Additionally, there are many other community collaborators that are working on. This problem, I would particularly like, to highlight the great folks at oval that have done a tremendous amount of research into distributed value or technology. In addition, how you can have sequencers
Acting to distributed manner between network appear to be a single sequencer. So I think anything that we put forward would just be an initial start and we obviously want to hear from the value of your community to make sure anything we are doing is fair to you all we definitely want to make this be more inclusive. I can guarantee that at least the roles will be no more restrictive than pos as is today. We don't want to take Any steps backward from the centralization aspect? As we do these upgrades at least on the validator side of things.
Any action needed to migrate delegators and valuers from matic to poll at this moment. Absolutely nothing pulled is not exist. I can at least speak on a technical side of things, there are investigations ongoing into and the reason I said, we are looking at the bridges, is there something can be done at the bridge layer particularly on the plasma bridge that will just say, after a certain hard fork block all matic inside of the POS system, just on the bridge, this is not cover validation, just auto converts. And so the gas token will natively kind of convert. It will still be matic inside the network, but from a functional perspective, it becomes full for validators. It's gonna be probably, a longer transition. The exact mechanism is still being designed and we want to make sure that there is absolutely communication between all the various validators, the other tech with the technical team and the community at large to do this transition in the smoothest, easiest, and most equitable manner.
So short answer, no conversion right now, for anyone token does not exist. This is purely a technical paper from polygon labs or a subset of folks of polygon labs. Now it goes to the community to kind of come to an agreement before implementation work begins. Yes, it will be a by slow rollout. If I had to actually guess the Zk, EVM network will probably upgrade to use Poll as it's token before mattock even before the POS network gets there, just to the complexity in size, the POS network.
Any other questions?
Just again to be clear.
Everything that we've laid out over the past couple of weeks of polygon to is just proposals. We've been intentionally light on technical details, it's not to say We don't have them, it's more of. We want to actually receive community feedback without kind of coloring people's opinions. So we're putting out kind of broad strokes as we want, push back on those broad strokes and we want those broad strokes to kind of be challenged in shape by the community before we start even releasing code, we're worried that releasing code would actually just kind of have people feel like we're forcing this upon everyone. We want to be clear. we actually do believe in polygon as a multi-tenant, and a multi-stakeholder community, a large community. This isn't like a unit swap or Hey guys. Here's the V4 and we're going with This is the implementation. This is of. Hey, These are our outline of principles of where we want to take the network next, but we are just one stakeholder There's 2.5 billion dollars worth of delegated steak across multiple values. Want to be fair to them. There's everyone.
Delegating to these holders, want to be fair to them. There's hundreds of thousands of users on every day on the network who want to be fair to them and there's app developers. And we want to be fair to them as well, and make sure everyone's voice is heard so that when we moving forward with consensus and so, again, I think I dropped my email early in there. You can find us on Twitter, you guys have access to the governance team. please share your feedback either directly with us but even better share it on the forum so everyone can see. And take part, we have a lot of great feedback of We want to make sure that OS is still using matic or Paul is the gas token. That's great. We've got a lot of feedback from the community there. We'd love to hear other areas of concern from you all, what parts of this transition, scare you guys the most. So we can make sure that we have the best do the best testing, as well as proper test. Runs of the migration in certain points. So everyone feels comfortable when it's time for the actual hard forks that do the scary changes.

**Harry Rook:** Perfect. thank you for that David's, great explanation. And I'm personally really excited for 2.0 and everything that Is going to come next. And thank you everyone for your questions.So, yeah, next we can move on to a debrief on the indoor fork on mainnet that occurred on the 11th. Yeah I believe Sandeep if you hear be able to cover this. Yes sandeep's here. Yeah, and…

**Sandeep Sreenath:** Yes. Sure.

**Harry Rook:** over to Sandeep.

**Sandeep Sreenath:** Yeah, thanks I'm gonna share my screen. So first of Harry mentioned kudos to the entire community, all the node we had a hundred percent validators who had upgraded before the hard fork so it was really smooth and even the other clients as well including bore as well as Aragon. So all the node operators, that we know had upgraded. So yeah, again thanks a lot for all the cooperation. so I'll move on Obviously, it's very early days, to be frank but we already have a few results that we wanted to share. We're really excited about it. As you all know, the
The Hartford which went live two days back, it had mainly two changes or two big features. One is the parallel execution of transactions, there's the our implementation of Block Hdm and the other one, being the State Singh Bug, which caused, quite a few deeper York's in the last couple of months, especially after the Delhi Hard Fork, which reduce the sprint length to 16 blocks. So yeah, the second one, which is the state sync confirmation delay. It's very hard to measure that because, as we had explained in some of the previous calls, there are multiple conditions, which need to be met in order to read, recreate that scenario where there were deep reorgs and obviously, it has to be done at a particular block as well like the end of the sprint. So it's pretty hard to measure the effect of that. I guess. The only way we can say that it's working is, if we don't find any deeper works going forward, basically because of the same, conditions Regarding parallel execution. We already have some initial results, which I'll be sharing. in the next few minutes.
So yeah, a couple One of the major improvement that we saw is in the execution time as you can see the percentile 99 and 99.9, graphs are mentioned here. We see a reduction of around 40 to 50% in execution time because of the panel execution and

Yeah, so I think the dates that we have, we're considering here is June 28th is when we released the tag and that's when we upgraded, most of our notes. And then July 11th is when we actually had the hard fork, but since this particular change, did not really depend on the hard work because purely or the code changes which came into effect. So you can see the improvement or the reduction in the execution time, After we upgraded the notes. So, these are all the graphs that you can see here.
So as a side effect of this, we also saw lesser number of ears because the decrease in execution time also has another effect which is basically, execution time contributes in the propagation delay and the propagation delay, the lower the number of reach. that's one of the major reasons why we have rex because I've blocked time is just two seconds. And if the block the execution time itself takes, a significant amount of time there's additional, Time which is spent in propagation only after the execution time is done. So since the execution is happening faster, we are able to propagate blocks, sooner to the rest of the network.
And Yeah, is this Like I said, very initial results. So what we are seeing is around 50% reduction in the number of reworks per hour that's really musical from this graph. Yeah, and also we don't see the kind of peaks that we used to see earlier. So I think if my point is visible so you see a lot of these peaks which have definitely smooth and out, after the rollout
Yeah, regarding transaction pool again. Yeah, the TX will react time has reduced after the deployment. AI. this is again, mainly to do with, how much three reorganization is happening within the transaction pool. And this also has an overall effect. Yorks and the execution overall.
Yeah, and again, some more metrics which are supporting the reorgs. Basically, the REORG acts and drops. These are some other metrics that are available in board. Not sure about Eragon, but yeah, INVO I think these metrics are really available which you plotted Also. The number of queued and pending transactions have decreased. As you can see here in these two graphs, these are the queue transactions and these are the pending transactions. Although the value transactions in the transaction pool have remained, pretty much the same, right? So you can see that this is almost the same, but in spite of this, we are seeing lesson number of queued and pending transactions, which is great.
Yeah, I think these are some initial observations that we wanted to share. any questions around this? You have to take them.
All right, so if we do not have any other questions, another short upgrade I wanted to share regarding the album Hard Fork. which is the implementation of PIP 11. As I had updated in the previous call. So we had one Audit which was done in we do not receive a lot of suggestions as such or any major changes but we also had another audit of sorts, basically where a few ethereum researchers were also contributing to those discussions. and so one update there is that there have been a few, suggestions like improvements that they proposed
A few genuine concerns basically on the implementation itself, like a few attack vectors. So we are still actively discussing with them and also we have a few initial solutions in mind, which we are exploring.

And I guess we had some timelines, which we had kind of proposed in the previous call, but it looks like there will be some delay due to all these suggestions because any implementation that we do, no matter how small it is, it requires a lot of testing to be done, as you guys already know about it. so once we are done with the testing on devnets, there's obviously going to be some cool of period and then we take it to Mumbai Network, we observe it for a couple of weeks there and only then mean So yeah, it's hard to tell what the delay is going to be because we are still discussing what changes need to be made, but I think before the next ppgc, we will have some concrete time, right?
Thanks Harry for posting the PIP as well. I think. Yeah, that's pretty much what I wanted to cover is, if Vaibhav is there. I think he can take us to the gardens, the road.

**Harry Rook:** Yeah, definitely. Yeah, thank you Sandeep.

**Harry Rook:** Vaibhav, I was just going to ask quickly. if there's any validators on the call that have any questions, I know you asked already Sandeep about window fork like out settling on their nodes, they've got any queries or any feedback then Yeah, I mean I'll give you guys a couple minutes, if you want to just ask some questions or provide feedback,if there's any feedback want to do async then just shoot me a message. Hit me up on the forum. Yeah, and we can talk about it Apologies very powerful. I'll hand it back over to you.

**Vaibhav Jindal:** No worries. yeah. so I was just want to present the PIP 14, in in which we propose to increase the checkpoint of a time. So before the idea, merge that checkpoint used to take near about 13 minutes nearly Nearly 950 seconds. To get pass on to get confirm on Ethereum. But now after the march it takes me about Or 12 1300 seconds on an average. So to compensate for this, we have increased the checkpoint er From top previously thousand seconds to know. 1500 second. And I just want to present the PIP for this.
So in this PIP 14, We have mentioned, why it was a need to change the checkpoint. But for time, from thousand second to 1500 seconds. And it is backward, compatible. But it to pass this, need to go through the governance. And for this, all of the validators need to vote for it. So actually, if all of you agree with this, we can have the proposal and In the 24 hours of the proposal, every validator have to watch for this. And so I will also come comment on this pip about how to vote. For this proposal.

**Harry Rook:** And in terms of lead time, we think in you mentioned before one week, so, We would give validators one week's lead so you can all check out the proposal only feedback on the forum and then after the seven days. So on the 20th, then it would be uploaded to the Heimdall governance module. And the CLI commands to vote for the validators would be in the comments. Correct me if I've gone wrong there. They have. But just record what we spoke about before. Okay.

**Sandeep Sreenath:** Yeah, that's So the idea is we can Post the proposal on himdal governance, module on the 20th. And there's a 24-hour voting period before which validators will have to put on the proposal. So by 21st, I think we'll have the resulting and since it's on the himdal governance module, there's no manual. intervention required, there's no upgrades needed, it's just a vote, which is through the CLI, we as vibe over as mentioning we will also share the command that you need to run on your aim does here so those instructions will be clear. I think a lot of validators have already voted on multiple proposals. We've had around 10 of them if I'm not wrong on mean So, Yeah, this is going to be pretty simple. But yeah, I want to make sure that the community understands why we are doing this. So, yeah, just story. I reiterate. So since last year, I think around September when ethereum, merge happened. So the number of blocks that we need to wait for confirmation on ethereum chain. Increase Significantly earlier. we were waiting for six to twelve blocks on ethereum, but now, as you all know, it takes around two to three epochs, which is close to around, 1400 to 1500 seconds. As I was mentioning and giving some buffer time we've taken the checkpoint period to be around 1500 seconds. So yeah, why would you want to explain what exactly the checkpoint buffer time is? And,

**Vaibhav Jindal:** Yes. you say would like to explain what is second buffer time? So basically, what happens?
This is one check point if the latest checkpoint has a timestamp acts. So, we would. So every wait for at least x plus 50 are checkpoint buffer time. Before we change the checkpoint. if it has not gone on the theorem, so making into more simpler terms, I can say if the checkpoint has gone at the 120th at one o'clock. And by one o'clock plus checkpoint buffer time. The next checkpoint is not on Then the checkpoint, which is in the er. Can be changed.

**Sandeep Sreenath:** So yeah. Essentially, this is like we have implemented the buffer time for the reason that we don't want the validators to keep proposing, different checkpoint, and then keep invalidating the checkpoint that was there earlier, So, that's the reason why we have a buffer time, because obviously, we all know. It takes quite some time for the checkpoint to get proposed for the voting to happen on him. Dial and then for it to be, posted on to the L1 chain and on L1 that is ethereum chain for mainnet. We never know how long it takes obviously, there are multiple considerations could be how we see the network is what the gas fee has been provided. So that's the reason and obviously there's also this confirmation delay in ethereum which we are talking about that. That's where after the merge there has been a huge increase and we want to kind of Considered factor in all of these things and that's where this 1500 seconds seems to be an optimal value.
Yeah, in any questions regarding this?
Looks like there are none.

**Vaibhav Jindal:** Yeah, if you have any question or in doubt, just please ask the question on the Pip. I would love to answer them as soon as possible.

**Harry Rook:** Thanks we have if there's no questions then that wraps up the agenda so you can all have 30 minutes back of your day. Yeah, just some closing points. The next ppgc will be on the 10th of August where, based on this call can imagine we'll have more details on the album for and PIP 11. So yes, stay tuned for that. And yeah, I hope to see you guys on that next call, and thank you for joining. Bye guys.