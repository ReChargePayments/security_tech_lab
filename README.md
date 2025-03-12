# Recharge Security Engineering Tech Lab

## Intent

The tech lab is a new part of Recharges' interview process. As a result, we appreciate any feedback regarding this approach and thank you for taking the time to complete one of these!

The intent isn't to coerce you into unpaid labor or waste your time; it's to help us understand how you approach problem solving and validate your technical abilities without turning the technical interview into a game of "stump the chump"

### DOs and DONTs

- DO submit the homework as if you were giving it to a coworker for code review.
- DO aim for a clear and concise MVP for your solution.
- DO follow directions and solve just the problem in front of you. There's no need to over-engineer the solution.

- DON'T submit multiple solutions. Choose the approach and language you feel is best.
- DON'T include unit tests. We won't run them.
- DON'T worry about handling arbitrary input, unless the assignment explicitly requires input validation.

## Labs

The first two steps must be done for the tech lab to be considered complete.  Additional steps are optional, and it will not count against you if you do not have the time or do not wish to do them.  Consider them "extra credit" and a place to show off a little.



1. [Mandatory] The `syslog` directory contains a lab where you will configure a syslog client and a forwarder to move specific container logs into an object storage bucket
1. [Mandatory] In the same directory, develop a python script that interacts with the log bucket and logs per the documented requirements
2. [Optional] In the `terraform` directory, you will modify a terraform file to add WAF protection to a load balancer and deploy it
1. [Optional] In the same directory, write a script that tests the WAF rules, then check logs to validate


## Deliverables

* Follow the instructions in the `README.md` file in each lab's directory. All of your work per lab should be done within that directory.
* Your git commits and code comments should clearly communicate your intent and choices made while completing the tasks.
* Add notes on running your solution and why you choose your particular solution in a `COMMENTS.md` file in each lab's directory. Remember, you are working with a remote team. Written communication is important!
* Finally, submit all of the above via a Pull Request against the repo. This is what will be referenced during the Tech Lab review.
