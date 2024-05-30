git clone https://commuterlot.com/nate101805/my-website.git
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Hartford Transportation Solutions</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Hartford Transportation Solutions</h1>
    </header>
    <main>
        <section id="issue">
            <h2>The Issue</h2>
            <p>The high number of buses in Hartford, West Hartford, and Windsor, CT, contributes significantly to environmental degradation due to emissions of greenhouse gases and pollutants from diesel engines. These emissions lead to poor air quality, contributing to respiratory issues and climate change. Additionally, frequent bus routes often overlap, causing unnecessary fuel consumption and increased wear and tear on infrastructure, further exacerbating their negative environmental impact.</p>
        </section>
        <section id="solutions">
            <h2>Transportation Solutions</h2>
            <article>
                <h3>Light Rail</h3>
                <p><strong>Pros:</strong></p>
                <ul>
                    <li>Reliable and efficient mode of transportation within Hartford's urban core</li>
                    <li>Reduces traffic congestion and air pollution</li>
                    <li>Stimulates economic development and revitalization of underutilized areas</li>
                </ul>
                <p><strong>Cons:</strong></p>
                <ul>
                    <li>High upfront capital costs</li>
                    <li>Potential disruption to existing traffic patterns</li>
                    <li>Significant changes to existing infrastructure required</li>
                </ul>
            </article>
            <article>
                <h3>Transportation Oriented Development</h3>
                <p><strong>Pros:</strong></p>
                <ul>
                    <li>Creates more walkable and livable communities</li>
                    <li>Reduces traffic congestion by reducing the need for lengthy commutes</li>
                    <li>Promotes mixed-use development, increasing property value and economic activity</li>
                </ul>
                <p><strong>Cons:</strong></p>
                <ul>
                    <li>Challenging to implement in areas with existing development patterns</li>
                    <li>Significant changes to zoning regulations and land use policies required</li>
                    <li>May not be feasible in areas with limited land availability or high environmental concerns</li>
                </ul>
            </article>
            <article>
                <h3>Regional Rail</h3>
                <p><strong>Pros:</strong></p>
                <ul>
                    <li>Convenient and efficient mode of transportation between Hartford and surrounding cities</li>
                    <li>Reduces traffic congestion and air pollution by reducing the number of cars on the road</li>
                    <li>Stimulates economic development in surrounding areas</li>
                </ul>
                <p><strong>Cons:</strong></p>
                <ul>
                    <li>High upfront capital costs</li>
                    <li>Significant changes to existing infrastructure required</li>
                    <li>Challenging to coordinate with other transportation modes</li>
                </ul>
            </article>
            <article>
                <h3>Traffic Calming</h3>
                <p><strong>Pros:</strong></p>
                <ul>
                    <li>Reduces traffic speeds and improves safety for pedestrians and cyclists</li>
                    <li>Reduces noise pollution and improves overall quality of life</li>
                    <li>Implemented at a relatively low cost compared to other options</li>
                </ul>
                <p><strong>Cons:</strong></p>
                <ul>
                    <li>May not be effective in high-traffic corridors</li>
                    <li>Can be perceived as inconvenient by motorists</li>
                    <li>Requires ongoing maintenance and monitoring</li>
                </ul>
            </article>
            <article>
                <h3>Enhanced Bike Infrastructure</h3>
                <p><strong>Pros:</strong></p>
                <ul>
                    <li>Encourages more people to use bicycles, reducing traffic congestion and air pollution</li>
                    <li>Promotes healthier lifestyles and community engagement</li>
                    <li>Implemented at a relatively low cost compared to other options</li>
                </ul>
                <p><strong>Cons:</strong></p>
                <ul>
                    <li>May not be feasible in heavily developed areas</li>
                    <li>Challenging to design and implement safe and accessible bike infrastructure</li>
                    <li>Requires ongoing maintenance and monitoring</li>
                </ul>
            </article>
            <article>
                <h3>Pedestrian Infrastructure</h3>
                <p><strong>Pros:</strong></p>
                <ul>
                    <li>Improves safety and accessibility for pedestrians</li>
                    <li>Enhances the overall aesthetic appeal of public spaces</li>
                    <li>Promotes healthier lifestyles and community engagement</li>
                </ul>
                <p><strong>Cons:</strong></p>
                <ul>
                    <li>May not be effective in high-traffic corridors</li>
                    <li>Challenging to design and implement safe and accessible pedestrian infrastructure</li>
                    <li>Requires ongoing maintenance and monitoring</li>
                </ul>
            </article>
        </section>
        <section id="commuter-lots">
            <h2>Why Commuter Lots are the Best Solution</h2>
            <div class="textbox">
                <p>Commuter lots are an effective solution to reduce environmental impact. By consolidating bus routes into fewer, more efficient services, commuter lots can decrease the number of buses on the road, reducing greenhouse gas emissions and pollutants. This also minimizes fuel consumption and lowers infrastructure wear and tear. Additionally, using large EV vans for shuttle services can further cut down on emissions, promoting a greener, healthier environment.</p>
            </div>
        </section>
    </main>
    <footer>
        <p>© 2024 Hartford Transportation Solutions</p>
    </footer>
</body>
</html>
body {
    font-family: Arial, sans-serif;
    line-height: 1.6;
    margin: 0;
    padding: 0;
    background-color: #f4f4f4;
}

header {
    background-color: #333;
    color: #fff;
    padding: 1rem 0;
    text-align: center;
}

header h1 {
    margin: 0;
}

main {
    padding: 1rem;
}

section {
    margin-bottom: 2rem;
}

section#issue, section#commuter-lots {
    background: #fff;
    padding: 1rem;
    border-radius: 5px;
    box-shadow: 0 0 10px rgba(0,0,0,0.1);
}

section#solutions article {
    background: #fff;
    padding: 1rem;
    margin-bottom: 1rem;
    border-radius: 5px;
    box-shadow: 0 0 10px rgba(0,0,0,0.1);
}

section#solutions h3, section#commuter-lots h2 {
    color: #333;
}

.textbox {
    background-color: #e6f7ff;
    padding: 1rem;
    border-left: 5px solid #0099cc;
    border-radius: 5px;
    box-shadow: 0 0 10px rgba(0,0,0,0.1);
}

footer {
    background-color: #333;
    color: #fff;
    text-align: center;
    padding: 1rem 0;
    position: fixed;
    width: 100%;
    bottom: 0;
}

