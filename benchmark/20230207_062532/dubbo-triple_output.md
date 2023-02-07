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
# Warmup Iteration   1: 1.099 ops/ms
# Warmup Iteration   2: 2.342 ops/ms
# Warmup Iteration   3: 5.509 ops/ms
Iteration   1: 5.978 ops/ms
Iteration   2: 5.921 ops/ms
Iteration   3: 6.128 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  6.009 ±(99.9%) 1.949 ops/ms [Average]
  (min, avg, max) = (5.921, 6.009, 6.128), stdev = 0.107
  CI (99.9%): [4.059, 7.958] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:15
# Fork: 1 of 1
# Warmup Iteration   1: 1.483 ops/ms
# Warmup Iteration   2: 4.258 ops/ms
# Warmup Iteration   3: 5.921 ops/ms
Iteration   1: 6.348 ops/ms
Iteration   2: 6.313 ops/ms
Iteration   3: 6.102 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  6.254 ±(99.9%) 2.434 ops/ms [Average]
  (min, avg, max) = (6.102, 6.254, 6.348), stdev = 0.133
  CI (99.9%): [3.821, 8.688] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:03
# Fork: 1 of 1
# Warmup Iteration   1: 1.483 ops/ms
# Warmup Iteration   2: 4.265 ops/ms
# Warmup Iteration   3: 5.868 ops/ms
Iteration   1: 5.947 ops/ms
Iteration   2: 5.936 ops/ms
Iteration   3: 6.179 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  6.021 ±(99.9%) 2.498 ops/ms [Average]
  (min, avg, max) = (5.936, 6.021, 6.179), stdev = 0.137
  CI (99.9%): [3.522, 8.519] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:58
# Fork: 1 of 1
# Warmup Iteration   1: 1.551 ops/ms
# Warmup Iteration   2: 4.203 ops/ms
# Warmup Iteration   3: 4.979 ops/ms
Iteration   1: 5.209 ops/ms
Iteration   2: 5.190 ops/ms
Iteration   3: 5.274 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.224 ±(99.9%) 0.800 ops/ms [Average]
  (min, avg, max) = (5.190, 5.224, 5.274), stdev = 0.044
  CI (99.9%): [4.425, 6.024] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:50
# Fork: 1 of 1
# Warmup Iteration   1: 19.542 ±(99.9%) 0.081 ms/op
# Warmup Iteration   2: 7.511 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 5.813 ±(99.9%) 0.013 ms/op
Iteration   1: 5.388 ±(99.9%) 0.025 ms/op
Iteration   2: 5.495 ±(99.9%) 0.012 ms/op
Iteration   3: 5.485 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.456 ±(99.9%) 1.074 ms/op [Average]
  (min, avg, max) = (5.388, 5.456, 5.495), stdev = 0.059
  CI (99.9%): [4.383, 6.530] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:43
# Fork: 1 of 1
# Warmup Iteration   1: 17.553 ±(99.9%) 0.070 ms/op
# Warmup Iteration   2: 6.060 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 5.176 ±(99.9%) 0.007 ms/op
Iteration   1: 5.076 ±(99.9%) 0.007 ms/op
Iteration   2: 5.110 ±(99.9%) 0.007 ms/op
Iteration   3: 5.279 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.155 ±(99.9%) 1.984 ms/op [Average]
  (min, avg, max) = (5.076, 5.155, 5.279), stdev = 0.109
  CI (99.9%): [3.171, 7.139] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:37
# Fork: 1 of 1
# Warmup Iteration   1: 18.883 ±(99.9%) 0.093 ms/op
# Warmup Iteration   2: 6.845 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 5.326 ±(99.9%) 0.015 ms/op
Iteration   1: 5.439 ±(99.9%) 0.023 ms/op
Iteration   2: 5.219 ±(99.9%) 0.019 ms/op
Iteration   3: 5.311 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.323 ±(99.9%) 2.021 ms/op [Average]
  (min, avg, max) = (5.219, 5.323, 5.439), stdev = 0.111
  CI (99.9%): [3.302, 7.344] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:31
# Fork: 1 of 1
# Warmup Iteration   1: 19.199 ±(99.9%) 0.098 ms/op
# Warmup Iteration   2: 8.045 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 6.251 ±(99.9%) 0.014 ms/op
Iteration   1: 6.108 ±(99.9%) 0.018 ms/op
Iteration   2: 6.218 ±(99.9%) 0.012 ms/op
Iteration   3: 6.092 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.139 ±(99.9%) 1.257 ms/op [Average]
  (min, avg, max) = (6.092, 6.139, 6.218), stdev = 0.069
  CI (99.9%): [4.882, 7.397] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:25
# Fork: 1 of 1
# Warmup Iteration   1: 17.818 ±(99.9%) 0.297 ms/op
# Warmup Iteration   2: 6.478 ±(99.9%) 0.044 ms/op
# Warmup Iteration   3: 5.866 ±(99.9%) 0.027 ms/op
Iteration   1: 5.278 ±(99.9%) 0.017 ms/op
                 createUser·p0.00:   2.478 ms/op
                 createUser·p0.50:   4.948 ms/op
                 createUser·p0.90:   6.439 ms/op
                 createUser·p0.95:   7.029 ms/op
                 createUser·p0.99:   10.060 ms/op
                 createUser·p0.999:  22.637 ms/op
                 createUser·p0.9999: 25.918 ms/op
                 createUser·p1.00:   26.542 ms/op

Iteration   2: 5.134 ±(99.9%) 0.016 ms/op
                 createUser·p0.00:   2.540 ms/op
                 createUser·p0.50:   4.915 ms/op
                 createUser·p0.90:   6.038 ms/op
                 createUser·p0.95:   6.701 ms/op
                 createUser·p0.99:   9.224 ms/op
                 createUser·p0.999:  24.000 ms/op
                 createUser·p0.9999: 27.984 ms/op
                 createUser·p1.00:   33.161 ms/op

Iteration   3: 5.133 ±(99.9%) 0.017 ms/op
                 createUser·p0.00:   1.700 ms/op
                 createUser·p0.50:   4.858 ms/op
                 createUser·p0.90:   6.177 ms/op
                 createUser·p0.95:   6.971 ms/op
                 createUser·p0.99:   8.798 ms/op
                 createUser·p0.999:  26.215 ms/op
                 createUser·p0.9999: 35.768 ms/op
                 createUser·p1.00:   36.110 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 185183
  mean =      5.180 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5 
    [ 2.500,  5.000) = 105876 
    [ 5.000,  7.500) = 73486 
    [ 7.500, 10.000) = 4486 
    [10.000, 12.500) = 808 
    [12.500, 15.000) = 239 
    [15.000, 17.500) = 37 
    [17.500, 20.000) = 30 
    [20.000, 22.500) = 25 
    [22.500, 25.000) = 54 
    [25.000, 27.500) = 71 
    [27.500, 30.000) = 30 
    [30.000, 32.500) = 7 
    [32.500, 35.000) = 12 
    [35.000, 37.500) = 17 

  Percentiles, ms/op:
      p(0.0000) =      1.700 ms/op
     p(50.0000) =      4.899 ms/op
     p(90.0000) =      6.242 ms/op
     p(95.0000) =      6.930 ms/op
     p(99.0000) =      9.273 ms/op
     p(99.9000) =     23.286 ms/op
     p(99.9900) =     34.700 ms/op
     p(99.9990) =     35.999 ms/op
     p(99.9999) =     36.110 ms/op
    p(100.0000) =     36.110 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:19
# Fork: 1 of 1
# Warmup Iteration   1: 16.686 ±(99.9%) 0.308 ms/op
# Warmup Iteration   2: 6.807 ±(99.9%) 0.050 ms/op
# Warmup Iteration   3: 5.174 ±(99.9%) 0.019 ms/op
Iteration   1: 5.195 ±(99.9%) 0.020 ms/op
                 existUser·p0.00:   0.483 ms/op
                 existUser·p0.50:   4.841 ms/op
                 existUser·p0.90:   6.439 ms/op
                 existUser·p0.95:   7.700 ms/op
                 existUser·p0.99:   10.448 ms/op
                 existUser·p0.999:  24.779 ms/op
                 existUser·p0.9999: 26.640 ms/op
                 existUser·p1.00:   26.739 ms/op

Iteration   2: 5.077 ±(99.9%) 0.015 ms/op
                 existUser·p0.00:   1.837 ms/op
                 existUser·p0.50:   4.784 ms/op
                 existUser·p0.90:   6.275 ms/op
                 existUser·p0.95:   7.356 ms/op
                 existUser·p0.99:   9.283 ms/op
                 existUser·p0.999:  13.990 ms/op
                 existUser·p0.9999: 25.759 ms/op
                 existUser·p1.00:   27.361 ms/op

Iteration   3: 5.112 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   2.228 ms/op
                 existUser·p0.50:   4.850 ms/op
                 existUser·p0.90:   6.136 ms/op
                 existUser·p0.95:   6.939 ms/op
                 existUser·p0.99:   9.257 ms/op
                 existUser·p0.999:  23.673 ms/op
                 existUser·p0.9999: 27.597 ms/op
                 existUser·p1.00:   28.115 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 187219
  mean =      5.128 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14 
    [ 2.500,  5.000) = 112738 
    [ 5.000,  7.500) = 66250 
    [ 7.500, 10.000) = 6589 
    [10.000, 12.500) = 975 
    [12.500, 15.000) = 339 
    [15.000, 17.500) = 93 
    [17.500, 20.000) = 25 
    [20.000, 22.500) = 18 
    [22.500, 25.000) = 48 
    [25.000, 27.500) = 124 

  Percentiles, ms/op:
      p(0.0000) =      0.483 ms/op
     p(50.0000) =      4.825 ms/op
     p(90.0000) =      6.267 ms/op
     p(95.0000) =      7.315 ms/op
     p(99.0000) =      9.699 ms/op
     p(99.9000) =     21.234 ms/op
     p(99.9900) =     26.715 ms/op
     p(99.9990) =     27.972 ms/op
     p(99.9999) =     28.115 ms/op
    p(100.0000) =     28.115 ms/op


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
# Warmup Iteration   1: 18.635 ±(99.9%) 0.277 ms/op
# Warmup Iteration   2: 6.529 ±(99.9%) 0.044 ms/op
# Warmup Iteration   3: 5.551 ±(99.9%) 0.023 ms/op
Iteration   1: 5.371 ±(99.9%) 0.018 ms/op
                 getUser·p0.00:   2.249 ms/op
                 getUser·p0.50:   5.120 ms/op
                 getUser·p0.90:   6.218 ms/op
                 getUser·p0.95:   7.315 ms/op
                 getUser·p0.99:   10.813 ms/op
                 getUser·p0.999:  22.343 ms/op
                 getUser·p0.9999: 25.761 ms/op
                 getUser·p1.00:   27.230 ms/op

Iteration   2: 5.521 ±(99.9%) 0.023 ms/op
                 getUser·p0.00:   2.535 ms/op
                 getUser·p0.50:   5.145 ms/op
                 getUser·p0.90:   6.824 ms/op
                 getUser·p0.95:   8.569 ms/op
                 getUser·p0.99:   12.730 ms/op
                 getUser·p0.999:  18.743 ms/op
                 getUser·p0.9999: 30.966 ms/op
                 getUser·p1.00:   31.195 ms/op

Iteration   3: 5.593 ±(99.9%) 0.022 ms/op
                 getUser·p0.00:   2.728 ms/op
                 getUser·p0.50:   5.218 ms/op
                 getUser·p0.90:   7.127 ms/op
                 getUser·p0.95:   8.167 ms/op
                 getUser·p0.99:   11.321 ms/op
                 getUser·p0.999:  28.888 ms/op
                 getUser·p0.9999: 33.376 ms/op
                 getUser·p1.00:   33.686 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 174672
  mean =      5.493 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10 
    [ 2.500,  5.000) = 69202 
    [ 5.000,  7.500) = 93808 
    [ 7.500, 10.000) = 7864 
    [10.000, 12.500) = 2560 
    [12.500, 15.000) = 778 
    [15.000, 17.500) = 184 
    [17.500, 20.000) = 104 
    [20.000, 22.500) = 10 
    [22.500, 25.000) = 37 
    [25.000, 27.500) = 19 
    [27.500, 30.000) = 39 
    [30.000, 32.500) = 44 
    [32.500, 35.000) = 13 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.249 ms/op
     p(50.0000) =      5.161 ms/op
     p(90.0000) =      6.726 ms/op
     p(95.0000) =      8.118 ms/op
     p(99.0000) =     11.682 ms/op
     p(99.9000) =     18.951 ms/op
     p(99.9900) =     32.032 ms/op
     p(99.9990) =     33.686 ms/op
     p(99.9999) =     33.686 ms/op
    p(100.0000) =     33.686 ms/op


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
# Warmup Iteration   1: 20.683 ±(99.9%) 0.321 ms/op
# Warmup Iteration   2: 7.500 ±(99.9%) 0.051 ms/op
# Warmup Iteration   3: 6.057 ±(99.9%) 0.022 ms/op
Iteration   1: 5.798 ±(99.9%) 0.020 ms/op
                 listUser·p0.00:   2.359 ms/op
                 listUser·p0.50:   5.505 ms/op
                 listUser·p0.90:   6.611 ms/op
                 listUser·p0.95:   7.545 ms/op
                 listUser·p0.99:   10.650 ms/op
                 listUser·p0.999:  25.166 ms/op
                 listUser·p0.9999: 27.127 ms/op
                 listUser·p1.00:   28.410 ms/op

Iteration   2: 6.003 ±(99.9%) 0.020 ms/op
                 listUser·p0.00:   2.560 ms/op
                 listUser·p0.50:   5.743 ms/op
                 listUser·p0.90:   6.873 ms/op
                 listUser·p0.95:   7.676 ms/op
                 listUser·p0.99:   11.239 ms/op
                 listUser·p0.999:  26.693 ms/op
                 listUser·p0.9999: 30.081 ms/op
                 listUser·p1.00:   32.145 ms/op

Iteration   3: 6.075 ±(99.9%) 0.022 ms/op
                 listUser·p0.00:   3.174 ms/op
                 listUser·p0.50:   5.792 ms/op
                 listUser·p0.90:   6.922 ms/op
                 listUser·p0.95:   8.143 ms/op
                 listUser·p0.99:   11.551 ms/op
                 listUser·p0.999:  25.838 ms/op
                 listUser·p0.9999: 28.598 ms/op
                 listUser·p1.00:   30.278 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 160949
  mean =      5.956 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1 
    [ 2.500,  5.000) = 11586 
    [ 5.000,  7.500) = 140116 
    [ 7.500, 10.000) = 6324 
    [10.000, 12.500) = 1869 
    [12.500, 15.000) = 509 
    [15.000, 17.500) = 120 
    [17.500, 20.000) = 60 
    [20.000, 22.500) = 80 
    [22.500, 25.000) = 81 
    [25.000, 27.500) = 127 
    [27.500, 30.000) = 69 
    [30.000, 32.500) = 7 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.359 ms/op
     p(50.0000) =      5.685 ms/op
     p(90.0000) =      6.808 ms/op
     p(95.0000) =      7.778 ms/op
     p(99.0000) =     11.207 ms/op
     p(99.9000) =     25.756 ms/op
     p(99.9900) =     29.249 ms/op
     p(99.9990) =     31.486 ms/op
     p(99.9999) =     32.145 ms/op
    p(100.0000) =     32.145 ms/op


# Run complete. Total time: 00:13:16

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   6.009 ± 1.949  ops/ms
ClientPb.existUser                       thrpt       3   6.254 ± 2.434  ops/ms
ClientPb.getUser                         thrpt       3   6.021 ± 2.498  ops/ms
ClientPb.listUser                        thrpt       3   5.224 ± 0.800  ops/ms
ClientPb.createUser                       avgt       3   5.456 ± 1.074   ms/op
ClientPb.existUser                        avgt       3   5.155 ± 1.984   ms/op
ClientPb.getUser                          avgt       3   5.323 ± 2.021   ms/op
ClientPb.listUser                         avgt       3   6.139 ± 1.257   ms/op
ClientPb.createUser                     sample  185183   5.180 ± 0.010   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.700           ms/op
ClientPb.createUser:createUser·p0.50    sample           4.899           ms/op
ClientPb.createUser:createUser·p0.90    sample           6.242           ms/op
ClientPb.createUser:createUser·p0.95    sample           6.930           ms/op
ClientPb.createUser:createUser·p0.99    sample           9.273           ms/op
ClientPb.createUser:createUser·p0.999   sample          23.286           ms/op
ClientPb.createUser:createUser·p0.9999  sample          34.700           ms/op
ClientPb.createUser:createUser·p1.00    sample          36.110           ms/op
ClientPb.existUser                      sample  187219   5.128 ± 0.010   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.483           ms/op
ClientPb.existUser:existUser·p0.50      sample           4.825           ms/op
ClientPb.existUser:existUser·p0.90      sample           6.267           ms/op
ClientPb.existUser:existUser·p0.95      sample           7.315           ms/op
ClientPb.existUser:existUser·p0.99      sample           9.699           ms/op
ClientPb.existUser:existUser·p0.999     sample          21.234           ms/op
ClientPb.existUser:existUser·p0.9999    sample          26.715           ms/op
ClientPb.existUser:existUser·p1.00      sample          28.115           ms/op
ClientPb.getUser                        sample  174672   5.493 ± 0.012   ms/op
ClientPb.getUser:getUser·p0.00          sample           2.249           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.161           ms/op
ClientPb.getUser:getUser·p0.90          sample           6.726           ms/op
ClientPb.getUser:getUser·p0.95          sample           8.118           ms/op
ClientPb.getUser:getUser·p0.99          sample          11.682           ms/op
ClientPb.getUser:getUser·p0.999         sample          18.951           ms/op
ClientPb.getUser:getUser·p0.9999        sample          32.032           ms/op
ClientPb.getUser:getUser·p1.00          sample          33.686           ms/op
ClientPb.listUser                       sample  160949   5.956 ± 0.012   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.359           ms/op
ClientPb.listUser:listUser·p0.50        sample           5.685           ms/op
ClientPb.listUser:listUser·p0.90        sample           6.808           ms/op
ClientPb.listUser:listUser·p0.95        sample           7.778           ms/op
ClientPb.listUser:listUser·p0.99        sample          11.207           ms/op
ClientPb.listUser:listUser·p0.999       sample          25.756           ms/op
ClientPb.listUser:listUser·p0.9999      sample          29.249           ms/op
ClientPb.listUser:listUser·p1.00        sample          32.145           ms/op
