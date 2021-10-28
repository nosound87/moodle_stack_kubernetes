# moodle_stack_kubernetes

Full description will be created soon.

Short information:
Stack is working without Ingress (just only testing on localhost - I use NodePort to access moodel panel on web interface, and ClusterIP to connection between platfrom and DB)

Default login and password to access dash is:
login: admin
Pass: q1w2e3r4

You need to check NodePort servie which port mapping default 8080 web interface (i.e. 31843) and connect in your browser to access web interface moodle (i.e http://yourhost:31843)
