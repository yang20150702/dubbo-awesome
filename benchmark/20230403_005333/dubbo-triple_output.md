# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 1.799 ops/ms
# Warmup Iteration   2: 4.325 ops/ms
# Warmup Iteration   3: 7.795 ops/ms
Iteration   1: 7.845 ops/ms
Iteration   2: 8.774 ops/ms
Iteration   3: 8.524 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  8.381 ±(99.9%) 8.765 ops/ms [Average]
  (min, avg, max) = (7.845, 8.381, 8.774), stdev = 0.480
  CI (99.9%): [≈ 0, 17.146] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.683 ops/ms
# Warmup Iteration   2: 7.249 ops/ms
# Warmup Iteration   3: 8.575 ops/ms
Iteration   1: 8.888 ops/ms
Iteration   2: 8.364 ops/ms
Iteration   3: 8.539 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.597 ±(99.9%) 4.868 ops/ms [Average]
  (min, avg, max) = (8.364, 8.597, 8.888), stdev = 0.267
  CI (99.9%): [3.729, 13.465] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:58
# Fork: 1 of 1
# Warmup Iteration   1: 2.368 ops/ms
# Warmup Iteration   2: 6.853 ops/ms
# Warmup Iteration   3: 8.447 ops/ms
Iteration   1: 8.300 ops/ms
Iteration   2: 8.678 ops/ms
Iteration   3: 8.468 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  8.482 ±(99.9%) 3.452 ops/ms [Average]
  (min, avg, max) = (8.300, 8.482, 8.678), stdev = 0.189
  CI (99.9%): [5.030, 11.934] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 2.259 ops/ms
# Warmup Iteration   2: 5.952 ops/ms
# Warmup Iteration   3: 7.203 ops/ms
Iteration   1: 6.954 ops/ms
Iteration   2: 7.211 ops/ms
Iteration   3: 7.358 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.174 ±(99.9%) 3.738 ops/ms [Average]
  (min, avg, max) = (6.954, 7.174, 7.358), stdev = 0.205
  CI (99.9%): [3.436, 10.912] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 12.509 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 4.605 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.960 ±(99.9%) 0.005 ms/op
Iteration   1: 3.802 ±(99.9%) 0.003 ms/op
Iteration   2: 3.717 ±(99.9%) 0.010 ms/op
Iteration   3: 3.859 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.793 ±(99.9%) 1.299 ms/op [Average]
  (min, avg, max) = (3.717, 3.793, 3.859), stdev = 0.071
  CI (99.9%): [2.494, 5.091] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 9.400 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.935 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.637 ±(99.9%) 0.007 ms/op
Iteration   1: 3.609 ±(99.9%) 0.008 ms/op
Iteration   2: 3.570 ±(99.9%) 0.009 ms/op
Iteration   3: 3.724 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.634 ±(99.9%) 1.461 ms/op [Average]
  (min, avg, max) = (3.570, 3.634, 3.724), stdev = 0.080
  CI (99.9%): [2.174, 5.095] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 11.165 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 4.213 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.940 ±(99.9%) 0.010 ms/op
Iteration   1: 3.741 ±(99.9%) 0.006 ms/op
Iteration   2: 3.853 ±(99.9%) 0.010 ms/op
Iteration   3: 3.829 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.808 ±(99.9%) 1.084 ms/op [Average]
  (min, avg, max) = (3.741, 3.808, 3.853), stdev = 0.059
  CI (99.9%): [2.723, 4.892] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:30
# Fork: 1 of 1
# Warmup Iteration   1: 12.620 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 4.930 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.514 ±(99.9%) 0.010 ms/op
Iteration   1: 4.469 ±(99.9%) 0.010 ms/op
Iteration   2: 4.374 ±(99.9%) 0.013 ms/op
Iteration   3: 4.225 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.356 ±(99.9%) 2.248 ms/op [Average]
  (min, avg, max) = (4.225, 4.356, 4.469), stdev = 0.123
  CI (99.9%): [2.109, 6.604] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:24
# Fork: 1 of 1
# Warmup Iteration   1: 11.367 ±(99.9%) 0.155 ms/op
# Warmup Iteration   2: 5.006 ±(99.9%) 0.028 ms/op
# Warmup Iteration   3: 4.300 ±(99.9%) 0.018 ms/op
Iteration   1: 3.879 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.145 ms/op
                 createUser·p0.50:   3.752 ms/op
                 createUser·p0.90:   4.547 ms/op
                 createUser·p0.95:   5.128 ms/op
                 createUser·p0.99:   7.168 ms/op
                 createUser·p0.999:  11.187 ms/op
                 createUser·p0.9999: 23.842 ms/op
                 createUser·p1.00:   24.347 ms/op

Iteration   2: 3.848 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.432 ms/op
                 createUser·p0.50:   3.686 ms/op
                 createUser·p0.90:   4.391 ms/op
                 createUser·p0.95:   4.899 ms/op
                 createUser·p0.99:   7.020 ms/op
                 createUser·p0.999:  22.282 ms/op
                 createUser·p0.9999: 24.828 ms/op
                 createUser·p1.00:   25.690 ms/op

Iteration   3: 3.825 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.642 ms/op
                 createUser·p0.50:   3.666 ms/op
                 createUser·p0.90:   4.366 ms/op
                 createUser·p0.95:   4.817 ms/op
                 createUser·p0.99:   7.610 ms/op
                 createUser·p0.999:  23.605 ms/op
                 createUser·p0.9999: 30.736 ms/op
                 createUser·p1.00:   31.523 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 249329
  mean =      3.850 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 880 
    [ 2.500,  5.000) = 236749 
    [ 5.000,  7.500) = 9444 
    [ 7.500, 10.000) = 1566 
    [10.000, 12.500) = 289 
    [12.500, 15.000) = 74 
    [15.000, 17.500) = 31 
    [17.500, 20.000) = 23 
    [20.000, 22.500) = 88 
    [22.500, 25.000) = 110 
    [25.000, 27.500) = 27 
    [27.500, 30.000) = 32 
    [30.000, 32.500) = 16 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.145 ms/op
     p(50.0000) =      3.703 ms/op
     p(90.0000) =      4.424 ms/op
     p(95.0000) =      4.940 ms/op
     p(99.0000) =      7.365 ms/op
     p(99.9000) =     21.419 ms/op
     p(99.9900) =     28.871 ms/op
     p(99.9990) =     31.312 ms/op
     p(99.9999) =     31.523 ms/op
    p(100.0000) =     31.523 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 10.781 ±(99.9%) 0.146 ms/op
# Warmup Iteration   2: 4.006 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.752 ±(99.9%) 0.010 ms/op
Iteration   1: 3.838 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.460 ms/op
                 existUser·p0.50:   3.576 ms/op
                 existUser·p0.90:   5.022 ms/op
                 existUser·p0.95:   5.399 ms/op
                 existUser·p0.99:   7.183 ms/op
                 existUser·p0.999:  14.189 ms/op
                 existUser·p0.9999: 28.344 ms/op
                 existUser·p1.00:   28.901 ms/op

Iteration   2: 3.468 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.292 ms/op
                 existUser·p0.50:   3.420 ms/op
                 existUser·p0.90:   3.699 ms/op
                 existUser·p0.95:   3.949 ms/op
                 existUser·p0.99:   6.005 ms/op
                 existUser·p0.999:  9.388 ms/op
                 existUser·p0.9999: 25.723 ms/op
                 existUser·p1.00:   26.608 ms/op

Iteration   3: 3.713 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   1.739 ms/op
                 existUser·p0.50:   3.592 ms/op
                 existUser·p0.90:   4.211 ms/op
                 existUser·p0.95:   4.653 ms/op
                 existUser·p0.99:   6.423 ms/op
                 existUser·p0.999:  25.750 ms/op
                 existUser·p0.9999: 34.800 ms/op
                 existUser·p1.00:   35.193 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 261922
  mean =      3.666 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2436 
    [ 2.500,  5.000) = 246937 
    [ 5.000,  7.500) = 11145 
    [ 7.500, 10.000) = 858 
    [10.000, 12.500) = 162 
    [12.500, 15.000) = 117 
    [15.000, 17.500) = 41 
    [17.500, 20.000) = 4 
    [20.000, 22.500) = 21 
    [22.500, 25.000) = 45 
    [25.000, 27.500) = 84 
    [27.500, 30.000) = 39 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 30 
    [35.000, 37.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      1.292 ms/op
     p(50.0000) =      3.510 ms/op
     p(90.0000) =      4.260 ms/op
     p(95.0000) =      4.956 ms/op
     p(99.0000) =      6.521 ms/op
     p(99.9000) =     16.695 ms/op
     p(99.9900) =     33.208 ms/op
     p(99.9990) =     35.046 ms/op
     p(99.9999) =     35.193 ms/op
    p(100.0000) =     35.193 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 12.299 ±(99.9%) 0.141 ms/op
# Warmup Iteration   2: 4.586 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 3.930 ±(99.9%) 0.013 ms/op
Iteration   1: 3.947 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   1.706 ms/op
                 getUser·p0.50:   3.604 ms/op
                 getUser·p0.90:   4.956 ms/op
                 getUser·p0.95:   6.529 ms/op
                 getUser·p0.99:   8.618 ms/op
                 getUser·p0.999:  17.269 ms/op
                 getUser·p0.9999: 23.491 ms/op
                 getUser·p1.00:   26.444 ms/op

Iteration   2: 3.793 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.327 ms/op
                 getUser·p0.50:   3.703 ms/op
                 getUser·p0.90:   4.182 ms/op
                 getUser·p0.95:   4.407 ms/op
                 getUser·p0.99:   6.526 ms/op
                 getUser·p0.999:  23.429 ms/op
                 getUser·p0.9999: 25.826 ms/op
                 getUser·p1.00:   26.935 ms/op

Iteration   3: 3.707 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.733 ms/op
                 getUser·p0.50:   3.564 ms/op
                 getUser·p0.90:   4.145 ms/op
                 getUser·p0.95:   4.563 ms/op
                 getUser·p0.99:   6.521 ms/op
                 getUser·p0.999:  23.462 ms/op
                 getUser·p0.9999: 29.143 ms/op
                 getUser·p1.00:   31.031 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 251635
  mean =      3.813 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 528 
    [ 2.500,  5.000) = 238392 
    [ 5.000,  7.500) = 9972 
    [ 7.500, 10.000) = 2038 
    [10.000, 12.500) = 353 
    [12.500, 15.000) = 61 
    [15.000, 17.500) = 24 
    [17.500, 20.000) = 11 
    [20.000, 22.500) = 45 
    [22.500, 25.000) = 109 
    [25.000, 27.500) = 67 
    [27.500, 30.000) = 32 
    [30.000, 32.500) = 3 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.327 ms/op
     p(50.0000) =      3.621 ms/op
     p(90.0000) =      4.268 ms/op
     p(95.0000) =      5.030 ms/op
     p(99.0000) =      7.578 ms/op
     p(99.9000) =     21.037 ms/op
     p(99.9900) =     28.017 ms/op
     p(99.9990) =     30.645 ms/op
     p(99.9999) =     31.031 ms/op
    p(100.0000) =     31.031 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 12.877 ±(99.9%) 0.184 ms/op
# Warmup Iteration   2: 5.567 ±(99.9%) 0.033 ms/op
# Warmup Iteration   3: 4.628 ±(99.9%) 0.017 ms/op
Iteration   1: 4.402 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.866 ms/op
                 listUser·p0.50:   4.260 ms/op
                 listUser·p0.90:   4.792 ms/op
                 listUser·p0.95:   5.308 ms/op
                 listUser·p0.99:   8.405 ms/op
                 listUser·p0.999:  23.364 ms/op
                 listUser·p0.9999: 28.236 ms/op
                 listUser·p1.00:   29.852 ms/op

Iteration   2: 4.398 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.081 ms/op
                 listUser·p0.50:   4.334 ms/op
                 listUser·p0.90:   4.719 ms/op
                 listUser·p0.95:   5.095 ms/op
                 listUser·p0.99:   7.324 ms/op
                 listUser·p0.999:  17.016 ms/op
                 listUser·p0.9999: 20.602 ms/op
                 listUser·p1.00:   21.103 ms/op

Iteration   3: 4.351 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.605 ms/op
                 listUser·p0.50:   4.268 ms/op
                 listUser·p0.90:   4.727 ms/op
                 listUser·p0.95:   5.046 ms/op
                 listUser·p0.99:   7.504 ms/op
                 listUser·p0.999:  14.778 ms/op
                 listUser·p0.9999: 19.104 ms/op
                 listUser·p1.00:   19.235 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 218763
  mean =      4.383 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17 
    [ 2.500,  5.000) = 205225 
    [ 5.000,  7.500) = 11126 
    [ 7.500, 10.000) = 1612 
    [10.000, 12.500) = 243 
    [12.500, 15.000) = 126 
    [15.000, 17.500) = 188 
    [17.500, 20.000) = 52 
    [20.000, 22.500) = 77 
    [22.500, 25.000) = 63 
    [25.000, 27.500) = 23 

  Percentiles, ms/op:
      p(0.0000) =      1.866 ms/op
     p(50.0000) =      4.293 ms/op
     p(90.0000) =      4.743 ms/op
     p(95.0000) =      5.128 ms/op
     p(99.0000) =      7.668 ms/op
     p(99.9000) =     17.826 ms/op
     p(99.9900) =     26.378 ms/op
     p(99.9990) =     28.766 ms/op
     p(99.9999) =     29.852 ms/op
    p(100.0000) =     29.852 ms/op


# Run complete. Total time: 00:13:14

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   8.381 ± 8.765  ops/ms
ClientPb.existUser                       thrpt       3   8.597 ± 4.868  ops/ms
ClientPb.getUser                         thrpt       3   8.482 ± 3.452  ops/ms
ClientPb.listUser                        thrpt       3   7.174 ± 3.738  ops/ms
ClientPb.createUser                       avgt       3   3.793 ± 1.299   ms/op
ClientPb.existUser                        avgt       3   3.634 ± 1.461   ms/op
ClientPb.getUser                          avgt       3   3.808 ± 1.084   ms/op
ClientPb.listUser                         avgt       3   4.356 ± 2.248   ms/op
ClientPb.createUser                     sample  249329   3.850 ± 0.007   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.145           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.703           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.424           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.940           ms/op
ClientPb.createUser:createUser·p0.99    sample           7.365           ms/op
ClientPb.createUser:createUser·p0.999   sample          21.419           ms/op
ClientPb.createUser:createUser·p0.9999  sample          28.871           ms/op
ClientPb.createUser:createUser·p1.00    sample          31.523           ms/op
ClientPb.existUser                      sample  261922   3.666 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.292           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.510           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.260           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.956           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.521           ms/op
ClientPb.existUser:existUser·p0.999     sample          16.695           ms/op
ClientPb.existUser:existUser·p0.9999    sample          33.208           ms/op
ClientPb.existUser:existUser·p1.00      sample          35.193           ms/op
ClientPb.getUser                        sample  251635   3.813 ± 0.007   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.327           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.621           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.268           ms/op
ClientPb.getUser:getUser·p0.95          sample           5.030           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.578           ms/op
ClientPb.getUser:getUser·p0.999         sample          21.037           ms/op
ClientPb.getUser:getUser·p0.9999        sample          28.017           ms/op
ClientPb.getUser:getUser·p1.00          sample          31.031           ms/op
ClientPb.listUser                       sample  218763   4.383 ± 0.007   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.866           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.293           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.743           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.128           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.668           ms/op
ClientPb.listUser:listUser·p0.999       sample          17.826           ms/op
ClientPb.listUser:listUser·p0.9999      sample          26.378           ms/op
ClientPb.listUser:listUser·p1.00        sample          29.852           ms/op
