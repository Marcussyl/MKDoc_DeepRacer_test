# Creating Community Race

You can create a community race via [this](https://us-east-1.console.aws.amazon.com/deepracer/home?region=us-east-1#communityRaces) link

## Community Race vs Student Community Race

| Community race      | Student community race                          |
| ----------- | ------------------------------------ |
| Race takes place in AWS Console       | Race takes place in AWS DeepRacer Student. Students need an AWS DeepRacer Student account  to access the race.  |
| Event creator can take part in the race       | Event creator can not take part in the race |
| Up to 2 competition formats    | Classic race format |
| Up to 3 race types | Time trial race type |
| 61 race tracks | 20 race tracks |

## Live Race vs Classic Race

|   Test    | LIVE                          | Classic |

| ----------- | ------------------------------------ | -------------------------------- |
| Synchronicity       | real-time racing event, players taking turns to compete  | asynchronous event |
| Public/ Private?       | private or public | private (invitations required) |
| Model submission   | last model submitted will be counted | unlimited model submission |
| Special features | interactive speed controls; twitch streaming is available through AWS DeepRacer League production playbooks | results and videos for submitted models are viewable as soon as the race is initiated |

## Fine Tune the Hyperparameters

## Multi User Mode

Multi-user mode account setup provides an exciting way for organizations to sponsor multiple AWS DeepRacer participants under one AWS account. Sponsored participants do not incur any of their own expenses; instead, their training hours and storage costs are billed to the sponsoring AWS account. With a multi-user mode account setup, AWS DeepRacer event organizers can set budgets and monitor and control spending by updating default quotas on training hours and models for individual participants, groups, or across all participants.

Multi-user mode is particularly useful for large events with multiple participants who don't have individual AWS accounts. Instead of creating and managing accounts for each participant in an event, an AWS DeepRacer administrator can host all of their sponsored participants through a single AWS account.

In multi-user mode, sponsored participants can compete and train without incurring any of their own costs. Their training and storage charges are billed to the sponsoring multi-user AWS account billing. If an administrator stops sponsoring participants' usage, participants keep their racer aliases and profiles.
