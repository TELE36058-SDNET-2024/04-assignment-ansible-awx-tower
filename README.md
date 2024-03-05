# Exploring Automation with Ansible AWX

## Objective
The goal of this assignment is for students to install Ansible AWX, configure it for network automation, and explore its features by creating and executing Ansible jobs. This includes managing inventories, integrating projects from GitHub, and handling credentials within AWX.

## Prerequisites

- Basic understanding of Linux/Unix command line.
- Access to a GitHub account and knowledge of basic Git operations.
- Understanding of YAML and Ansible playbook structures.

## Assignment Outline

### Part 1: Installation of Ansible AWX

#### Objective
Install Ansible AWX on a Ubuntu VM

#### Tasks
1. Deploy Ubuntu VM
2. Clone the Ansible AWX GitHub repository and navigate to the installer directory.
3. Run the installation playbook using Ansible to deploy AWX.
4. Verify the installation by accessing the AWX web interface.

#### Deliverables

Outline of your network Infrastructure lab.

### Part 2: Configuring Ansible AWX

#### Objective
Configure AWX to manage network devices by setting up inventories, credentials, and projects.

#### Tasks
- **Create an Inventory**: Add a new inventory in AWX, naming it `NetworkDevices`, and manually add a couple of mock network devices to it.
- **Set Up Credentials**: Create SSH credentials in AWX for accessing the mock network devices.
- **Create a Project from GitHub**: Link a new project in AWX to a GitHub repository containing Ansible playbooks for network automation.

#### Deliverables
- Screenshots of the Inventory, Credentials, and Project configuration pages in AWX.
- The URL of the GitHub repository used.

### Part 3: Creating and Running Ansible Jobs

#### Objective
Utilize AWX to create and run Ansible jobs for network device configuration.

#### Tasks
- **Create a Job Template**: Using the previously created project, inventory, and credentials, create a job template in AWX.
- **Run the Job**: Execute the job template and monitor its execution in the AWX dashboard.
- **Create Workflow**: Create a workflow that deploys 2-3 different jobs
- **Create a survey**: Create a survey within a job that allows users to input data. Survey should include a list, checkbox and input text.
- **Investigate the Results**: Review the output of the job execution, focusing on how AWX manages task execution and reporting.

#### Deliverables
- A detailed report on the job execution process, including the purpose of the job, the outcome, and any errors encountered.
- Reflection on how the AWX interface and features facilitate the management and execution of Ansible jobs.

### Part 4: Reflection and Exploration

#### Objective
Reflect on the learning experience and explore additional features of AWX.

#### Tasks
- Explore additional features in AWX such as scheduling jobs, setting up notifications, or using dynamic inventories.
- Reflect on the potential of AWX and Ansible for automating tasks beyond network configuration.

#### Deliverables
- A reflective essay on the potential impacts of automation with Ansible AWX in various IT domains.
- A brief exploration report on one additional feature of AWX, including how it could be used in a real-world scenario.

## Evaluation Criteria

- Completeness and accuracy of installation and configuration tasks.
- Ability to create and execute Ansible jobs within AWX successfully.
- Quality and depth of the reflective essays and reports.
- Creativity in exploring and reporting on additional AWX features.
