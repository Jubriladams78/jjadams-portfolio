# jjadams-portfolio
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Enterprise Linux Admin Portfolio Project</title>
  <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@4.6.1/dist/css/bootstrap.min.css">
</head>
<body class="bg-dark text-light">
  <div class="container py-5">
    <header class="mb-4">
      <h1 class="display-4 text-info">Enterprise Linux Infrastructure: Automation & Monitoring Suite</h1>
      <p class="lead">A hands-on project demonstrating advanced system administration skills for enterprise environments.</p>
    </header>
    
    <section>
      <h2>Project Overview</h2>
      <p>Deploy a production-grade Linux infrastructure featuring automated provisioning (Ansible), central monitoring (Prometheus/Grafana), and backup management (Bacula). This project simulates tasks common in an 8-year professional sysadmin role.</p>
    </section>

    <section>
      <h2>Step-by-Step Execution</h2>
      <ol>
        <li>
          <strong>Lab Setup:</strong>
          <ul>
            <li>Deploy 3 VMs (CentOS/Ubuntu) in a virtual or cloud environment.</li>
            <li>Configure networking, hostnames, and secure SSH access.</li>
          </ul>
        </li>
        <li>
          <strong>Automation with Ansible:</strong>
          <ul>
            <li>Install Ansible, clone playbooks, and create inventories.</li>
            <li>Automate tasks: user creation, security patching, service setup.</li>
          </ul>
        </li>
        <li>
          <strong>Monitoring with Prometheus & Grafana:</strong>
          <ul>
            <li>Deploy node exporters, set up Prometheus server.</li>
            <li>Create Grafana dashboards for live system metrics.</li>
          </ul>
        </li>
        <li>
          <strong>Backup Management:</strong>
          <ul>
            <li>Install Bacula, configure backup policies.</li>
            <li>Automate nightly backups and test restoration procedures.</li>
          </ul>
        </li>
        <li>
          <strong>Security Hardening:</strong>
          <ul>
            <li>Apply CIS benchmarks, password policies, and sudo auditing.</li>
            <li>Set up file integrity and vulnerability scans.</li>
          </ul>
        </li>
        <li>
          <strong>Reporting & Documentation:</strong>
          <ul>
            <li>Generate automated daily/weekly status reports in HTML/PDF.</li>
            <li>Document all processes for future admins and portfolio reviewers.</li>
          </ul>
        </li>
      </ol>
    </section>

    <section>
      <h2>Sample Commands & Snippets</h2>
      <pre>
# Run automated user provisioning
ansible-playbook users.yml -i hosts

# Install node exporter
sudo apt install prometheus-node-exporter

# Backup with Bacula
bconsole -c /etc/bacula/bconsole.conf

# Check and harden SSH
sudo nano /etc/ssh/sshd_config
# PermitRootLogin no
      </pre>
    </section>

    <section>
      <h2>Results & Value</h2>
      <ul>
        <li>Automated deployment shortens onboarding for new infrastructure.</li>
        <li>Centralized monitoring and alerting enables rapid incident response.</li>
        <li>Robust backup/recovery procedures protect critical business data.</li>
        <li>Security hardening minimizes risk and meets audit requirements.</li>
      </ul>
    </section>
    
    <footer class="mt-5">
      <p class="text-secondary">Project by <a href="https://github.com/Jubriladams78" class="text-info">Jubril Adams</a>. Source available on GitHub.</p>
    </footer>
  </div>
</body>
</html>
