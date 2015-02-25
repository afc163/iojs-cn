---
layout: post
title: io.js 项目管理守则
author: iojs team
reference: https://github.com/iojs/io.js/blob/v1.x/GOVERNANCE.md
---

# io.js 项目管理守则
-------

## 技术委员会

io.js 项目将由技术委员会简称 ( TC ) 的成员们共同监督和管理，保持 io.js 项目的统一性。

TC 拥有这个项目的最终权威，其中包括：

* 项目的技术方向
* 项目管理守则和制定方针
* 贡献着的权利和义务
* GitHub 项目库的管理
* 保持行为准则
* 增加或减少项目的合作伙伴

技术委员会的初期会员来自于一直对 io.js 项目积极和热衷的优秀贡献者，和对于io.js项目有显著管理经验的成员。所有技术委员会会员将有资格
对 io.js 项目发表自己的意见。

技术委员会的初期会员列表，请参阅[这里](https://github.com/iojs/io.js/blob/v1.x/README.md#current-project-team-members)。

## 优秀贡献者

[iojs/io.js](https://github.com/iojs/io.js) GitHub 项目库的管理将由技术委员会会员和热衷的合作伙伴共同完成。技术委员会将有权利增加更多的合作伙伴。

优秀贡献者花费了大量的时间和精力为了 io.js 项目的成功，技术委员会将回馈及肯定这些优秀贡献者，并给予 GitHub 项目库的初级管理员的身份。优秀贡献者并且参与与技术委员会会员小组会议的权利和讨论议题。

注意事项：假如你贡献了很多有效的代码，但并没有初级管理员的身份，请直接联系任何一个技术委员会成员，下一次技术委员会会员小组会议将讨论把你的代码加入到 io.js 项目中。

[iojs/io.js](https://github.com/iojs/io.js) GitHub 项目库的文件及其内容的管理，将在一个共同团队协作的基础上完成。每一个有GitHub帐户的会员都可以提出自己认为对的修改方案，每个修改方案都会由技术委员会会员及对项目了解的资深优秀贡献者们共同认真及严谨的审核及校对，至少有两个以上的资深管理员批准，才能通过，以保证项目的高质量。如果在审核及校对修改方案的过程中，资深管理员们不能达成共识，请仔细参照[促进达成共识的守则](./促进达成共识的守则)。

假如某个修改方案有着显著的争议，而且促进达成共识的守则并没有明确的说明，合作伙伴们可以选择提交这个修改方案到技术委员会，通过给这个修改方案这个标签 ***tc-agenda***，技术委员会通过会议方式做出最后的仲裁。

技术委员会的所有会员列表，请参阅[这里](https://github.com/iojs/io.js/blob/v1.x/README.md#current-project-team-members)。

假如你想成为项目的合作伙伴，请参阅[这里](https://github.com/iojs/io.js/blob/v1.x/README.md#current-project-team-members)。

A guide for Collaborators is maintained in
[COLLABORATOR_GUIDE.md](https://github.com/iojs/io.js/blob/v1.x/COLLABORATOR_GUIDE.md).

## 技术委员会成员守则

TC seats are not time-limited.  There is no fixed size of the TC.
However, the expected target is between 6 and 12, to ensure adequate
coverage of important areas of expertise, balanced with the ability to
make decisions efficiently.

There is no specific set of requirements or qualifications for TC
membership beyond these rules.

The TC may add additional members to the TC by a standard TC motion.

A TC member may be removed from the TC by voluntary resignation, or by
a standard TC motion.

Changes to TC membership should be posted in the agenda, and may be
suggested as any other agenda item (see "TC Meetings" below).

No more than 1/3 of the TC members may be affiliated with the same
employer.  If removal or resignation of a TC member, or a change of
employment by a TC member, creates a situation where more than 1/3 of
the TC membership shares an employer, then the situation must be
immediately remedied by the resignation or removal of one or more TC
members affiliated with the over-represented employer(s).

## 技术委员会小组会议

The TC meets weekly on a Google Hangout On Air. The meeting is run by
a designated moderator approved by the TC. Each meeting should be
published to YouTube.

Items are added to the TC agenda which are considered contentious or
are modifications of governance, contribution policy, TC membership,
or release process.

The intention of the agenda is not to approve or review all patches,
that should happen continuously on GitHub and be handled by the larger
group of Collaborators.

Any community member or contributor can ask that something be added to
the next meeting's agenda by logging a GitHub Issue. Any Collaborator,
TC member or the moderator can add the item to the agenda by adding
the ***tc-agenda*** tag to the issue.

Prior to each TC meeting the moderator will share the Agenda with
members of the TC. TC members can add any items they like to the
agenda at the beginning of each meeting. The moderator and the TC
cannot veto or remove items.

The TC may invite persons or representatives from certain projects to
participate in a non-voting capacity. These invitees currently are:

* A representative from [build](https://github.com/node-forward/build)
  chosen by that project.

The moderator is responsible for summarizing the discussion of each
agenda item and send it as a pull request after the meeting.

## 促进达成共识的守则

The TC follows a
[Consensus Seeking](http://en.wikipedia.org/wiki/Consensus-seeking_decision-making)
decision making model.

When an agenda item has appeared to reach a consensus the moderator
will ask "Does anyone object?" as a final call for dissent from the
consensus.

If an agenda item cannot reach a consensus a TC member can call for
either a closing vote or a vote to table the issue to the next
meeting. The call for a vote must be seconded by a majority of the TC
or else the discussion will continue. Simple majority wins.
