import type { Config } from '../types/config';

const config: Config = {
  // Personal Info - DzINR bold hero
  name: 'Partha Maity',
  title: 'Sports Marketing & Brand Management',
  tagline: 'Driving Fan Engagement | Dubai Relocation',
  description: '6+ years delivering campaigns, partnerships, and events at Leeds United, YCCC. Masters Sports Business. Seeking senior roles in Dubai sports industry.',

  // Theme - Black/minimal like dzinr.in
  accentColor: '#000000',  // Black primary

  // Social - Your links
  social: {
    email: 'your.email@example.com',
    linkedin: 'https://linkedin.com/in/parthamaity',
    github: 'https://github.com/parthamaity',
  },

  // About - Your story
  aboutMe: `Detail-oriented sports marketing professional with proven track record in brand partnerships, event delivery, and fan engagement. Experienced with global brands, social campaigns, GA4 analytics, CRM tools. Relocating to Dubai for next career challenge.`,

  // Skills - Your expertise
  skills: [
    'Campaign Strategy',
    'Brand Partnerships', 
    'Stakeholder Management',
    'Event Delivery',
    'Google Analytics 4',
    'CRM (Dot Digital, Seatgeek)',
    'Social Media Activation'
  ],

  // Projects - DzINR cards w/ your work
  projects: [
    {
      name: 'Leeds United Brand Partnerships',
      description: 'Social-led activations driving 25% fan engagement uplift, 150K impressions. ROI 3.2x.',
      link: 'https://your-link-or-pdf',
      skills: ['Social Campaigns', 'Partnerships', 'Analytics']
    },
    {
      name: 'YCCC Tournament Operations',
      description: 'Operations for 50K+ attendees. Sponsor liaison, customer engagement.',
      link: 'https://your-link',
      skills: ['Event Management', 'Stakeholder']
    },
    {
      name: 'Leeds Festival Project Management',
      description: 'Full event coordination, delivery excellence.',
      link: 'https://your-link',
      skills: ['Project Management', 'Events']
    }
  ],

  // Experience timeline
  experience: [
    {
      company: 'Leeds United Football Club',
      title: 'Account Manager',
      dateRange: 'Current',
      bullets: [
        'Social-led brand partnerships & campaign delivery',
        'Stakeholder management between teams & sponsors',
        'Customer engagement driving measurable impact'
      ]
    },
    {
      company: 'Yorkshire County Cricket Club (YCCC)',
      title: 'Operations Assistant',
      dateRange: 'Previous',
      bullets: [
        'Tournament delivery & operations',
        'Event coordination 50K+ attendees',
        'Sponsor liaison & activation'
      ]
    }
  ],

  // Education
  education: [
    {
      school: 'Leeds Beckett University',
      degree: 'Masters in Sports Business',
      dateRange: 'Recent',
      achievements: ['Post Study Work Visa UK']
    }
  ]
};

export default config;
