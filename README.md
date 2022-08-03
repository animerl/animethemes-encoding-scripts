<p align="center">
<a href="https://discordapp.com/invite/m9zbVyQ"><img src="https://img.shields.io/discord/354388306580078594.svg?label=&logo=discord&logoColor=ffffff&color=7389D8&labelColor=6A7EC2"></a>
<a href="https://github.com/AnimeThemes/animethemes-server/blob/wiki/LICENSE"><img src="https://img.shields.io/github/license/AnimeThemes/animethemes-server"></a>
<a href="https://reddit.com/r/AnimeThemes"><img src="https://img.shields.io/reddit/subreddit-subscribers/AnimeThemes?style=social"></a>
<a href="https://twitter.com/AnimeThemesMoe"><img src="https://img.shields.io/twitter/follow/AnimeThemesMoe?style=social"></a>
</p>

[**AnimeThemes**](https://animethemes.moe/) is a simple and consistent repository of anime opening and ending themes. We provide direct links to high quality WebMs of your favorite OPs and EDs for your listening and discussion needs.

This is the repository for scripts used to produce encoded WebMs for AnimeThemes.moe.

## Installation

For encoding script contributions, no dependencies are required. Simply clone the repository and add scripts.

For producing builds, [**animethemes-batch-encoder**](https://pypi.org/project/animethemes-batch-encoder/) is recommended.

## Contributing

Please review the [**Contributing Guide**](https://github.com/AnimeThemes/animethemes-encoding-scripts/blob/main/.github/CONTRIBUTING.md) for detailed instructions.

## Expectations

Scripts will be executed in an environment with `/animethemes-encoding-scripts/`, `/animethemes-sources/` & `/animethemes-target/` directories.

Builds are run from the root directory.

Scripts, sources & the target build shall be organized by year and season.

## Example

The Bakemonogatari sources shall exist in the `/animethemes-sources/2009/Summer/` directory.

The Bakemonogatari scripts shall exist in the `/animethemes-encoding-scripts/2009/Summer/` directory.

The Bakemonogatari build shall output to the `/animethemes-target/2009/Summer/` directory.

An FFmpeg command for Bakemonogatari shall be of the format:

`ffmpeg -i "/animethemes-sources/2009/Summer/release-path/source-file" {encoding settings} "/animethemes-target/2009/Summer/output-file.webm"`

## Resources

For support, please make use of the **#encoding_general** channel in the [**Discord Server**](https://discordapp.com/invite/m9zbVyQ).