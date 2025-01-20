## Data for the figure skating competition at the Winter Olympics 2022.

The figure skating competition at the Winter Olympics 2022 consisted of two sessions; a short program and a long program. In each program the athletes were judged by nine judges and given a score based on two distinct scoring systems; the technical element score (TES) and the performance component score (PCS).

Only the long program is depicted in the data.

R syntax to extract data:
<pre class="r"><code>df.com &lt;- read.csv(
&quot;https://raw.githubusercontent.com/janbvalentin/figureskating/refs/heads/main/women_2022_long_com.csv&quot;
)
df.goe &lt;- read.csv(
&quot;https://raw.githubusercontent.com/janbvalentin/figureskating/refs/heads/main/women_2022_long_goe.csv&quot;
)</code></pre>
<p>The data is also available at skatingscores.com.</p>
