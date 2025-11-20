<script lang="ts">
	// Components
	import Summary from "$lib/components/layout/Summary.svelte";
	import Features from "$lib/components/layout/Features.svelte";
	import Testimonials from "$lib/components/layout/Testimonials.svelte";
	import CallToAction from "$lib/components/layout/CallToAction.svelte";
	import AboutTeaser from "$lib/components/layout/AboutTeaser.svelte";
	import LogoScroller from "$lib/components/layout/LogoScroller.svelte";
	import CenteredTextOnlyHero from "$lib/components/layout/hero-sections/CenteredTextOnlyHero.svelte";

	// Icons
	import IconLayers from "~icons/lucide/layers";
	import IconContainer from "~icons/lucide/container";
	import IconShield from "~icons/lucide/shield";
	import IconZap from "~icons/lucide/zap";
	import IconCode from "~icons/lucide/code";
	import IconUnlock from "~icons/lucide/unlock";
</script>

<CenteredTextOnlyHero
	title="Transform prompts into production apps"
	subtitle="Multi-model AI code generation with true developer freedom. Built by developers who refused to compromise."
	imageSrc="/generated/image-a-candid-documentary-style-photograph-of.webp"
/>
<LogoScroller
	label="Trusted by developers at"
	logoUrls={[
		'https://cdn.brandfetch.io/vercel.com/w/400/h/400/logo',
		'https://cdn.brandfetch.io/railway.app/w/400/h/400/logo',
		'https://cdn.brandfetch.io/supabase.com/w/400/h/400/logo',
		'https://cdn.brandfetch.io/clerk.com/w/400/h/400/logo'
	]}
/>

<Summary
	title="Built for developers who move fast"
	text="CodinIT turns your ideas into working full-stack applications using multi-model AI code generation and instant WebContainer execution. Start with any AI model you choose, prototype in minutes instead of hours, and maintain complete control over your development environment. We're the open-source alternative built by developers who got tired of expensive platforms that lock you in."
/>

<Testimonials
	testimonials={[
		{
			name: "Marcus Chen",
			position: "Indie Developer",
			company: "BuildFast Studio",
			quote:
				"CodinIT cut my prototype development time from 3 weeks to 2 days. I shipped 5 MVPs in a month using different models for each project. The WebContainer execution means I can demo live without deployment costs.",
			image: "/generated/image-candid-editorial-headshot-of-marcus-chen.webp"
		},
		{
			name: "Priya Sharma",
			position: "Founder",
			company: "MicroSaaS Labs",
			quote:
				"Switching between Claude, GPT-4, and local models saved me $800/month compared to locked-in platforms. The multi-model approach eliminated the risk of vendor lock-in while I scaled from idea to paying customers.",
			image: "/generated/image-editorial-documentary-headshot-of-priya-.webp"
		},
		{
			name: "Dmitri Volkov",
			position: "Full-Stack Maker",
			company: "Solo Ventures",
			quote:
				"I built and tested 12 different app concepts in one weekend. CodinIT's local control meant zero API costs during experimentation. When one concept gained traction, I had production-ready code immediately.",
			image: "/generated/image-candid-editorial-headshot-of-dmitri-volk.webp"
		}
	]}
/>

<Features
	title="Built for developers who refuse to compromise"
	subtitle="True multi-model freedom meets instant execution"
	features={[
		{
			title: "Multi-model AI freedom",
			description:
				"Switch between GPT-4, Claude, Gemini, and more without vendor lock-in. No single AI model monopoly—choose the best tool for each task.",
			icon: IconLayers
		},
		{
			title: "WebContainer execution",
			description:
				"Test and run your generated code instantly in a real browser environment. Skip the deploy-and-pray cycle with immediate feedback.",
			icon: IconContainer
		},
		{
			title: "Local-first control",
			description:
				"Your code, your machine, your rules. Run everything locally without sending your IP to closed platforms or sharing your work with third-party servers.",
			icon: IconShield
		},
		{
			title: "Rapid full-stack prototyping",
			description:
				"Go from prompt to working app in minutes, not days. Complete frontend and backend scaffolding with routing, state management, and API integration built in.",
			icon: IconZap
		},
		{
			title: "Open-source flexibility",
			description:
				"Community-driven development means features you actually need get built. Fork it, extend it, customize it—no feature request gatekeeping.",
			icon: IconCode
		},
		{
			title: "Escape expensive platforms",
			description:
				"Break free from $20-50/month AI coding subscriptions. Pay only for the AI models you use, when you use them.",
			icon: IconUnlock
		}
	]}
/>
<AboutTeaser />
<CallToAction
	title="Your tools. Your code. Your pace."
	subtitle="Break free from expensive platforms"
	description="CodinIT doesn't box you in. Whether you're exploring an idea or launching the real thing, you get production-grade outputs, version control, and model choice built in. Start building with true multi-model freedom."
	imageSrc="/generated/image-a-candid-documentary-style-photograph-of.webp"
	callsToAction={[
		{
			href: "#",
			label: "Start building for free",
			variant: "primary"
		},
		{
			href: "#",
			label: "View documentation",
			variant: "secondary"
		}
	]}
/>
