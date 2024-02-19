# 1 Internet Banking System

![diagram](https://www.plantuml.com/plantuml/svg/0/fPJ1Jjj048RlaV8Eqnog89damgcdGeXA4848Xq9FQBoUn5lMkzREE05LVVTgrubnA1M7dYpF_ZlppUyPVsL1BtLf-hrFsYfJvmI5ICLVncEFsz5QIr5dDPDNpWfP6IbNZZ7t6kt6r5KzdfmSBmnQkPjVZGqAiOmd9uyJPmMr9J-gOl9-x-hqnytTyl5-jhnul9f-crwV3uz2V46UdHrMcKfWqBoWWJEqJzgkOLApk9By8871AQZT6xWLI46GeNrAOAkbW6f_CyG0bNAr5HuDZlgzz8M5oiVfimo94nXCZqlK1ZY6G-9bGQ2ja0_tvrfvnsubC7rM1Ter0NKll4rPPY7d7BLTUIof9K_RzAauJmnep9vRET_01w6sA-TB5EqiOEPgQTlaf6qa0V5e6LMGSG8agWjovcgRetyPwaWpYysGx646H_2htmC0QB_BS8i93EufWzEgCbh5-e7s9suGqEQGLZxWpRzFGlYSZDwGvyZFWg8Lx4OYggNraAHjZRLT6u8ArmJuMYQI7z9m5N3IHhy8-dUmM7bTDUNGhck3SImMtcrqlZFuNOnLRQDlQBIyWBXNWs6ZCTpH7hQKGURTbic_mrS6lBdBj8baeUu3bkYrFKG0eqijb0FN6PE0a_z0AfjwkqTE6wte7ROy2zy71JDa2ZYtPB193limfAgW4ZlZ67OQFAqrYs-6hpE82HJ81UM0jHHaPVSXG7dAmokQPZQ96OnRTmRo40qh7HPtCVltb4btobeZFp0iU8HmcTvSZo-MomMSBcQnUbF_banJEQvxIZRdtGvpD62-NEnHMscpndTCKV8mlug9qxzqqUnRmfpXCsoz5c8G5-vSdfzDklAmOCrOxtUdUnfF6dlsHTjs3ggM7-X-Xww3CFv1urRlXQscFMvuudatNBwD1kEQF_A1Uw7JetxlAzay_jN_0000)

**Level 2: Container diagram**

Once you understand how your system fits in to the overall IT environment, a really useful next step is to zoom-in to the system boundary with a Container diagram. A "container" is something like a server-side web application, single-page application, desktop application, mobile app, database schema, file system, etc. Essentially, a container is a separately runnable/deployable unit (e.g. a separate process space) that executes code or stores data.

The Container diagram shows the high-level shape of the software architecture and how responsibilities are distributed across it. It also shows the major technology choices and how the containers communicate with one another. It's a simple, high-level technology focussed diagram that is useful for software developers and support/operations staff alike.

**Scope**: A single software system.

**Primary elements**: Containers within the software system in scope.
Supporting elements: People and software systems directly connected to the containers.

**Intended audience**: Technical people inside and outside of the software development team; including software architects, developers and operations/support staff.

**Notes**: This diagram says nothing about deployment scenarios, clustering, replication, failover, etc.