### Hello World 🖥️ 🖐️

### About me 🐬

- 🖐️ I'm Nguyen Van Tuan
- 🖥️ I’m currently Big Data Engineer.
- 🌱 I’m currently working Bigdata, GCP, SQL,Docker,K8s ... 
- 📫 How to reach me: [Face book - @tuancam](https://www.facebook.com/tuanbacam)
- 😄 Pronouns: He/His

### Skills

 [![Haoop](https://img.shields.io/badge/bigdata-hadoop-yellow)](#)
(https://img.shields.io/badge/-Javascript-F0DB4F?style=for-the-badge&labelColor=black&logo=javascript&logoColor=F0DB4F)](#) [![Nodejs Badge]

 ![visitors](https://visitor-badge.glitch.me/badge?page_id=tuancamtbtx&left_color=green&right_color=red)

## Today's Weather Forecast in My Hometown

{{ with $todayWeather := index .Weathers 0 }}

`{{ $todayWeather.City }}, {{$todayWeather.Country }} - {{ formatDate $todayWeather.StartTime $todayWeather.Timezone }}`

<img src="{{ $todayWeather.Icon}}"/>

{{ $todayWeather.Condition }}

{{template "hourly-table" $todayWeather.HourlyWeathers}}

{{- end }}


