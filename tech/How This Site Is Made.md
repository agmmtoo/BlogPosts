# How I made this Blog

## Hello, good thing to see you here.

I made this site as a project of my React learning. Sorta novice level, but I learnt a lot of things. Big shout out to @NitelPhyoe [0] who gave me the idea.

## How things work

Straight to the point, I made this with React - well, JavaScript. The whole site is hosted on github pages. You can see the source code [here](https://github.com/agmyintmyatoo/portfolio)[1]. Check the `package.json` file for libs I used.

Basically, I created a [repo](https://github.com/agmyintmyatoo/BlogPosts)[2] with contents written in markdown format. Fetch these contents from GitHub API endpoints, and render markdown files with [react-markdown](https://github.com/remarkjs/react-markdown)[3] lib.

GitHub pages don't support client routing. And I don't want to see my urls with hashes; I doubt no one would. So I followed [this turorial](https://github.com/rafgraph/spa-github-pages)[4]. I used some tricks to convert readme file names to slug, for pretty url. _Aesthetic-wise_

**Honestly, I think it's a big waste and kind of reinventing the wheel to implement the function just to show contents from a Github repo (stuffs like Jekyll). But, like I said, this is my React learning project.**

_p.s. Since it is a learning stepstone, this project is likely to be thrown away lol. But feel free to reach out to me if you have smth you wanna know about where to learn react or how to get learning materials for FREE_

- [0] https://github.com/NitelPhyoe
- [1] https://github.com/agmyintmyatoo/portfolio
- [2] https://github.com/agmyintmyatoo/BlogPosts
- [3] https://github.com/remarkjs/react-markdown
- [4] https://github.com/rafgraph/spa-github-pages
