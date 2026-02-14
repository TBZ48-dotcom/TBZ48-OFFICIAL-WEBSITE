<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>TBZ48 Official Portal</title>
    <style>
        :root {
            --blue-light: #e0f2fe;
            --blue-main: #0ea5e9;
            --blue-dark: #0369a1;
            --team-t: #3b82f6;
            --team-b: #dc2626;
            --team-z: #f472b6;
        }

        body {
            font-family: 'Segoe UI', Arial, sans-serif;
            margin: 0;
            background-color: #f8fafc;
            color: #334155;
            line-height: 1.6;
        }

        header {
            background: white;
            padding: 30px 20px;
            text-align: center;
            border-bottom: 5px solid var(--blue-main);
            position: sticky;
            top: 0;
            z-index: 1000;
        }

        .logo-area h1 { margin: 0; font-size: 3rem; color: var(--blue-dark); letter-spacing: 8px; }
        
        .leadership-box {
            background: var(--blue-light);
            display: inline-block;
            padding: 10px 20px;
            border-radius: 50px;
            margin-top: 15px;
            font-weight: bold;
            color: var(--blue-dark);
        }

        nav {
            margin-top: 20px;
            display: flex;
            justify-content: center;
            gap: 20px;
            flex-wrap: wrap;
        }

        nav a {
            text-decoration: none;
            color: var(--blue-dark);
            font-weight: 600;
            padding: 8px 15px;
            border-radius: 5px;
            transition: 0.3s;
        }

        nav a:hover { background: var(--blue-main); color: white; }

        .container { max-width: 1200px; margin: 40px auto; padding: 0 20px; }

        h2.section-title {
            text-align: center;
            border-bottom: 2px solid #ddd;
            padding-bottom: 10px;
            margin-top: 60px;
            color: var(--blue-dark);
        }

        /* TEAM GRID */
        .team-card {
            background: white;
            border-radius: 15px;
            padding: 25px;
            margin-bottom: 30px;
            box-shadow: 0 4px 15px rgba(0,0,0,0.05);
        }

        .team-header { display: flex; align-items: center; gap: 20px; margin-bottom: 20px; }
        .team-logo { width: 80px; height: 80px; border-radius: 10px; }

        .member-list {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(150px, 1fr));
            gap: 15px;
        }

        .member-item {
            background: #f1f5f9;
            padding: 10px;
            border-radius: 8px;
            font-size: 0.9rem;
            text-align: center;
        }

        /* DISCOGRAPHY TABLE */
        .scroll-box {
            overflow-x: auto;
            background: white;
            padding: 20px;
            border-radius: 15px;
        }

        table { width: 100%; border-collapse: collapse; margin-top: 10px; }
        th, td { text-align: left; padding: 12px; border-bottom: 1px solid #eee; }
        th { background: var(--blue-light); color: var(--blue-dark); }

        .center-tag {
            background: #dcfce7;
            color: #166534;
            padding: 2px 8px;
            border-radius: 4px;
            font-size: 0.8rem;
            font-weight: bold;
        }

        footer {
            background: var(--blue-dark);
            color: white;
            text-align: center;
            padding: 40px 20px;
            margin-top: 100px;
        }

        .gen-stats {
            display: flex;
            justify-content: center;
            gap: 20px;
            flex-wrap: wrap;
            margin-bottom: 30px;
        }

        .stat-badge {
            background: white;
            padding: 10px 20px;
            border-radius: 10px;
            box-shadow: 0 2px 5px rgba(0,0,0,0.1);
        }
    </style>
</head>
<body>

<header>
    <div class="logo-area">
        <h1>TBZ48</h1>
        <div class="leadership-box">
            Captain: Shato | Vice: Agra | Center: Fakhry
        </div>
    </div>
    <nav>
        <a href="#members">MEMBERS</a>
        <a href="#discography">DISCOGRAPHY</a>
        <a href="#setlist">SETLIST</a>
        <a href="#stats">STATISTICS</a>
    </nav>
</header>

<div class="container">

    <div id="stats" class="gen-stats">
        <div class="stat-badge"><b>Gen 1:</b> 15 (13 Active)</div>
        <div class="stat-badge"><b>Gen 2:</b> 13 (13 Active)</div>
        <div class="stat-badge"><b>Gen 3:</b> 13 (13 Active)</div>
        <div class="stat-badge"><b>Gen 4:</b> 8 (8 Active)</div>
        <div class="stat-badge"><b>Gen 5:</b> 19 (13 Active)</div>
    </div>

    <h2 id="members" class="section-title">OUR TEAMS</h2>
    
    <div class="team-card" style="border-left: 10px solid var(--team-t);">
        <div class="team-header">
            <img src="1766998678640.jpg" class="team-logo">
            <h2>TEAM T2</h2>
        </div>
        <div class="member-list">
            <div class="member-item">Fakhry (Gen 1)</div>
            <div class="member-item">Aidyn (Gen 1)</div>
            <div class="member-item">Alex (Gen 1)</div>
            <div class="member-item">Noerin (Gen 2)</div>
            <div class="member-item">Haturo (Gen 2)</div>
            <div class="member-item">Azriel (Gen 2)</div>
            <div class="member-item">Aoron (Gen 2)</div>
            <div class="member-item">Victor (Gen 3)</div>
            <div class="member-item">Valdes (Gen 3)</div>
            <div class="member-item">Akino (Gen 3)</div>
            <div class="member-item">Danniel (Gen 3)</div>
            <div class="member-item">Ichiro (Gen 3)</div>
            <div class="member-item">Kenzo (Gen 4)</div>
            <div class="member-item">Kei (Gen 4)</div>
            <div class="member-item">Aori (Gen 4)</div>
            <div class="member-item">Reyyih (Gen 1)</div>
        </div>
    </div>

    <div class="team-card" style="border-left: 10px solid var(--team-b);">
        <div class="team-header">
            <img src="1766998687785.jpg" class="team-logo">
            <h2>TEAM BVII</h2>
        </div>
        <div class="member-list">
            <div class="member-item">Ghifary (Gen 1)</div>
            <div class="member-item">Chen (Gen 1)</div>
            <div class="member-item">Shato (Gen 1)</div>
            <div class="member-item">Hataro (Gen 1)</div>
            <div class="member-item">Yeun (Gen 2)</div>
            <div class="member-item">Akhiro (Gen 2)</div>
            <div class="member-item">Rio (Gen 2)</div>
            <div class="member-item">Chiko (Gen 3)</div>
            <div class="member-item">Day (Gen 3)</div>
            <div class="member-item">Gibs (Gen 3)</div>
            <div class="member-item">Nathan (Gen 3)</div>
            <div class="member-item">Seojin (Gen 2)</div>
            <div class="member-item">Ryiee (Gen 4)</div>
            <div class="member-item">Jinu (Gen 4)</div>
            <div class="member-item">Mark (Gen 4)</div>
            <div class="member-item">Khenken (Gen 1)</div>
        </div>
    </div>

    <div class="team-card" style="border-left: 10px solid var(--team-z);">
        <div class="team-header">
            <img src="1766998668433.jpg" class="team-logo">
            <h2>TEAM Z</h2>
        </div>
        <div class="member-list">
            <div class="member-item">Fakhry (Gen 1)</div>
            <div class="member-item">Donny (Gen 1)</div>
            <div class="member-item">Shaid (Gen 1)</div>
            <div class="member-item">Jaewon (Gen 1)</div>
            <div class="member-item">Agra (Gen 2)</div>
            <div class="member-item">Junn (Gen 2)</div>
            <div class="member-item">Seijin (Gen 2)</div>
            <div class="member-item">Noelv (Gen 4)</div>
            <div class="member-item">Sino (Gen 2)</div>
            <div class="member-item">Hino (Gen 2)</div>
            <div class="member-item">Iroha (Gen 3)</div>
            <div class="member-item">Furio (Gen 3)</div>
            <div class="member-item">Jean (Gen 4)</div>
            <div class="member-item">Ryan (Gen 1)</div>
            <div class="member-item">Rifqie (Gen 1)</div>
            <div class="member-item">Ryanie (Gen 1)</div>
        </div>
    </div>

    <h2 id="discography" class="section-title">DISCOGRAPHY</h2>
    <div class="scroll-box">
        <table>
            <thead>
                <tr>
                    <th>Rilisan</th>
                    <th>Judul Lagu / Album</th>
                    <th>Center</th>
                    <th>Tanggal</th>
                </tr>
            </thead>
            <tbody>
                <tr><td>1st Single</td><td>Banzai Venus!</td><td><span class="center-tag">Fakhry</span></td><td>15 Des 2022</td></tr>
                <tr><td>2nd Single</td><td>Cosmos no Kioku</td><td><span class="center-tag">Fakhry</span></td><td>30 Des 2022</td></tr>
                <tr><td>Special EP</td><td>Sugar Rush</td><td><span class="center-tag">Fakhry/Ghifary</span></td><td>30 Jan 2023</td></tr>
                <tr><td>3rd Single</td><td>Idol Nanka ja Nakatta</td><td><span class="center-tag">Fakhry</span></td><td>9 Mar 2023</td></tr>
                <tr><td>8th Single</td><td>Luv me (Original)</td><td><span class="center-tag">Rayyih</span></td><td>30 Jun 2023</td></tr>
                <tr><td>1st Album</td><td>Best Of TBZ</td><td>-</td><td>14 Des 2023</td></tr>
                <tr><td>23rd Single</td><td>Seishun no Deadline</td><td><span class="center-tag">Shaid</span></td><td>1 Jan 2026</td></tr>
            </tbody>
        </table>
        <p><small>*Data ditampilkan sebagian. Lihat daftar lengkap di arsip.</small></p>
    </div>

    <h2 id="setlist" class="section-title">THEATER SETLIST</h2>
    <div class="member-list">
        <div class="team-card" style="flex: 1;">
            <h3>Ongoing Setlist</h3>
            <ul>
                <li>Pajama Drive (All)</li>
                <li>Renai Kinshi Journey (Team T)</li>
                <li>Saka Agari (Team B)</li>
                <li>Seifuku no Me (Team Z)</li>
                <li>Dareka no Tame ni (New)</li>
            </ul>
        </div>
    </div>

</div>

<footer>
    <p><b>TBZ48 Official Website</b></p>
    <p>Dreams under the Light Blue Sky &copy; 2026</p>
</footer>

</body>
</html>
