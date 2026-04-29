---
title:          "An MLIR-Based Compilation Flow for CGRAs: Optimized CDFG Generation, Control-Flow Handling, and Scalability"
date:           2026-03-27 00:00:00 +0800
selected:       true
pub:            "International Symposium of Electronics Design Automation (ISEDA)"
# pub_pre:        "Submitted to "
# pub_post:       'Under review.'
pub_last:       ' <span class="badge badge-pill badge-publication badge-warning">Best paper candidate</span>'
pub_date:       "2026"
#semantic_scholar_id: b7f7c9912089092229ba8a87cfae996a36517020  # use this to retrieve citation count
abstract: >-
  Mapping high-level applications with diverse memory access patterns and control structures onto Coarse-Grained Reconfigurable Architectures (CGRAs) remains a significant compilation challenge. This paper proposes a unified MLIR based compilation flow that bridges multiple frontends (C/C++ and ONNX) to hardware-specific spatial mappings. We introduce an optimized Control-Data Flow Graph (CDFG) generation framework featuring dataflow pruning, control-flow handling via if-conversion and carry nodes, and memory access linearization. Evaluated on fundamental Polybench kernels, our approach significantly reduces mapped node counts and achieves an optimal Initiation Interval (II) compared to a state-of-the-art MLIR compiler. These results highlight the high structural quality of our generated CDFGs and demonstrate practical portability across different CGRA backends.

cover: /assets/images/covers/ISEDA26.png
authors:
  - Jiahang Lou*
  - Jiayao Hu*
  - Jianrong Zhang
  - Yikuan Chen
  - Zewei Zhong
  - Yuan Dai
  - Wenbo Yin
  - Lingli Wang
  - Yu He
  - Qing He
#links:
  #paper: https://ieeexplore.ieee.org/document/11132704
---