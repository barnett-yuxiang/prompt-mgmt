{
  "meta_prompt_template": {
    "template_name": "品牌产品演变史3D信息图生成器",
    "template_version": "2.0",
    "template_description": "用于生成博物馆级品牌产品演变史信息图的通用提示词模板，支持手机、汽车、消费电子等多种产品类别",
    "output_format": "4K/8K超高清16:9横版海报",

    "required_variables": {
      "brand_name_cn": "品牌中文名称（如：小米、保时捷）",
      "brand_name_en": "品牌英文名称（如：XIAOMI、PORSCHE）",
      "start_year": "起始年份（如：2011、1948）",
      "end_year": "结束年份（如：2025）",
      "years_span": "总年限（自动计算：end_year - start_year）",
      "product_category": "产品类别（如：手机、汽车、相机、游戏机等）",
      "total_products": "里程碑产品数量（建议12-13款）",
      "brand_color_primary": "品牌主色调（如：小米橙铜色、保时捷赛车绿）",
      "brand_slogan": "品牌标志性口号（如：为发烧而生、Inspired by Racing）"
    },

    "product_lineup": {
      "description": "按时间顺序排列的产品清单，每个产品包含年份、型号、关键特征",
      "format": "YEAR Product_Name (key_feature) → YEAR Product_Name (key_feature) → ...",
      "example_xiaomi": "2011 Mi 1 (1999元 price tag) → 2012 Mi 2 → 2013 Redmi Note → 2014 Mi 4 (steel frame) → 2016 Mi MIX (bezel-less pioneer) → 2017 Mi 6 → 2019 Mi 9 → 2020 Mi 10 → 2021 Mi 11 Ultra (Leica camera) → 2022 Mi 12S Ultra → 2023 Mi 13 Ultra → 2024 Mi 14 Ultra → 2025 Mi 15 Ultra (AI flagship)",
      "example_porsche": "1948 Porsche 356 (first car) → 1963 Porsche 911 (iconic silhouette) → 1970 Porsche 917 (Le Mans) → 1975 911 Turbo 930 (whale tail) → 1996 Boxster → 1998 911 996 (water-cooled) → 2003 Cayenne (SUV) → 2009 Panamera → 2014 918 Spyder → 2019 Taycan (electric) → 2023 911 Dakar → 2024 911 Hybrid → 2025 Mission X",
      "customization_guide": "根据品牌实际产品线替换，保留关键特征标签"
    },

    "era_divisions": {
      "description": "将品牌历史划分为3-5个时代，每个时代包含时间段、标志图标、核心特征",
      "recommended_count": "4-5个时代",
      "format_structure": {
        "era_name_cn": "时代中文名称",
        "era_name_en": "时代英文名称",
        "time_range": "起止年份",
        "icon": "代表图标（emoji或描述）",
        "key_features": ["特征1", "特征2", "特征3"]
      },
      "example_xiaomi": [
        {
          "era": "发烧友时代 2011-2013 (Enthusiast Era)",
          "icon": "flame icon",
          "features": ["为发烧而生", "互联网营销", "MIUI系统", "粉丝文化"]
        },
        {
          "era": "性价比之王 2014-2017 (Value King Era)",
          "icon": "crown icon",
          "features": ["红米系列", "印度第一", "生态链爆发"]
        },
        {
          "era": "全面屏革命 2018-2020 (Full-Screen Revolution)",
          "icon": "screen icon",
          "features": ["MIX引领", "屏下指纹", "冲击高端"]
        },
        {
          "era": "高端化征程 2021-2024 (Premium Journey)",
          "icon": "mountain peak icon",
          "features": ["徕卡合作", "影像旗舰", "卫星通信"]
        },
        {
          "era": "AI智能新纪元 2025 (AI Intelligence Era)",
          "icon": "brain icon",
          "features": ["端侧大模型", "生态闭环", "全球化"]
        }
      ],
      "example_porsche": [
        {
          "era": "手工制作时代 1948-1975 (Handcrafted Era)",
          "icon": "wrench icon",
          "features": ["356奠基", "911诞生", "勒芒传奇"]
        },
        {
          "era": "涡轮增压革命 1976-1995 (Turbo Revolution)",
          "icon": "turbo icon",
          "features": ["930 Turbo", "鲸鱼尾", "风冷巅峰"]
        },
        {
          "era": "水冷多元化 1996-2013 (Water-Cooled Diversification)",
          "icon": "expansion icon",
          "features": ["水冷转型", "Cayenne/Panamera", "全系车企"]
        },
        {
          "era": "电气化新纪元 2014-2025 (Electric New Era)",
          "icon": "lightning bolt icon",
          "features": ["918 Spyder", "Taycan纯电", "Mission X未来"]
        }
      ]
    },

    "complete_prompt_structure": {
      "header": {
        "template": "A massive, encyclopedic 16:9 3D infographic poster titled \"THE EVOLUTION OF {BRAND_EN} | {BRAND_CN}进化史 {START_YEAR}-{END_YEAR}\". The visual style is a high-end fusion of museum-grade {PRODUCT_CATEGORY} photography and complex technical engineering blueprints.",
        "customization": "替换大括号内的变量"
      },

      "hero_lineup": {
        "template": "The Hero Lineup: A complete chronological lineup of {TOTAL_PRODUCTS} iconic {BRAND_EN} {PRODUCT_CATEGORY} arranged horizontally across the center on a {SURFACE_MATERIAL} with {MEASUREMENT_TOOL}:\n{PRODUCT_TIMELINE_STRING}",
        "surface_material_options": [
          "precision metal measurement scale (科技产品)",
          "polished black marble platform with chrome scale (奢侈品/汽车)",
          "wooden display shelf with brass rulers (复古产品)",
          "acrylic transparent platform (未来科技)"
        ],
        "example": "precision metal measurement scale | polished black marble platform"
      },

      "rendering_style": {
        "template": "Rendering: Hyper-realistic 3D, 8k resolution. Emphasis on the evolution of {EVOLUTION_ASPECT}: showing {EARLY_STAGE_DESCRIPTION} vs. {LATE_STAGE_DESCRIPTION}.",
        "evolution_aspects": {
          "materials": "material evolution (材质演变)",
          "design": "design language evolution (设计语言)",
          "technology": "technological advancement (技术进步)",
          "size": "form factor evolution (形态演变)"
        },
        "example_xiaomi": "materials: showing the plastic back cover of early 2011 models vs. the premium ceramic, glass, and titanium finishes with sophisticated camera modules and AI capabilities of 2025 flagship phones",
        "example_porsche": "design language: showing the curved simplicity of 1948 356 vs. the aerodynamic sophistication and futuristic electric innovation of 2025 Mission X concept"
      },

      "background_design": {
        "template": "Background: A deep, rich {COLOR_GRADIENT} gradient textured background ({BRAND_COLOR_CONTEXT}). It is heavily layered with low-opacity watermarks of {BRAND_ELEMENTS_LIST}, with \"{START_YEAR}-{END_YEAR}\" and \"{YEARS_SPAN} YEARS\" timeline markers.",
        "color_examples": {
          "xiaomi": "orange-to-copper (Xiaomi's signature MIUI color)",
          "porsche": "racing-green-to-charcoal (Porsche's heritage racing colors)",
          "apple": "silver-to-space-gray (Apple's premium aesthetic)",
          "ferrari": "racing-red-to-black (Ferrari's passion colors)"
        },
        "brand_elements_examples": {
          "tech_company": "brand logo evolution, product launch keynote slides, system interface screenshots, store opening photos, IPO newspapers, market share charts",
          "automotive": "brand crest evolution, vintage racing posters, technical engine drawings, lap time charts, victory newspapers, iconic colorway samples"
        }
      },

      "header_design": {
        "template": "Header: The iconic {BRAND_EN} logo displayed at the top center in {LOGO_MATERIAL} 3D relief, with bold {FONT_STYLE} title \"THE EVOLUTION OF {BRAND_EN} | {BRAND_CN}进化史 {START_YEAR}-{END_YEAR}\" with prominent \"{YEARS_SPAN} YEARS\" badge.",
        "logo_material_options": [
          "brushed metal (科技品牌)",
          "metallic with gold accents (奢侈品)",
          "chrome (汽车品牌)",
          "glossy enamel (消费品)"
        ],
        "font_style_options": [
          "sans-serif (现代科技)",
          "serif (经典奢华)",
          "German-style typography (汽车)",
          "handwritten script (创意品牌)"
        ]
      },

      "information_layer": {
        "dense_annotation_network": {
          "description": "密集标注网络，连接产品细节与数据说明",
          "template": "Hundreds of fine {LINE_COLOR} hairlines connecting design elements ({DESIGN_ELEMENTS_LIST}) to compact text blocks showing {DATA_METRICS_LIST}",
          "line_color_by_brand": {
            "tech_modern": "white/silver",
            "luxury_auto": "gold/silver",
            "vintage": "sepia/cream",
            "futuristic": "neon blue/cyan"
          },
          "design_elements_examples": {
            "smartphone": "camera modules, bezel evolution, fingerprint sensors, pop-up cameras, under-display cameras, AI chips",
            "automotive": "headlight shapes, rear spoiler evolution, exhaust configurations, wheel designs, engine placement, electric motor integration",
            "camera": "lens mount evolution, sensor size, shutter mechanism, viewfinder design, grip ergonomics",
            "gaming_console": "controller evolution, port configurations, cooling system, storage media, processing power"
          },
          "data_metrics_examples": {
            "smartphone": "processor generation, RAM/ROM, camera megapixels, battery capacity, charging speed, launch price, second-hand value, AI features",
            "automotive": "engine displacement, horsepower, 0-100km/h time, lap records, production numbers, racing wins, electric range",
            "camera": "sensor size, ISO range, shutter speed, lens compatibility, price evolution, professional adoption rate"
          }
        },

        "contextual_zones": {
          "description": "时代划分模块，浮动在产品阵容上方",
          "template": "Era modules floating above: \"{ERA_1_CN} {TIME_1} ({ERA_1_EN})\" with {ICON_1}, \"{ERA_2_CN} {TIME_2} ({ERA_2_EN})\" with {ICON_2}, ...",
          "customization": "根据era_divisions部分填充"
        },

        "magnifying_inserts": {
          "description": "放大镜特写，展示关键技术细节",
          "template": "Circular zoom-in lenses showing: {DETAIL_1}, {DETAIL_2}, {DETAIL_3}, ...",
          "examples": {
            "smartphone": "Stainless steel frame micro-texture, Ceramic back material close-up, Camera sensor size comparison, Under-display fingerprint sensor structure, Leica lens coating, AI chip neural engine",
            "automotive": "Air-cooled engine internals, Turbo spoiler aerodynamics, Mid-engine layout cutaway, Hybrid drivetrain schematic, Battery pack thermal management, Carbon fiber monocoque detail"
          }
        },

        "tech_specs_strip": {
          "description": "底部技术规格数据条",
          "template": "A horizontal data bar at the bottom displaying: {COLUMN_1} | {COLUMN_2} | {COLUMN_3} | ...",
          "examples": {
            "smartphone": "YEAR | MODEL | PROCESSOR | RAM/ROM | CAMERA | BATTERY | CHARGING | LAUNCH PRICE | 二手价值 | AI FEATURES",
            "automotive": "YEAR | MODEL | ENGINE TYPE | POWER | 0-100KM/H | NÜRBURGRING TIME | PRODUCTION UNITS | RACING WINS | ELECTRIC RANGE",
            "camera": "YEAR | MODEL | SENSOR SIZE | ISO RANGE | SHUTTER SPEED | LENS MOUNT | WEIGHT | LAUNCH PRICE | PRO ADOPTION"
          }
        }
      },

      "floating_elements": {
        "description": "额外的漂浮信息元素",
        "template": "Patent-style technical drawings of {TECH_FEATURE_1}, {TIMELINE_ELEMENT}, {DIAGRAM_ELEMENT}, {CHART_ELEMENT}, {VISUAL_ELEMENT}",
        "examples": {
          "tech_features": "pop-up camera mechanism, under-display camera, wireless charging coil, foldable hinge, PDK transmission, turbo system",
          "timeline_elements": "global market expansion map, racing victory timeline, OS version evolution tree, international awards timeline",
          "diagram_elements": "brand logo evolution 1952-2025, ecosystem products integration, supply chain network",
          "chart_elements": "market share growth chart, power-to-weight ratio comparison, sales volume by region, price positioning matrix",
          "visual_elements": "iconic colorways palette, material samples, packaging evolution, celebrity endorsements"
        }
      },

      "technical_specs": {
        "rendering_engine": "Octane render, Unreal Engine 5 aesthetic",
        "art_direction": "editorial layout, information design masterpiece, volumetric lighting, sharp focus, professional {INDUSTRY} color grading, museum exhibition quality",
        "special_effects": {
          "latest_product": "with futuristic holographic elements for {END_YEAR} concept {PRODUCT_CATEGORY}",
          "vintage_product": "with aged paper texture and sepia tone for historical {START_YEAR} products",
          "premium_feel": "with ray-traced reflections and depth-of-field bokeh"
        },
        "aspect_ratio": "--ar 16:9",
        "version": "--v 6.0",
        "stylization": "--stylize 300 (balanced realism and artistry)"
      }
    },

    "image_size_options": {
      "4k_standard": "5120x2880 (16:9 4K Ultra HD)",
      "8k_ultra": "7680x4320 (16:9 8K Ultra HD)",
      "2k_web": "2560x1440 (16:9 2K for web)",
      "portrait_4k": "2160x3840 (9:16 portrait 4K)",
      "square_4k": "4096x4096 (1:1 square 4K)"
    },

    "use_cases": {
      "brand_anniversary": "品牌周年庆典海报、投资者报告封面、展厅核心展品",
      "museum_exhibition": "博物馆主题展览、品牌历史馆核心视觉、教育机构案例教学",
      "social_media": "微博/小红书/Instagram高质量内容、品牌官方宣传、媒体深度报道配图",
      "commercial_print": "杂志封面/内页、合作伙伴礼品、高端客户俱乐部纪念品、A0/A1尺寸海报打印"
    },

    "customization_checklist": [
      "✓ 替换所有{VARIABLE}为实际品牌信息",
      "✓ 填充完整产品阵容清单（12-13款）",
      "✓ 定义3-5个品牌发展时代",
      "✓ 选择匹配的品牌配色方案",
      "✓ 列出关键技术演进指标",
      "✓ 添加品牌独特元素（logo演变、经典色、标志性技术）",
      "✓ 确定目标分辨率（4K/8K）",
      "✓ 调整风格化参数（realistic vs artistic）"
    ],

    "example_filled_prompt": {
      "brand": "小米手机 2010-2025",
      "full_prompt": "A massive, encyclopedic 16:9 3D infographic poster titled \"THE EVOLUTION OF XIAOMI | 小米手机进化史 2010-2025\". The visual style is a high-end fusion of museum-grade smartphone photography and complex technical engineering blueprints.\n\nThe Hero Lineup: A complete chronological lineup of 13 iconic Xiaomi smartphones arranged horizontally across the center on a precision metal measurement scale:\n2011 Mi 1 (1999元) → 2012 Mi 2 → 2013 Redmi Note → 2014 Mi 4 (steel frame) → 2016 Mi MIX (bezel-less) → 2017 Mi 6 → 2019 Mi 9 → 2020 Mi 10 → 2021 Mi 11 Ultra → 2022 Mi 12S Ultra → 2023 Mi 13 Ultra → 2024 Mi 14 Ultra → 2025 Mi 15 Ultra (AI flagship).\n\nRendering: Hyper-realistic 3D, 8k resolution. Emphasis on material evolution: plastic 2011 models vs. premium ceramic, glass, titanium 2025 flagships with AI capabilities.\n\nBackground: Deep orange-to-copper gradient (Xiaomi's MIUI color). Layered with \"为发烧而生\" slogan, MIUI interface screenshots, Lei Jun keynotes, India store openings, IPO newspapers, \"2010-2025\" and \"15 YEARS\" markers.\n\nHeader: Xiaomi \"MI\" logo in brushed metal 3D relief, bold sans-serif title \"THE EVOLUTION OF XIAOMI | 小米手机进化史 2010-2025\" with \"15 YEARS\" badge.\n\nInformation Layer:\n- Dense white hairlines connecting camera modules, bezels, fingerprint sensors to text blocks showing Snapdragon generations, RAM/ROM, camera MP (8MP→200MP→AI), battery, charging (18W→120W), price, AI features\n- Five era modules: \"发烧友时代 2011-2013 (Enthusiast Era)\" flame icon, \"性价比之王 2014-2017 (Value King)\" crown icon, \"全面屏革命 2018-2020 (Full-Screen Revolution)\" screen icon, \"高端化征程 2021-2024 (Premium Journey)\" mountain icon, \"AI智能新纪元 2025 (AI Era)\" brain icon\n- Magnifying inserts: steel frame texture, ceramic close-up, sensor size evolution, under-display fingerprint, Leica coating, AI neural engine\n- Bottom strip: YEAR | MODEL | PROCESSOR | RAM/ROM | CAMERA | BATTERY | CHARGING | PRICE | 二手价值 | AI FEATURES\n\nFloating elements: pop-up camera patents, global expansion map (China/India/Europe), MIUI→HyperOS evolution tree, market share chart, IoT/EV/Smart Home ecosystem, sustainability milestones.\n\nTechnical Specs: Octane render, Unreal Engine 5, editorial layout, volumetric lighting, sharp focus, consumer electronics color grading, museum quality with holographic AI elements for 2025. --ar 16:9 --v 6.0 --stylize 300"
    },

    "advanced_tips": {
      "color_psychology": {
        "orange/copper": "创新、活力、科技感（小米、华为）",
        "racing_green": "传承、赛道、奢华（保时捷、捷豹）",
        "space_gray": "极简、高端、设计感（苹果）",
        "electric_blue": "未来、电动、智能（特斯拉、蔚来）"
      },
      "visual_hierarchy": {
        "primary_focus": "中央产品阵容（最大、最清晰）",
        "secondary_focus": "时代划分模块（中等大小、浮动）",
        "tertiary_details": "技术标注、数据条、漂浮元素（细节、辅助）"
      },
      "storytelling_elements": {
        "emotional_anchors": "价格标签（1999元）、里程碑事件（勒芒冠军）、粉丝文化（钉子户）、技术突破（卫星通信）",
        "nostalgia_triggers": "早期产品设计、经典配色、标志性广告语、时代背景元素",
        "future_vision": "最新产品的科幻感、全息效果、概念车特写"
      },
      "technical_accuracy": {
        "research_requirements": "产品发布时间、准确规格参数、历史里程碑事件、市场数据",
        "fact_checking": "处理器型号、相机规格、价格信息、销量数据、赛事成绩",
        "citation_elements": "在背景水印中嵌入新闻报道、官方数据、权威认证"
      }
    }
  }
}
