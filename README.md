# 🎉 Github Actions

GitHub Actions: Automate your workflow! Build, test, and deploy code directly from your GitHub repository. Effortless CI/CD for developers.

![version](https://img.shields.io/badge/version-1.0-blue)
![rating](https://img.shields.io/badge/rating-★★★★★-yellow)
![uptime](https://img.shields.io/badge/uptime-100%25-brightgreen)

### 🚀 Setup

![permission](./img/permission.png)

> [WEATHER_API_KEY](https://www.weatherapi.com/) in Your repo > settings > Secrets and variables > Actions > New repository secret

### ✅ Blog Post `blog-post.yaml` with schedule every day: [source](https://github.com/gautamkrishnar/blog-post-workflow)

<!-- BLOG:START -->
- [ประกาศย้ายไปเว็บ codeinsane.dev](https://codeinsane.wordpress.com/2024/03/19/%e0%b8%9b%e0%b8%a3%e0%b8%b0%e0%b8%81%e0%b8%b2%e0%b8%a8%e0%b8%a2%e0%b9%89%e0%b8%b2%e0%b8%a2%e0%b9%84%e0%b8%9b%e0%b9%80%e0%b8%a7%e0%b9%87%e0%b8%9a-codeinsane-dev/)
- [How to Trust Sign Image on Docker](https://codeinsane.wordpress.com/2023/10/31/how-to-trust-sign-image-on-docker/)
- [Poetry Virtual Environment Command](https://codeinsane.wordpress.com/2023/10/30/poetry-virtual-environment-command/)
- [How to Rename all Files in Folder use UUID with Power Automate Desktop](https://codeinsane.wordpress.com/2023/10/09/how-to-rename-all-files-in-folder-use-uuid-with-power-automate/)
- [How to use Web Application Firewall &lpar;WAF&rpar; with Waf2Py](https://codeinsane.wordpress.com/2023/10/05/how-to-use-web-application-firewall-waf-with-waf2py/)
<!-- BLOG:END -->

### ✅ Setup Poetry `setup-poetry.yaml` with on push: [source](https://github.com/abatilo/actions-poetry)

- Use command generate poetry virtualenv in project

```
poetry config virtualenvs.create true --local
poetry config virtualenvs.in-project true --local
```

- Show in file `poetry.toml`

```
[virtualenvs]
create = true
in-project = true
```

### ✅ Create Tag `create-tag.yaml` with on push: [source](https://github.com/mathieudutour/github-tag-action)

| Commit Message                                                        | Release Type  |
|-----------------------------------------------------------------------|---------------|
| fix(pencil): stop graphite breaking when too much pressure applied    | Patch Release |
| feat(pencil): add 'graphiteWidth' option                              | Minor Release |
| perf(pencil): remove graphiteWidth option                             | Major Release |

### ✅ Update Weather `update-weather.yml` with on push: [source](https://github.com/huantt/weather-forecast)


<table>
    <tr>
        <th>Date</th>
        <td>26/10/2023</td><td>27/10/2023</td><td>28/10/2023</td>
    </tr>
    <tr>
        <th>Weather</th>
        <td><img src="https://cdn.weatherapi.com/weather/64x64/day/302.png"/></td><td><img src="https://cdn.weatherapi.com/weather/64x64/day/176.png"/></td><td><img src="https://cdn.weatherapi.com/weather/64x64/day/176.png"/></td>
    </tr>
    <tr>
        <th>Condition</th>
        <td width="200px">Moderate rain</td><td width="200px">Patchy rain possible</td><td width="200px">Patchy rain possible</td>
    </tr>
    <tr>
        <th>Temperature</th>
        <td>25.4 -  31.7 °C</td><td>26.4 -  32.3 °C</td><td>26.7 -  31.9 °C</td>
    </tr>
    <tr>
        <th>Wind</th>
        <td>12.2 kph</td><td>14 kph</td><td>11.9 kph</td>
    </tr>
</table>
