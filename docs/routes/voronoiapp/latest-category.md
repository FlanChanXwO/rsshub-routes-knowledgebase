# Voronoi - Latest Posts

## Coverage
`index-only`

## Route
- Namespace: `voronoiapp`
- Namespace Name: `Voronoi`
- Route Path: `/latest/:category?`
- Route Name: `Latest Posts`
- Example: `/voronoiapp/latest`
- URL: `voronoiapp.com`
- Language: `en`
- Categories: `picture`
- Maintainers: `Cesaryuan`
- Source Location: `latest.ts`
- Source Module: `() => import('@/routes/voronoiapp/latest.ts')`

## Description
_None_

## Parameters
- `category`: {"default": "", "description": "The category of the post", "options": [{"label": "All categories", "value": ""}, {"label": "Automotive Data Insights - Explore a range of automotive data visualizations showcasing trends, innovations, and market dynamics in the automotive industry.", "value": "Automotive"}, {"label": "Business Visualization Trends - Discover business visualizations covering market analysis, corporate strategies, and economic impacts across global industries.", "value": "Business"}, {"label": "Climate Data Visualized - Delve into climate change data visualizations that detail weather patterns, environmental impacts, and sustainability efforts worldwide.", "value": "Climate"}, {"label": "Demographic Visual Insights - Explore visual demographics data showcasing population trends, societal changes, and demographic analytics across regions.", "value": "Demographics"}, {"label": "Economic Visualization Insights - View economic visualizations illustrating financial markets, economic policies, and global economic health.", "value": "Economy"}, {"label": "Energy Industry Visual Data - Discover the dynamics of global energy consumption, renewable sources, and energy market trends through vivid visualizations.", "value": "Energy"}, {"label": "Entertainment Industry Data - Explore data visualizations in the entertainment industry, covering everything from box office trends to streaming service analytics.", "value": "Entertainment"}, {"label": "Geopolitical Data Visualized - Understand global geopolitical shifts and international relations through comprehensive geopolitical data visualizations.", "value": "Geopolitics"}, {"label": "Healthcare Insights Visualized - Analyze healthcare data visualizations spanning disease trends, healthcare services, and public health policies.", "value": "Healthcare"}, {"label": "Innovation in Data - Dive into innovation data visualizations highlighting technology advancements, R&D investments, and patent trends.", "value": "Innovation"}, {"label": "Cartographic Visual Insights - Discover cartographic visualizations that map everything from socio-economic data to geographical phenomena.", "value": "Maps"}, {"label": "Market Trends Visualized - Visualize market trends, financial data, and economic forecasts through comprehensive market visualizations.", "value": "Markets"}, {"label": "Financial Data Visualized - Dive into financial visualizations depicting currency trends, investment flows, and banking statistics.", "value": "Money"}, {"label": "Natural Resources Data - Explore visualizations of natural resources, detailing extraction, consumption, and conservation data.", "value": "Natural Resources"}, {"label": "Political Visual Insights - Analyze political trends, election results, and legislative impacts through detailed political visualizations.", "value": "Politics"}, {"label": "Public Opinion Trends - Discover visualizations of public opinion polls, social trends, and cultural shifts across different regions.", "value": "Public Opinion"}, {"label": "Real Estate Market Insights - Explore real estate market trends, property values, and urban development through targeted data visualizations.", "value": "Real Estate"}, {"label": "Sports Data Insights - Analyze sports data visualizations that showcase performance statistics, team rankings, and sports economics.", "value": "Sports"}, {"label": "Technology Trends Visualized - Dive into technology visualizations highlighting industry trends, tech adoption rates, and innovation impacts.", "value": "Technology"}, {"label": "Wealth Distribution Insights - Explore wealth distribution, financial health, and economic disparities through detailed visualizations.", "value": "Wealth"}, {"label": "Travel Trends Visualized - Discover travel trends, tourism statistics, and destination analytics through engaging visualizations.", "value": "Travel"}, {"label": "Nature and Conservation Data - Delve into visualizations of ecological data, wildlife statistics, and conservation efforts around the globe.", "value": "Nature"}, {"label": "Space Exploration Data - Explore the universe with space data visualizations covering planetary science, space missions, and astronomical discoveries.", "value": "Space"}, {"label": "Diagrammatic Data Insights - Understand complex data through diagrams that simplify information across various topics and industries.", "value": "Diagram"}, {"label": "Diverse Data Visualizations - Explore a variety of data visualizations that don't neatly fit into any single category but offer unique insights.", "value": "Other"}]}


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `www.voronoiapp.com/posts/latest`
- `target`: `/latest`

## Raw JSON
```json
{
  "categories": [
    "picture"
  ],
  "example": "/voronoiapp/latest",
  "location": "latest.ts",
  "maintainers": [
    "Cesaryuan"
  ],
  "module": "() => import('@/routes/voronoiapp/latest.ts')",
  "name": "Latest Posts",
  "parameters": {
    "category": {
      "default": "",
      "description": "The category of the post",
      "options": [
        {
          "label": "All categories",
          "value": ""
        },
        {
          "label": "Automotive Data Insights - Explore a range of automotive data visualizations showcasing trends, innovations, and market dynamics in the automotive industry.",
          "value": "Automotive"
        },
        {
          "label": "Business Visualization Trends - Discover business visualizations covering market analysis, corporate strategies, and economic impacts across global industries.",
          "value": "Business"
        },
        {
          "label": "Climate Data Visualized - Delve into climate change data visualizations that detail weather patterns, environmental impacts, and sustainability efforts worldwide.",
          "value": "Climate"
        },
        {
          "label": "Demographic Visual Insights - Explore visual demographics data showcasing population trends, societal changes, and demographic analytics across regions.",
          "value": "Demographics"
        },
        {
          "label": "Economic Visualization Insights - View economic visualizations illustrating financial markets, economic policies, and global economic health.",
          "value": "Economy"
        },
        {
          "label": "Energy Industry Visual Data - Discover the dynamics of global energy consumption, renewable sources, and energy market trends through vivid visualizations.",
          "value": "Energy"
        },
        {
          "label": "Entertainment Industry Data - Explore data visualizations in the entertainment industry, covering everything from box office trends to streaming service analytics.",
          "value": "Entertainment"
        },
        {
          "label": "Geopolitical Data Visualized - Understand global geopolitical shifts and international relations through comprehensive geopolitical data visualizations.",
          "value": "Geopolitics"
        },
        {
          "label": "Healthcare Insights Visualized - Analyze healthcare data visualizations spanning disease trends, healthcare services, and public health policies.",
          "value": "Healthcare"
        },
        {
          "label": "Innovation in Data - Dive into innovation data visualizations highlighting technology advancements, R&D investments, and patent trends.",
          "value": "Innovation"
        },
        {
          "label": "Cartographic Visual Insights - Discover cartographic visualizations that map everything from socio-economic data to geographical phenomena.",
          "value": "Maps"
        },
        {
          "label": "Market Trends Visualized - Visualize market trends, financial data, and economic forecasts through comprehensive market visualizations.",
          "value": "Markets"
        },
        {
          "label": "Financial Data Visualized - Dive into financial visualizations depicting currency trends, investment flows, and banking statistics.",
          "value": "Money"
        },
        {
          "label": "Natural Resources Data - Explore visualizations of natural resources, detailing extraction, consumption, and conservation data.",
          "value": "Natural Resources"
        },
        {
          "label": "Political Visual Insights - Analyze political trends, election results, and legislative impacts through detailed political visualizations.",
          "value": "Politics"
        },
        {
          "label": "Public Opinion Trends - Discover visualizations of public opinion polls, social trends, and cultural shifts across different regions.",
          "value": "Public Opinion"
        },
        {
          "label": "Real Estate Market Insights - Explore real estate market trends, property values, and urban development through targeted data visualizations.",
          "value": "Real Estate"
        },
        {
          "label": "Sports Data Insights - Analyze sports data visualizations that showcase performance statistics, team rankings, and sports economics.",
          "value": "Sports"
        },
        {
          "label": "Technology Trends Visualized - Dive into technology visualizations highlighting industry trends, tech adoption rates, and innovation impacts.",
          "value": "Technology"
        },
        {
          "label": "Wealth Distribution Insights - Explore wealth distribution, financial health, and economic disparities through detailed visualizations.",
          "value": "Wealth"
        },
        {
          "label": "Travel Trends Visualized - Discover travel trends, tourism statistics, and destination analytics through engaging visualizations.",
          "value": "Travel"
        },
        {
          "label": "Nature and Conservation Data - Delve into visualizations of ecological data, wildlife statistics, and conservation efforts around the globe.",
          "value": "Nature"
        },
        {
          "label": "Space Exploration Data - Explore the universe with space data visualizations covering planetary science, space missions, and astronomical discoveries.",
          "value": "Space"
        },
        {
          "label": "Diagrammatic Data Insights - Understand complex data through diagrams that simplify information across various topics and industries.",
          "value": "Diagram"
        },
        {
          "label": "Diverse Data Visualizations - Explore a variety of data visualizations that don't neatly fit into any single category but offer unique insights.",
          "value": "Other"
        }
      ]
    }
  },
  "path": "/latest/:category?",
  "radar": [
    {
      "source": [
        "www.voronoiapp.com/posts/latest"
      ],
      "target": "/latest"
    }
  ],
  "url": "voronoiapp.com",
  "view": 2
}
```
