```c
/* ************************************************************************** */
/*                                                                            */
/*                                                                            */
/*   profile.h                                                                */
/*                                                                            */
/*   By: Mikel Garrido <@LordMikkel>                                          */
/*                                                                            */
/*   Created: 2026/08/20 by migarrid                                          */
/*                                                                            */
/* ************************************************************************** */

#ifndef PROFILE_H
# define PROFILE_H

typedef enum e_focus
{
	SECURITY_RESEARCH,
	APPLIED_AI,
	DATA_ENGINEERING,
}	t_focus;

typedef struct s_profile
{
	char	*name;
	char	*school;
	char	*languages;
	char	*looking_for;
	char	*focus;
}	t_profile;

static const t_profile	me =
{
	.name = "Mikel Garrido",
	.school = "Computer Science @ 42 Barcelona",
	.languages = "C / C++ / Python",
	.looking_for = "Internship or junior role",
	.focus = "Cybersecurity research, applied AI and data"
};

/*
** SHORT VERSION
**
** I am a 42 Barcelona student interested in security, AI and data.
** My background is practical: C projects, open source, data workflows,
** custom AI models and technical workshops.
**
** I usually learn by building the thing myself, reading source code,
** testing edge cases and writing down what I understood.
*/

typedef struct s_project
{
	char	*name;
	char	*type;
	char	*notes;
	char	*link;
}	t_project;

static const t_project	projects[] =
{
	{
		.name = "Session",
		.type = "Open source contribution",
		.notes = "Fixed Unicode search for Cyrillic contact names in a privacy-focused messenger.",
		.link = "github.com/session-foundation/session-desktop/pull/1764"
	},
	{
		.name = "Cub3D",
		.type = "Raycasting engine in C",
		.notes = "Camera vectors, DDA, textures, lighting, sprites, enemy logic and threads.",
		.link = "github.com/LordMikkel/Cub3d"
	},
	{
		.name = "Minishell",
		.type = "Unix shell in C",
		.notes = "Tokenizer, parser, AST execution, pipes, redirections, signals and memory cleanup.",
		.link = "github.com/LordMikkel/Minishell"
	},
	{
		.name = "FdF",
		.type = "3D and 4D wireframe renderer",
		.notes = "Topographic maps, projections, rotations and 4D geometry experiments.",
		.link = "github.com/LordMikkel/Fdf"
	},
	{
		.name = "Code review tricks",
		.type = "C review checklist",
		.notes = "Symbols, leaks, hardening, weird inputs, tracing and performance checks.",
		.link = "github.com/LordMikkel/code-reviews-tricks"
	},
	{NULL, NULL, NULL, NULL}
};

/*
** ARCHIVEMENTS NOTES
**
** At 42, I earned the Hackerman achievement after finding and reporting
** a privilege escalation issue that gave me root access.
**
** I have worked as a cybersecurity instructor, generative AI developer,
** data technician, data analyst intern and web systems technician.
**
** Before 42, I studied at the University of Barcelona. I also taught
** there and later coordinate a project with more than 70 people.
*/

static const char	*languages[] =
{
	"Spanish: native",
	"English: professional",
	"German: elementary",
	NULL
};

#endif
```

**Links**

[Session PR](https://github.com/session-foundation/session-desktop/pull/1764) · [Cub3D](https://github.com/LordMikkel/Cub3d) · [FdF](https://github.com/LordMikkel/Fdf) · [Minishell](https://github.com/LordMikkel/Minishell) · [Code review tricks](https://github.com/LordMikkel/code-reviews-tricks)

**Contact**

GitHub: [@LordMikkel](https://github.com/LordMikkel) · LinkedIn: [Mikel Garrido](https://linkedin.com/in/mikelgarrido)
