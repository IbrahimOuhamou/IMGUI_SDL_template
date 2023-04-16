#بسم الله الرحمن الرحيم
project('SDL_Imgui', 'cpp',
        default_options: 'default_library=static')

sdl2_dep = dependency('sdl2')

files = ['main.cpp',
         'third_party/imgui/imgui.cpp',
         'third_party/imgui/imgui_widgets.cpp',
         'third_party/imgui/imgui_demo.cpp',
         'third_party/imgui/imgui_draw.cpp',
         'third_party/imgui/imgui_tables.cpp',
         'third_party/imgui/imgui_impl_sdl2.cpp',
         'third_party/imgui/imgui_impl_sdlrenderer.cpp']

executable('BismiAllah_SDL_IMGUI', files,
           win_subsystem: 'windows',
           dependencies: sdl2_dep)