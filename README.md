# HTML
<!DOCTYPE html>
<html lang="en">

<head>

    <meta charset="UTF-8">

    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <title>System Monitoring Dashboard</title>

    <!-- Bootstrap -->

    <link rel="stylesheet"
        href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css">

    <!-- Google Font -->

    <link rel="preconnect" href="https://fonts.googleapis.com">

    <link
        href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;500;600;700&display=swap"
        rel="stylesheet">

    <!-- Font Awesome -->

    <link rel="stylesheet"
        href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css">

    <!-- CSS File -->

    <link rel="stylesheet" href="style.css">

</head>

<body>

    <!-- Sidebar -->

    <div class="sidebar">

        <div class="logo">
            System<span>Panel</span>
        </div>

        <ul class="menu">

            <li>
                <a href="#">
                    <i class="fa-solid fa-chart-line"></i>
                    Dashboard
                </a>
            </li>

            <li>
                <a href="#">
                    <i class="fa-solid fa-server"></i>
                    Servers
                </a>
            </li>

            <li>
                <a href="#">
                    <i class="fa-solid fa-database"></i>
                    Database
                </a>
            </li>

            <li>
                <a href="#">
                    <i class="fa-solid fa-network-wired"></i>
                    Network
                </a>
            </li>

            <li>
                <a href="#">
                    <i class="fa-solid fa-user-shield"></i>
                    Security
                </a>
            </li>

            <li>
                <a href="#">
                    <i class="fa-solid fa-gear"></i>
                    Settings
                </a>
            </li>

            <li>
                <a href="#">
                    <i class="fa-solid fa-right-from-bracket"></i>
                    Logout
                </a>
            </li>

        </ul>

    </div>

    <!-- Main Content -->

    <div class="main">

        <!-- Topbar -->

        <div class="topbar">

            <div>

                <h1>System Monitoring Dashboard</h1>

                <p>Track your server performance and system health</p>

            </div>

            <div class="profile">

                <div>

                    <h6>Admin User</h6>

                    <small class="text-secondary">
                        System Administrator
                    </small>

                </div>

                <img src="https://i.pravatar.cc/100" alt="profile">

            </div>

        </div>

        <!-- Cards -->

        <div class="row g-4">

            <div class="col-lg-3 col-md-6">

                <div class="stat-card">

                    <div class="icon-box bg-blue">
                        <i class="fa-solid fa-microchip"></i>
                    </div>

                    <div class="card-title">
                        CPU Usage
                    </div>

                    <div class="card-value">
                        72%
                    </div>

                    <div class="small-text">
                        Running smoothly
                    </div>

                </div>

            </div>

            <div class="col-lg-3 col-md-6">

                <div class="stat-card">

                    <div class="icon-box bg-purple">
                        <i class="fa-solid fa-memory"></i>
                    </div>

                    <div class="card-title">
                        RAM Usage
                    </div>

                    <div class="card-value">
                        65%
                    </div>

                    <div class="small-text">
                        Stable memory status
                    </div>

                </div>

            </div>

            <div class="col-lg-3 col-md-6">

                <div class="stat-card">

                    <div class="icon-box bg-green">
                        <i class="fa-solid fa-hard-drive"></i>
                    </div>

                    <div class="card-title">
                        Storage
                    </div>

                    <div class="card-value">
                        81%
                    </div>

                    <div class="small-text">
                        Disk nearly full
                    </div>

                </div>

            </div>

            <div class="col-lg-3 col-md-6">

                <div class="stat-card">

                    <div class="icon-box bg-orange">
                        <i class="fa-solid fa-wifi"></i>
                    </div>

                    <div class="card-title">
                        Network Speed
                    </div>

                    <div class="card-value">
                        920Mb/s
                    </div>

                    <div class="small-text">
                        Excellent connectivity
                    </div>

                </div>

            </div>

        </div>

        <!-- Progress Section -->

        <div class="monitor-card">

            <div class="monitor-title">

                <h3>Server Performance</h3>

                <span class="badge bg-primary">
                    Live Monitoring
                </span>

            </div>

            <div class="mb-4">

                <div class="d-flex justify-content-between mb-2">

                    <span>CPU Performance</span>

                    <span>72%</span>

                </div>

                <div class="progress">

                    <div class="progress-bar bg-primary" style="width:72%">
                        72%
                    </div>

                </div>

            </div>

            <div class="mb-4">

                <div class="d-flex justify-content-between mb-2">

                    <span>RAM Consumption</span>

                    <span>65%</span>

                </div>

                <div class="progress">

                    <div class="progress-bar bg-success" style="width:65%">
                        65%
                    </div>

                </div>

            </div>

            <div class="mb-4">

                <div class="d-flex justify-content-between mb-2">

                    <span>Storage Capacity</span>

                    <span>81%</span>

                </div>

                <div class="progress">

                    <div class="progress-bar bg-warning" style="width:81%">
                        81%
                    </div>

                </div>

            </div>

        </div>

        <!-- Logs -->

        <div class="logs-card">

            <div class="monitor-title">

                <h3>System Logs</h3>

            </div>

<textarea readonly>

[10:02:15] Server started successfully...
[10:04:18] Database connection established...
[10:05:01] Security firewall activated...
[10:07:23] User admin logged in...
[10:10:40] Backup process initialized...
[10:13:11] RAM usage reached 65%...
[10:15:55] CPU temperature normal...
[10:18:32] Network latency optimized...
[10:22:09] Security scan completed...

</textarea>

        </div>

    </div>

</body>

</html>
