<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Avinash Kumar Portfolio</title>
    <style>
        body {
            background-color: #1e1e1e;
            color: #00ff00;
            font-family: 'Courier New', Courier, monospace;
            display: flex;
            flex-direction: column;
            align-items: center;
            margin: 0;
            padding: 20px;
        }
        .container {
            background-color: #262626;
            width: 100%;
            max-width: 800px;
            border: 3px solid #f5f17ce9;
            padding: 20px;
            box-sizing: border-box;
        }
        .section {
            margin: 10px 0;
            background-color: #2e2e2e;
            padding: 15px;
            border: 2px solid #a90586;
            box-sizing: border-box;
        }
        .personal-details {
            display: flex;
            justify-content: space-between;
            align-items: center;
        }
        .personal-details .details {
            flex: 1;
        }
        .personal-details img {
            height: 100px;
            width: 100px;
            border-radius: 50%;
            margin-left: 20px;
        }
        .experience ul, .languages-tools .skills {
            list-style-type: none;
            padding: 0;
        }
        .experience li {
            margin: 5px 0;
        }
        .languages-tools .skills {
            display: flex;
            flex-wrap: wrap;
            gap: 15px;
            justify-content: center;
        }
        .languages-tools .skills img {
            height: 30px;
            width: 30px;
        }
        h2 {
            text-align: center;
            color: #00bfff;
        }
        .highlight {
            color: #00bfff;
        }
    </style>
</head>
<body>
    <div class="container">
        <!-- Personal Details Section -->
        <div class="section personal-details">
            <div class="details">
                <p><strong class="highlight">Avinash Kumar</strong></p>
                <p>Mob: +91 9955136036</p>
                <p>Email: avinash2001aiuch@gmail.com</p>
                <p><strong class="highlight">Bachelor of Technology (B.Tech)</strong></p>
                <p>National Institute Of Technology Nagpur (VNIT)</p>
            </div>
            <img src="assets/Avi_photo.jpg" alt="Profile Photo">
        </div>
        
        <!-- What Work I Do Section -->
        <div class="section experience">
            <h2>What Kind Of Work I Do</h2>
            <ul>
                <li><strong class="highlight">Infrastructure & Cloud:</strong> Proficient in managing Linux-based infrastructure, utilizing Docker, Kubernetes (K8s), Terraform, and Ansible for efficient deployment and scaling.</li>
                <li><strong class="highlight">Automation & CI/CD:</strong> Experienced in automating workflows with Jenkins, GitLab CI/CD, and Azure CI/CD, ensuring rapid and reliable software delivery.</li>
                <li><strong class="highlight">Networking & Security:</strong> Skilled in configuring Nginx, Traefik, HAProxy for robust networking, and implementing security measures with Vault and IPFire.</li>
                <li><strong class="highlight">Monitoring & Logging:</strong> Proficient in setting up monitoring solutions with ELK stack (Elasticsearch, Logstash, Kibana), Grafana stack, and Prometheus for proactive system management.</li>
                <li><strong class="highlight">Development & Scripting:</strong> Strong in C, C++, Python programming languages, and Bash scripting for automating tasks and optimizing system performance.</li>
                <li><strong class="highlight">Cloud Platforms:</strong> Experienced in AWS and Azure cloud platforms for scalable and cost-effective infrastructure solutions.</li>
                <li><strong class="highlight">Version Control & Collaboration:</strong> Utilizing Git for version control, enabling efficient collaboration and code management.</li>
                <li><strong class="highlight">Additional Skills:</strong> OpenStack, Pgbouncer, Envoy Proxy, Keepalived, Docker Compose, and managing private PyPI servers, HFS, FTP, and SMTP servers.</li>
            </ul>
        </div>
        
        <!-- Languages and Tools Section -->
        <div class="section languages-tools">
            <h2>Languages and Tools</h2>
            <div class="skills">
                <img src="https://upload.wikimedia.org/wikipedia/commons/1/18/C_Programming_Language.svg" alt="C Logo" title="C">
                <img src="assets/cpp3-svgrepo-com.svg" alt="C++ Logo" title="C++">
                <a href="assets/python-svgrepo-com.svg"><img src="assets/python-svgrepo-com.svg" title="Python"></a>
                <a href="assets/python-svgrepo-com.svg"><img src="assets/bash-icon-svgrepo-com.svg" title="Bash"></a>
                <a href="https://cdnlogo.com/logo/git_40194.html"><img src="assets/git-svgrepo-com.svg" alt="Git Logo" title="Git"></a>
                <a href="https://cdnlogo.com/logo/git_40194.html"><img src="assets/gitlab-svgrepo-com.svg" alt="Git lab Logo" title="Gitlab"></a>
                <a href="https://cdnlogo.com/logo/git_40194.html"><img src="assets/github-color-svgrepo-com.svg" alt="Git hub Logo" title="Github"></a>
                <a href="assets/linux-svgrepo-com.svg"><img src="assets/linux-svgrepo-com.svg" alt="linux logo" title="linux"></a>
                <a href="https://cdnlogo.com/logo/docker_39450.html"><img src="assets/docker-svgrepo-com.svg" alt="Docker Logo" title="Docker"></a>
                <a href="https://cdnlogo.com/logo/kubernets_40312.html"><img src="assets/kubernetes-svgrepo-com.svg" alt="Kubernetes Logo" title="Kubernetes"></a>
                <a href="https://cdnlogo.com/logo/aws_29177.html"><img src="assets/aws-svgrepo-com.svg" alt="AWS Logo" title="AWS"></a>
                <img src="assets/azure-svgrepo-com.svg" alt="Azure Logo" title="Azure">
                <img src="assets/azure-devops-svgrepo-com.svg" alt="Azure dev Logo" title="Azuredevops">
                <a href="https://cdnlogo.com/logo/ansible_14048.html"><img src="assets/ansible-svgrepo-com.svg" alt="Ansible Logo" title="Ansible"></a>
                <a href="https://cdnlogo.com/logo/jenkins_31565.html"><img src="assets/jenkins-svgrepo-com.svg" alt="Jenkins Logo" title="Jenkins"></a>
                <img src="assets/terraform-icon-svgrepo-com.svg" alt="Terraform Logo" title="Terraform">
                <a href="https://cdnlogo.com/logo/nginx_51821.html"><img src="assets/nginx-svgrepo-com.svg" alt="Nginx Logo" title="Nginx"></a>
                <a href="https://cdnlogo.com/logo/traefik_123462.html"><img src="https://www.cdnlogo.com/logos/t/39/traefik.svg" alt="Traefik Logo" title="Traefik"></a>
                <a href="https://cdnlogo.com/logo/traefik_123462.html"><img src="assets/envoyproxy-svgrepo-com.svg" alt="envoy Logo" title="envoy"></a>
                <img src="assets/openstack-icon-svgrepo-com.svg" alt="OpenStack Logo" title="OpenStack">
                <a href="https://cdnlogo.com/logo/grafana_47505.html"><img src="assets/grafana-svgrepo-com.svg" alt="Grafana Logo" title="Grafana"></a>
                <a href="https://cdnlogo.com/logo/prometheus_5211.html"><img src="assets/prometheus-svgrepo-com.svg" alt="Prometheus Logo" title="Prometheus"></a>
            </div>
        </div>
    </div>
</body>
</html>
