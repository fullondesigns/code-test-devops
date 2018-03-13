Ravelin Code Test For DevOps
============================

## Summary
We need an HTTP server that will accept a GET request to `https://LoadBalancer-IP-Address/` and return.
```javascript
{"foo": "barr"}
```

## Requirements
* Use n1-standard-1 Preemptibles.
* Ensure the environment is completely secure.
* The server machines scale at 40% CPU.
* Feel free to use nginx/apache or SimpleHTTPServer.
* Return the correct headers.
* If a server dies, rebuild and re-add to the LB.
* Minimum size of server auto-scaling group = 2 and max = 10.
* Please send a README.md, once the test in complete, explaining your process.

## Network Diagram
![alt text](https://raw.githubusercontent.com/unravelin/code-test-devops/master/network-diagram.png)

## Bonus Points
Please complete the above test manually first - in case you run out of time. If you have experience with the below technologies, for bonus points, please feel to use them and send us the code.
* Configuration management (e.g. puppet, chef, ansible)
* Terraform
* Bastion (a.k.a Jump Box)
* NAT

