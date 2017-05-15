Meeting Notes 2014-08-05 
 These are the notes from the [https://www.noisebridge.net/wiki/Category:Meeting_Notes The 320th Meeting of Noisebridge]. Note-taker: John; Moderator: Naomi.
* '''Proposed consensus item: "If the Sudo Room hackerspace in Oakland bans a person from their space for reasons of safety, that person is immediately and automatically banned from Noisebridge."'''

= Attendance =
* Naomi: Sleepy from exercise; internal monologue is monotone at the moment.
* Adrienne - Reading the Grapes of Wrath; regrets it.
* Matt: Dust; coughing; requests beer and tacos.
* Henner: Working on RFID access control stuff; can maybe hook it up to phones.
* John: Taking notes; hosts 5MoF; does other things (???).
* Patrick: Helping out with the reboot; mostly networking stuff and whatever idle hands can be put to.
* Torrie: Is getting paid to be a full-time cryptoanarchist starting next week.
* Daniella &amp; Mark: [Present in other room.]
* Jarrod: [Present very briefly.]

= Short announcements and events =
* Matt says we're on track for the fundraising party.
* John volunteered to do a workshop on basic crypto tools for the class-a-thon.
* [https://www.noisebridge.net/pipermail/tor/2014-March/000173.html DuckDuckGo has donated $10,000 to Noisetor.]
* John will add treasury notes when he has the deets.

= [[ Membership Binder ]] =
* Daniel Lewis, week one.
* Q-Bit, past twelve weeks, application is pulled.
* Jarrod, week three (because of Reboot time warp), two sponsors.
* Xavier, past twelve weeks, no sponsors, application pulled.
* Tristan Mosley, week two, zero sponsors.

= Financial Report =
* Funds in bank: Dunno.
* Noisetor: $10,000 from DuckDuckGo, plus unknown additional amount.

= Consensus items =

== [[ Consensus Items History | Proposals from last week ]] ==
''(Add any items which pass or are blocked to the [[Consensus Items History]] page.)''

== [[ Current Consensus Items | Proposals for next week ]] ==
'''If the Sudo Room hackerspace in Oakland bans a person from their space for reasons of safety, that person is immediately and automatically banned from Noisebridge.'''

= Discussion Notes =

Naomi: Our agenda is to change the meeting format to make meetings more fun. Or at least make them less horrible. Only consensus proposal is revoking Tom's membership, but he's not present, so setting that aside.

Henner: [Discusses access control terminal that can have multiple peripherals.] Keypad, RFID reader. Upstairs at the door, an RFID reader.

Naomi: RFID all the things. Any RFID-enabled card?

Henner: Clipper cards are an option. There was a Kickstarter once with an NFC ring, same frequency, but it's pretty sucky.

Matt: We have micro-RFID chips.

Henner: We have people who inject it in your hand. Keyfobs will work, Clipper cards will work, and other RFID readers that are pretty cheap (50 for $20). Noisebridge branded RFID? We can grant access through a terminal in the space -- possibly with two members vouching for a person to get access. All that would be similar to the old system is the IDs, maybe e-mail addresses. Anyway: The terminal is mostly done, only need to add the keypad.

Matt: Are we still going to use the phone keypad?

Henner: Yes, phone is essentially a keypad.

Naomi: Is the top lock going to have any time of day characteristics?

Henner: What I got is an electric strike. Will need someone to put it in the frame. Requires dremelling. Strike works with AC and DC. For Tuesday meetings and classes, can keep the door open for X number of hours. Door will no longer need to be propped open. Other times, you would present your card and it would buzz. I need to play with it.

Naomi: Can we put NFC tags on things?

Henner: You can use an NFC tag to get into the door, but it has to be close proximity. RFID could be used for tools, books, and so on. We could combine that with something that takes a picture when a tool goes out the door. Computer would be a Raspberry Pi mounted near the door, so we don't have another cable going to Minotaur. Still connected to network so it's possible to login. Might implement Noisebridge API, but that needs to be re-established.

Naomi: Andy had some fun ideas to apply to this project, but you should just keep on installing stuff and we'll soup it up over time.

Matt: What do you do as far as security measures for the Raspberry Pi?

Henner: Close it down sufficiently like a regular attendance machine.

Naomi: As moderator, I would like to see if there are any more discussion topics. No? Meeting was approximately 32 minutes long.

[Meeting re-opens.]

[Discussion of reciprocal banning. Anyone banned from Sudo Room is banned from Noisebridge, and vice versa.]

Matt: Can we pull up their exact wording?

Consensus Proposal: "If the Sudoroom hackerspace in Oakland bans a person from their space for reasons of safety, that person is immediately and automatically banned from Noisebridge."

Torrie: Proposed and passed at Sudo Room due to concerns about Joe Black.

Naomi: Does anybody have anything they want to discuss?

Adrienne: Can we discuss how awesome it is?

Patrick: There's a limit for only people banned for safety.

Matt: I think it's a concern over privacy and violent behavior.

Torrie: Sudo Room has a special safe space policy. Similar to anti-harassment policy at Noisebridge.

Patrick: Is it safety of persons or safety of property in the space?

Torrie: Could we circumvent the whole issue by saying someone should be considered for banning from Noisebridge if banned from Sudo Room?

Matt: The only thing I don't like about it is one hackerspace could play favorites. Maybe we should specify safety for oneself or the community.

Patrick: Refers to definition of "safe space" on Wikipedia.

Matt: There was discussion of bringing up bannings first in safe-space working group before weekly meeting. That way it's just a consensus item rather than a debate in the meeting.

Naomi: No more, "Go away and come back to the Tuesday meeting."

Matt: "Go away and come back to the Monday meeting."

Torrie: Inculturation before being part of group.

Naomi: If SSWG had to have quorum of three or four, make sure at least three people are experienced.

Matt: There's not a whole lot to it, and hopefully we won't have to do it every week.

Naomi: What if someone asks someone to leave and come back to a SSWG meeting, how do we handle it if there isn't a weekly meeting?

Adrienne: Is this related to original discussion?

Matt: Yes, because it relates to how we handle banning.

Torrie: I like holding meetings as necessary.

Matt: I think it should be up for debate again.

Naomi: From UX perspective, asking someone to leave and come back to SSWG meeting, what happens then?

Torrie: Have two people cosign?

Matt: We definitely wanted a failsafe on asking people to leave.

Naomi: Why?

Matt: It's the responsibility of the two parties to work it out, and if they can't, to bring someone else into it.

Naomi: I don't like this.

Matt: Keeps it from becoming a weapon.

Naomi: How often has it happened?

Matt: I've seen it four times in the past two months. Dan and Monad did it -- reciprocal asks to leave.

Torrie: Whoever draws quickest.

Matt: Ease it back to requiring two people since other people in the space would hear or see it. I've seen it two times where it was kind of shaky.

Naomi: But what's the actual harm? You may be causing someone harm by making this requirement.

Matt: How so?

Naomi: People who are harassed don't want to walk around and talk about how they were harassed. Shouldn't put the onus on them to convince other people it happened. It's not a big deal to have to leave if asked. It's an inconvenience.

Matt: Sometimes it creates a bigger situation if people refuse to leave.

Naomi: And then it becomes a clear indication that person shouldn't be here.

Matt: The intention is that people don't use it as a weapon.

Naomi: I don't think it has been as huge a problem as it is being made out to be. In light of the harm it does to make this policy more complicated, I don't think that it's worth it. One of the features of this policy is that it's really clear and really simple. There are undesireable situations that arise from it, but when you look at how they play out, they don't cause a lot of harm -- permanent physical or emotional harm.

Matt: The only retort I have to that is that sometimes the person asking the other person to leave doesn't have the physical prowess to ask them to leave. Some people refuse to leave and are willing to fight about it. Looking at it as a way to involve the community.

Naomi: You can do that without setting a requirement.

Matt: Better to involve community before things get out of hand than after.

Torrie: This person banned at Sudo Room -- it took three of us to get him to get out, because he was incredibly stubborn.

Naomi: And I think that's a feature of the policy. It puts a point that that person would become a bigger problem. When people abuse the policy it's pretty tame. When someone abuses the policy...

Matt: Early warning device.

Naomi: I think it's worth talking it out with other people. This is a small group.

Matt: I've just seen it being really embarassing for people sometimes, being asked to leave.

Matt: Adding to consensus proposal, add that it's for violations of Sudo Room's safe-space policy.

Torrie: They follow their rules until they don't make sense. If the rules they make are too encumbering, they can just not listen to the rules.

Naomi: Safe space before ideology.

Torrie: It helps easily undo stuff that power-tripping people start doing.

Naomi: I have something to show and tell about! We used to use the beginning of meetings for Show &amp; Tell. This is a card from Digium. Two phone-line inputs, two phone-line outputs. On FSO and FXS. We can run our own little PDX. You can plug in a playphone to one of these and a DSL phone. Plug it into an Asterisk-running computer. Need to get a computer running, and want to use the Pony rack since it's so fuck-off huge. I like the idea of a payphone mounted in as many hackerspaces as possible, and have a hackerspace payphone network. We can also use tones to "sieze trunks" and unlock the doors.

Adrienne: Are we back to whistling into the modem?

Naomi &amp; Torrie: Yes!

Matt: I have huge plans for the phone downstairs. Squirt guns and servos.

Adrienne: Drunk dialing.

Matt: 8-Bit video game songs when you enter the name of the game into the keypad.

Naomi: Doc Pop would help you with that.

[Meeting closed for the second and final time as note-taker's battery runs out of charge.]

[[Category:Meeting Notes]]