package(default_visibility = ["//tensorboard:internal"])

load("//tensorboard/defs:web.bzl", "tf_web_library")

licenses(["notice"])  # Apache 2.0

tf_web_library(
    name = "tf_debugger_dashboard",
    srcs = [
        "selection-tree-node.ts",
        "tensor-shape-helper.ts",
        "tf-debugger-dashboard.html",
        "tf-debugger-initial-dialog.html",
        "tf-debugger-line-chart.html",
        "tf-op-selector.html",
        "tf-session-runs-view.html",
        "tf-tensor-data-summary.html",
        "tf-tensor-value-multi-view.html",
        "tf-tensor-value-view.html",
    ],
    path = "/tf-debugger-dashboard",
    visibility = ["//visibility:public"],
    deps = [
        "//tensorboard/components/tf_backend",
        "//tensorboard/components/tf_card_heading",
        "//tensorboard/components/tf_categorization_utils",
        "//tensorboard/components/tf_color_scale",
        "//tensorboard/components/tf_dashboard_common",
        "//tensorboard/components/tf_imports:lodash",
        "//tensorboard/components/tf_imports:polymer",
        "//tensorboard/components/tf_paginated_view",
        "//tensorboard/components/tf_runs_selector",
        "//tensorboard/components/tf_storage",
        "//tensorboard/components/tf_tensorboard:registry",
        "//tensorboard/components/vz_line_chart",
        "//tensorboard/plugins/graph/tf_graph",
        "//tensorboard/plugins/graph/tf_graph_loader",
        "//tensorboard/plugins/histogram/vz_histogram_timeseries",
        "@org_polymer_iron_collapse",
        "@org_polymer_iron_icon",
        "@org_polymer_paper_button",
        "@org_polymer_paper_checkbox",
        "@org_polymer_paper_dropdown_menu",
        "@org_polymer_paper_icon_button",
        "@org_polymer_paper_input",
        "@org_polymer_paper_item",
        "@org_polymer_paper_menu",
        "@org_polymer_paper_progress",
        "@org_polymer_paper_slider",
        "@org_polymer_paper_spinner",
        "@org_polymer_paper_styles",
        "@org_polymer_paper_toast",
    ],
)
