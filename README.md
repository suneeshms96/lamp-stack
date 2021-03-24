########Installing  lamp-stack using ansible-galaxy#########

We can ansible role using the ansible-galaxy command line tool, We can create a role with the init command: "ansible-galaxy init roll-dir-name" it will create a directory named "roll-dir-name" and we can see the roll stucture in the directory created.
=================
]$ tree 
.
├── defaults
│   └── main.yml
├── files
│   └── index.html
├── handlers
│   └── main.yml
├── meta
│   └── main.yml
├── README.md
├── tasks
│   ├── configure.yml
│   ├── install.yml
│   ├── main.yml
│   └── service.yml
├── templates
├── tests
│   ├── inventory
│   └── test.yml
└── vars
    └── main.yml
==================

Its very easy to create and for re-use.


