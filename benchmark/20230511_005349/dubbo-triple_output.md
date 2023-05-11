# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 0.999 ops/ms
# Warmup Iteration   2: 2.373 ops/ms
# Warmup Iteration   3: 5.024 ops/ms
Iteration   1: 5.656 ops/ms
Iteration   2: 5.850 ops/ms
Iteration   3: 5.930 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.812 ±(99.9%) 2.572 ops/ms [Average]
  (min, avg, max) = (5.656, 5.812, 5.930), stdev = 0.141
  CI (99.9%): [3.240, 8.384] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:04
# Fork: 1 of 1
# Warmup Iteration   1: 1.753 ops/ms
# Warmup Iteration   2: 5.294 ops/ms
# Warmup Iteration   3: 5.905 ops/ms
Iteration   1: 6.203 ops/ms
Iteration   2: 6.286 ops/ms
Iteration   3: 6.335 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  6.275 ±(99.9%) 1.218 ops/ms [Average]
  (min, avg, max) = (6.203, 6.275, 6.335), stdev = 0.067
  CI (99.9%): [5.057, 7.493] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:11:03
# Fork: 1 of 1
# Warmup Iteration   1: 1.740 ops/ms
# Warmup Iteration   2: 5.103 ops/ms
# Warmup Iteration   3: 5.909 ops/ms
Iteration   1: 5.912 ops/ms
Iteration   2: 5.686 ops/ms
Iteration   3: 5.954 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.850 ±(99.9%) 2.629 ops/ms [Average]
  (min, avg, max) = (5.686, 5.850, 5.954), stdev = 0.144
  CI (99.9%): [3.221, 8.480] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:54
# Fork: 1 of 1
# Warmup Iteration   1: 1.617 ops/ms
# Warmup Iteration   2: 4.061 ops/ms
# Warmup Iteration   3: 5.102 ops/ms
Iteration   1: 5.239 ops/ms
Iteration   2: 5.110 ops/ms
Iteration   3: 5.209 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.186 ±(99.9%) 1.233 ops/ms [Average]
  (min, avg, max) = (5.110, 5.186, 5.239), stdev = 0.068
  CI (99.9%): [3.953, 6.419] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:49
# Fork: 1 of 1
# Warmup Iteration   1: 18.553 ±(99.9%) 0.163 ms/op
# Warmup Iteration   2: 6.798 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 5.683 ±(99.9%) 0.013 ms/op
Iteration   1: 5.581 ±(99.9%) 0.013 ms/op
Iteration   2: 5.412 ±(99.9%) 0.013 ms/op
Iteration   3: 5.582 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.525 ±(99.9%) 1.785 ms/op [Average]
  (min, avg, max) = (5.412, 5.525, 5.582), stdev = 0.098
  CI (99.9%): [3.740, 7.310] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:42
# Fork: 1 of 1
# Warmup Iteration   1: 15.241 ±(99.9%) 0.075 ms/op
# Warmup Iteration   2: 6.246 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 5.139 ±(99.9%) 0.012 ms/op
Iteration   1: 5.329 ±(99.9%) 0.008 ms/op
Iteration   2: 5.022 ±(99.9%) 0.011 ms/op
Iteration   3: 5.086 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.146 ±(99.9%) 2.955 ms/op [Average]
  (min, avg, max) = (5.022, 5.146, 5.329), stdev = 0.162
  CI (99.9%): [2.191, 8.101] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:37
# Fork: 1 of 1
# Warmup Iteration   1: 16.957 ±(99.9%) 0.081 ms/op
# Warmup Iteration   2: 6.266 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 5.406 ±(99.9%) 0.015 ms/op
Iteration   1: 5.297 ±(99.9%) 0.022 ms/op
Iteration   2: 5.499 ±(99.9%) 0.011 ms/op
Iteration   3: 5.401 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.399 ±(99.9%) 1.839 ms/op [Average]
  (min, avg, max) = (5.297, 5.399, 5.499), stdev = 0.101
  CI (99.9%): [3.560, 7.238] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:31
# Fork: 1 of 1
# Warmup Iteration   1: 18.701 ±(99.9%) 0.091 ms/op
# Warmup Iteration   2: 7.821 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 6.699 ±(99.9%) 0.019 ms/op
Iteration   1: 6.460 ±(99.9%) 0.017 ms/op
Iteration   2: 6.436 ±(99.9%) 0.014 ms/op
Iteration   3: 6.228 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.374 ±(99.9%) 2.327 ms/op [Average]
  (min, avg, max) = (6.228, 6.374, 6.460), stdev = 0.128
  CI (99.9%): [4.048, 8.701] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:25
# Fork: 1 of 1
# Warmup Iteration   1: 16.273 ±(99.9%) 0.278 ms/op
# Warmup Iteration   2: 6.878 ±(99.9%) 0.043 ms/op
# Warmup Iteration   3: 5.790 ±(99.9%) 0.023 ms/op
Iteration   1: 5.527 ±(99.9%) 0.020 ms/op
                 createUser·p0.00:   2.290 ms/op
                 createUser·p0.50:   5.243 ms/op
                 createUser·p0.90:   6.799 ms/op
                 createUser·p0.95:   7.504 ms/op
                 createUser·p0.99:   11.125 ms/op
                 createUser·p0.999:  23.201 ms/op
                 createUser·p0.9999: 29.461 ms/op
                 createUser·p1.00:   30.179 ms/op

Iteration   2: 5.602 ±(99.9%) 0.020 ms/op
                 createUser·p0.00:   2.013 ms/op
                 createUser·p0.50:   5.317 ms/op
                 createUser·p0.90:   7.111 ms/op
                 createUser·p0.95:   7.987 ms/op
                 createUser·p0.99:   9.880 ms/op
                 createUser·p0.999:  25.390 ms/op
                 createUser·p0.9999: 32.819 ms/op
                 createUser·p1.00:   34.472 ms/op

Iteration   3: 5.636 ±(99.9%) 0.024 ms/op
                 createUser·p0.00:   2.142 ms/op
                 createUser·p0.50:   5.325 ms/op
                 createUser·p0.90:   6.980 ms/op
                 createUser·p0.95:   7.807 ms/op
                 createUser·p0.99:   11.239 ms/op
                 createUser·p0.999:  29.156 ms/op
                 createUser·p0.9999: 40.522 ms/op
                 createUser·p1.00:   40.567 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 171838
  mean =      5.588 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 60355 
    [ 5.000, 10.000) = 109194 
    [10.000, 15.000) = 1863 
    [15.000, 20.000) = 188 
    [20.000, 25.000) = 35 
    [25.000, 30.000) = 128 
    [30.000, 35.000) = 61 
    [35.000, 40.000) = 6 
    [40.000, 45.000) = 8 

  Percentiles, ms/op:
      p(0.0000) =      2.013 ms/op
     p(50.0000) =      5.292 ms/op
     p(90.0000) =      6.963 ms/op
     p(95.0000) =      7.799 ms/op
     p(99.0000) =     10.682 ms/op
     p(99.9000) =     26.018 ms/op
     p(99.9900) =     34.996 ms/op
     p(99.9990) =     40.567 ms/op
     p(99.9999) =     40.567 ms/op
    p(100.0000) =     40.567 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 16.262 ±(99.9%) 0.278 ms/op
# Warmup Iteration   2: 6.908 ±(99.9%) 0.049 ms/op
# Warmup Iteration   3: 5.880 ±(99.9%) 0.025 ms/op
Iteration   1: 5.297 ±(99.9%) 0.018 ms/op
                 existUser·p0.00:   1.796 ms/op
                 existUser·p0.50:   5.005 ms/op
                 existUser·p0.90:   6.668 ms/op
                 existUser·p0.95:   7.684 ms/op
                 existUser·p0.99:   10.158 ms/op
                 existUser·p0.999:  22.479 ms/op
                 existUser·p0.9999: 28.006 ms/op
                 existUser·p1.00:   28.246 ms/op

Iteration   2: 5.093 ±(99.9%) 0.018 ms/op
                 existUser·p0.00:   1.862 ms/op
                 existUser·p0.50:   4.841 ms/op
                 existUser·p0.90:   6.324 ms/op
                 existUser·p0.95:   7.021 ms/op
                 existUser·p0.99:   9.306 ms/op
                 existUser·p0.999:  22.581 ms/op
                 existUser·p0.9999: 25.943 ms/op
                 existUser·p1.00:   27.197 ms/op

Iteration   3: 5.059 ±(99.9%) 0.018 ms/op
                 existUser·p0.00:   2.404 ms/op
                 existUser·p0.50:   4.841 ms/op
                 existUser·p0.90:   6.054 ms/op
                 existUser·p0.95:   6.865 ms/op
                 existUser·p0.99:   9.913 ms/op
                 existUser·p0.999:  24.872 ms/op
                 existUser·p0.9999: 30.540 ms/op
                 existUser·p1.00:   30.966 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 186324
  mean =      5.148 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 50 
    [ 2.500,  5.000) = 106347 
    [ 5.000,  7.500) = 72200 
    [ 7.500, 10.000) = 5998 
    [10.000, 12.500) = 1012 
    [12.500, 15.000) = 318 
    [15.000, 17.500) = 129 
    [17.500, 20.000) = 67 
    [20.000, 22.500) = 17 
    [22.500, 25.000) = 73 
    [25.000, 27.500) = 85 
    [27.500, 30.000) = 20 
    [30.000, 32.500) = 8 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.796 ms/op
     p(50.0000) =      4.891 ms/op
     p(90.0000) =      6.324 ms/op
     p(95.0000) =      7.234 ms/op
     p(99.0000) =      9.814 ms/op
     p(99.9000) =     22.523 ms/op
     p(99.9900) =     28.213 ms/op
     p(99.9990) =     30.937 ms/op
     p(99.9999) =     30.966 ms/op
    p(100.0000) =     30.966 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 16.435 ±(99.9%) 0.314 ms/op
# Warmup Iteration   2: 7.349 ±(99.9%) 0.047 ms/op
# Warmup Iteration   3: 5.642 ±(99.9%) 0.025 ms/op
Iteration   1: 5.485 ±(99.9%) 0.020 ms/op
                 getUser·p0.00:   2.630 ms/op
                 getUser·p0.50:   5.259 ms/op
                 getUser·p0.90:   6.439 ms/op
                 getUser·p0.95:   7.176 ms/op
                 getUser·p0.99:   10.289 ms/op
                 getUser·p0.999:  23.138 ms/op
                 getUser·p0.9999: 39.235 ms/op
                 getUser·p1.00:   40.108 ms/op

Iteration   2: 5.718 ±(99.9%) 0.021 ms/op
                 getUser·p0.00:   0.853 ms/op
                 getUser·p0.50:   5.382 ms/op
                 getUser·p0.90:   7.201 ms/op
                 getUser·p0.95:   8.487 ms/op
                 getUser·p0.99:   11.305 ms/op
                 getUser·p0.999:  16.089 ms/op
                 getUser·p0.9999: 33.948 ms/op
                 getUser·p1.00:   34.406 ms/op

Iteration   3: 5.655 ±(99.9%) 0.021 ms/op
                 getUser·p0.00:   2.662 ms/op
                 getUser·p0.50:   5.358 ms/op
                 getUser·p0.90:   6.889 ms/op
                 getUser·p0.95:   7.864 ms/op
                 getUser·p0.99:   11.043 ms/op
                 getUser·p0.999:  28.572 ms/op
                 getUser·p0.9999: 37.794 ms/op
                 getUser·p1.00:   38.601 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 170669
  mean =      5.617 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 53477 
    [ 5.000, 10.000) = 114466 
    [10.000, 15.000) = 2405 
    [15.000, 20.000) = 136 
    [20.000, 25.000) = 49 
    [25.000, 30.000) = 28 
    [30.000, 35.000) = 59 
    [35.000, 40.000) = 48 
    [40.000, 45.000) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.853 ms/op
     p(50.0000) =      5.325 ms/op
     p(90.0000) =      6.816 ms/op
     p(95.0000) =      7.897 ms/op
     p(99.0000) =     10.977 ms/op
     p(99.9000) =     21.987 ms/op
     p(99.9900) =     37.749 ms/op
     p(99.9990) =     39.876 ms/op
     p(99.9999) =     40.108 ms/op
    p(100.0000) =     40.108 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 19.475 ±(99.9%) 0.363 ms/op
# Warmup Iteration   2: 7.931 ±(99.9%) 0.059 ms/op
# Warmup Iteration   3: 6.517 ±(99.9%) 0.023 ms/op
Iteration   1: 6.347 ±(99.9%) 0.025 ms/op
                 listUser·p0.00:   2.724 ms/op
                 listUser·p0.50:   5.980 ms/op
                 listUser·p0.90:   7.709 ms/op
                 listUser·p0.95:   8.946 ms/op
                 listUser·p0.99:   11.960 ms/op
                 listUser·p0.999:  28.466 ms/op
                 listUser·p0.9999: 35.062 ms/op
                 listUser·p1.00:   35.652 ms/op

Iteration   2: 6.605 ±(99.9%) 0.025 ms/op
                 listUser·p0.00:   2.675 ms/op
                 listUser·p0.50:   6.275 ms/op
                 listUser·p0.90:   7.913 ms/op
                 listUser·p0.95:   8.946 ms/op
                 listUser·p0.99:   12.456 ms/op
                 listUser·p0.999:  28.330 ms/op
                 listUser·p0.9999: 31.238 ms/op
                 listUser·p1.00:   33.292 ms/op

Iteration   3: 6.298 ±(99.9%) 0.023 ms/op
                 listUser·p0.00:   1.778 ms/op
                 listUser·p0.50:   6.013 ms/op
                 listUser·p0.90:   7.332 ms/op
                 listUser·p0.95:   8.208 ms/op
                 listUser·p0.99:   12.567 ms/op
                 listUser·p0.999:  26.640 ms/op
                 listUser·p0.9999: 30.111 ms/op
                 listUser·p1.00:   31.031 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 149673
  mean =      6.414 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4 
    [ 2.500,  5.000) = 6376 
    [ 5.000,  7.500) = 126008 
    [ 7.500, 10.000) = 13155 
    [10.000, 12.500) = 2788 
    [12.500, 15.000) = 667 
    [15.000, 17.500) = 284 
    [17.500, 20.000) = 76 
    [20.000, 22.500) = 40 
    [22.500, 25.000) = 37 
    [25.000, 27.500) = 78 
    [27.500, 30.000) = 96 
    [30.000, 32.500) = 50 
    [32.500, 35.000) = 8 
    [35.000, 37.500) = 6 

  Percentiles, ms/op:
      p(0.0000) =      1.778 ms/op
     p(50.0000) =      6.087 ms/op
     p(90.0000) =      7.668 ms/op
     p(95.0000) =      8.700 ms/op
     p(99.0000) =     12.239 ms/op
     p(99.9000) =     27.787 ms/op
     p(99.9900) =     32.104 ms/op
     p(99.9990) =     35.586 ms/op
     p(99.9999) =     35.652 ms/op
    p(100.0000) =     35.652 ms/op


# Run complete. Total time: 00:13:17

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.812 ± 2.572  ops/ms
ClientPb.existUser                       thrpt       3   6.275 ± 1.218  ops/ms
ClientPb.getUser                         thrpt       3   5.850 ± 2.629  ops/ms
ClientPb.listUser                        thrpt       3   5.186 ± 1.233  ops/ms
ClientPb.createUser                       avgt       3   5.525 ± 1.785   ms/op
ClientPb.existUser                        avgt       3   5.146 ± 2.955   ms/op
ClientPb.getUser                          avgt       3   5.399 ± 1.839   ms/op
ClientPb.listUser                         avgt       3   6.374 ± 2.327   ms/op
ClientPb.createUser                     sample  171838   5.588 ± 0.012   ms/op
ClientPb.createUser:createUser·p0.00    sample           2.013           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.292           ms/op
ClientPb.createUser:createUser·p0.90    sample           6.963           ms/op
ClientPb.createUser:createUser·p0.95    sample           7.799           ms/op
ClientPb.createUser:createUser·p0.99    sample          10.682           ms/op
ClientPb.createUser:createUser·p0.999   sample          26.018           ms/op
ClientPb.createUser:createUser·p0.9999  sample          34.996           ms/op
ClientPb.createUser:createUser·p1.00    sample          40.567           ms/op
ClientPb.existUser                      sample  186324   5.148 ± 0.010   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.796           ms/op
ClientPb.existUser:existUser·p0.50      sample           4.891           ms/op
ClientPb.existUser:existUser·p0.90      sample           6.324           ms/op
ClientPb.existUser:existUser·p0.95      sample           7.234           ms/op
ClientPb.existUser:existUser·p0.99      sample           9.814           ms/op
ClientPb.existUser:existUser·p0.999     sample          22.523           ms/op
ClientPb.existUser:existUser·p0.9999    sample          28.213           ms/op
ClientPb.existUser:existUser·p1.00      sample          30.966           ms/op
ClientPb.getUser                        sample  170669   5.617 ± 0.012   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.853           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.325           ms/op
ClientPb.getUser:getUser·p0.90          sample           6.816           ms/op
ClientPb.getUser:getUser·p0.95          sample           7.897           ms/op
ClientPb.getUser:getUser·p0.99          sample          10.977           ms/op
ClientPb.getUser:getUser·p0.999         sample          21.987           ms/op
ClientPb.getUser:getUser·p0.9999        sample          37.749           ms/op
ClientPb.getUser:getUser·p1.00          sample          40.108           ms/op
ClientPb.listUser                       sample  149673   6.414 ± 0.014   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.778           ms/op
ClientPb.listUser:listUser·p0.50        sample           6.087           ms/op
ClientPb.listUser:listUser·p0.90        sample           7.668           ms/op
ClientPb.listUser:listUser·p0.95        sample           8.700           ms/op
ClientPb.listUser:listUser·p0.99        sample          12.239           ms/op
ClientPb.listUser:listUser·p0.999       sample          27.787           ms/op
ClientPb.listUser:listUser·p0.9999      sample          32.104           ms/op
ClientPb.listUser:listUser·p1.00        sample          35.652           ms/op
