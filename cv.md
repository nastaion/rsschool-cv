![Nasta Ion - digital avatar] (ion.jpg)
# Nasta Ion 
## Contacts
+ [GitHub](https://github.com/nastaion)
+ [Discord](https://discord.com/channels/1072442477627318282)
## About me
I'm trying not to die and find some interesting things in my life. I'm trying to finish JS Pre-School course for the 4th or 5th time - so I'm pretty persistent person. If you want to give me money please contact me via Discord.
## Skills
+ Markdown
+ Markup
+ HTML
+ CSS
+ Tilda
+ OTT
+ VOD
+ SQL
## Work experience
+ Freelance
+ Freelance
+ Freelance
## Code examples
1. JavaScript
```function century(year) {
  return Math.floor((year + 99) / 100);
  }
```
2. SQL
```select * from interviews
where suspect_id in (35, 44, 97)
```
3. R
```priceplot <- function(data, ticker, normalise=F){
    
  if (normalise) {
      data  <- data %>% spread(stock, close) 
      
      for (it in c(2:17)){
        data[it] <- (data[it])/(data[1,it])*100
        }
      
      data <- data %>% gather(key = stock, value =close, -date)
    }
    
     data %>%  
       filter(stock %in% ticker) %>%
       ggplot(aes(x = date, y = close, colour = stock)) +
       geom_line() +
       labs (title = ticker)
}
```
## Languages 
+ English (Advanced)
+ Russian (native)
+ Belarusian (native)

## Education
Bachelor Degree | Slavic Philology | BSU
