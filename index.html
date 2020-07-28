# Gators Around the World 
## International Students at the University of Florida 

```{r, echo = FALSE}
library(plotly)
library(ggthemes)
library(ggplot2)
library(maps)
library(readxl)
library(htmlwidgets)

internat <- read_excel("~/Desktop/uf international .xlsx")


internat$Years <- as.character(internat$Year)
internat$year <- as.Date(internat$Years, '%Y') #Setting Date Variable 

inter2018<- subset(internat, Years == '2018') #Collects 2018 Data ONLY
inter2017<- subset(internat, Years == '2017') #Collect 2017 Data ONLY

int2018 <- inter2018 %>%
  filter(total!= 0) #Removes countries with 0 observations for 2018 students 

int2017 <- inter2017 %>%
  filter(total!= 0) #Removes countries with 0 observations for 2017 students

int2018$Country <- int2018$origin
int2018$Students <- int2018$total
int2018$Undergraduate <-int2018$undergrad
int2018$Graduate <- int2018$grad
int2018$NonDegree <- int2018$nondegree


int2017$Country <- int2017$origin
int2017$Students <- int2017$total
int2017$Undergraduate <-int2017$undergrad
int2017$Graduate <- int2017$grad

world <- map_data("world") 
interactive_map<-ggplot()+geom_polygon(data = world, aes(x=long, y = lat, group = group), fill = "grey", alpha = 0.3)+geom_point(data=int2018, aes(x=longitude, y=latitude, size=total,
                                           text = paste0("<b>Country:<b> ", Country, "<br>",
                                                              "<b>Number of Students:<b> ", Students, "<br>",
                                                              "<b>Undergraduates:<b> ", Undergraduate, "<br>",
                                                              "<b>Graduates: <b>", Graduate, "<br>",
                                                              "<b>Non-Degree: <b>", NonDegree, "<br>",
                                                              "<b>Optional Practical Training:<b> ", opt),group=1),color = '#FA4616')+

  theme_map()+
  theme(plot.title = element_text(color = '#0021A5', family = "Libre Franklin", face='bold',size=18, vjust=2))+
  theme(plot.subtitle = element_text(color = '#FA4616', family = "Libre Franklin", face="bold", size=14, vjust=2))+
  theme(plot.caption = element_text (color = "gray60", family = "Libre Franklin", face = 'bold', hjust=1))+
  theme(plot.background = element_rect(fill='gray96', colour =NA))+
  theme(legend.position = 'none')

ggplotly(interactive_map, tooltip = 'text') %>%
  config(displayModeBar = FALSE)

```

