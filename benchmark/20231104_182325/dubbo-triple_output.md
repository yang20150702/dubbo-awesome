# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 1.664 ops/ms
# Warmup Iteration   2: 3.779 ops/ms
# Warmup Iteration   3: 6.939 ops/ms
Iteration   1: 7.403 ops/ms
Iteration   2: 7.831 ops/ms
Iteration   3: 7.833 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.689 ±(99.9%) 4.512 ops/ms [Average]
  (min, avg, max) = (7.403, 7.689, 7.833), stdev = 0.247
  CI (99.9%): [3.177, 12.201] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:14
# Fork: 1 of 1
# Warmup Iteration   1: 2.185 ops/ms
# Warmup Iteration   2: 7.148 ops/ms
# Warmup Iteration   3: 8.077 ops/ms
Iteration   1: 8.078 ops/ms
Iteration   2: 8.050 ops/ms
Iteration   3: 8.363 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.163 ±(99.9%) 3.163 ops/ms [Average]
  (min, avg, max) = (8.050, 8.163, 8.363), stdev = 0.173
  CI (99.9%): [5.000, 11.327] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:11:01
# Fork: 1 of 1
# Warmup Iteration   1: 2.285 ops/ms
# Warmup Iteration   2: 6.238 ops/ms
# Warmup Iteration   3: 7.823 ops/ms
Iteration   1: 7.959 ops/ms
Iteration   2: 7.780 ops/ms
Iteration   3: 7.726 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  7.822 ±(99.9%) 2.225 ops/ms [Average]
  (min, avg, max) = (7.726, 7.822, 7.959), stdev = 0.122
  CI (99.9%): [5.597, 10.047] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:54
# Fork: 1 of 1
# Warmup Iteration   1: 2.075 ops/ms
# Warmup Iteration   2: 5.328 ops/ms
# Warmup Iteration   3: 6.338 ops/ms
Iteration   1: 6.603 ops/ms
Iteration   2: 6.632 ops/ms
Iteration   3: 6.556 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.597 ±(99.9%) 0.700 ops/ms [Average]
  (min, avg, max) = (6.556, 6.597, 6.632), stdev = 0.038
  CI (99.9%): [5.897, 7.297] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:49
# Fork: 1 of 1
# Warmup Iteration   1: 14.780 ±(99.9%) 0.072 ms/op
# Warmup Iteration   2: 4.731 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.366 ±(99.9%) 0.007 ms/op
Iteration   1: 4.171 ±(99.9%) 0.004 ms/op
Iteration   2: 4.009 ±(99.9%) 0.004 ms/op
Iteration   3: 4.066 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  4.082 ±(99.9%) 1.499 ms/op [Average]
  (min, avg, max) = (4.009, 4.082, 4.171), stdev = 0.082
  CI (99.9%): [2.582, 5.581] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:43
# Fork: 1 of 1
# Warmup Iteration   1: 10.544 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 4.357 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.197 ±(99.9%) 0.007 ms/op
Iteration   1: 4.102 ±(99.9%) 0.004 ms/op
Iteration   2: 3.834 ±(99.9%) 0.003 ms/op
Iteration   3: 4.039 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.991 ±(99.9%) 2.557 ms/op [Average]
  (min, avg, max) = (3.834, 3.991, 4.102), stdev = 0.140
  CI (99.9%): [1.434, 6.549] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:37
# Fork: 1 of 1
# Warmup Iteration   1: 13.391 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 4.608 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.166 ±(99.9%) 0.006 ms/op
Iteration   1: 4.017 ±(99.9%) 0.005 ms/op
Iteration   2: 4.071 ±(99.9%) 0.004 ms/op
Iteration   3: 3.991 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  4.026 ±(99.9%) 0.748 ms/op [Average]
  (min, avg, max) = (3.991, 4.026, 4.071), stdev = 0.041
  CI (99.9%): [3.278, 4.774] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:31
# Fork: 1 of 1
# Warmup Iteration   1: 13.714 ±(99.9%) 0.067 ms/op
# Warmup Iteration   2: 6.318 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 5.105 ±(99.9%) 0.008 ms/op
Iteration   1: 4.820 ±(99.9%) 0.009 ms/op
Iteration   2: 4.801 ±(99.9%) 0.009 ms/op
Iteration   3: 4.759 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.793 ±(99.9%) 0.567 ms/op [Average]
  (min, avg, max) = (4.759, 4.793, 4.820), stdev = 0.031
  CI (99.9%): [4.227, 5.360] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:24
# Fork: 1 of 1
# Warmup Iteration   1: 13.020 ±(99.9%) 0.205 ms/op
# Warmup Iteration   2: 4.950 ±(99.9%) 0.026 ms/op
# Warmup Iteration   3: 4.421 ±(99.9%) 0.018 ms/op
Iteration   1: 4.074 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.659 ms/op
                 createUser·p0.50:   3.838 ms/op
                 createUser·p0.90:   4.768 ms/op
                 createUser·p0.95:   5.358 ms/op
                 createUser·p0.99:   7.914 ms/op
                 createUser·p0.999:  24.167 ms/op
                 createUser·p0.9999: 27.006 ms/op
                 createUser·p1.00:   28.672 ms/op

Iteration   2: 3.977 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.630 ms/op
                 createUser·p0.50:   3.887 ms/op
                 createUser·p0.90:   4.506 ms/op
                 createUser·p0.95:   4.841 ms/op
                 createUser·p0.99:   6.201 ms/op
                 createUser·p0.999:  26.195 ms/op
                 createUser·p0.9999: 28.371 ms/op
                 createUser·p1.00:   28.967 ms/op

Iteration   3: 4.092 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.436 ms/op
                 createUser·p0.50:   3.908 ms/op
                 createUser·p0.90:   4.825 ms/op
                 createUser·p0.95:   5.169 ms/op
                 createUser·p0.99:   6.431 ms/op
                 createUser·p0.999:  12.699 ms/op
                 createUser·p0.9999: 31.324 ms/op
                 createUser·p1.00:   32.145 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 237223
  mean =      4.047 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 492 
    [ 2.500,  5.000) = 222650 
    [ 5.000,  7.500) = 12293 
    [ 7.500, 10.000) = 1109 
    [10.000, 12.500) = 302 
    [12.500, 15.000) = 78 
    [15.000, 17.500) = 9 
    [17.500, 20.000) = 34 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 141 
    [27.500, 30.000) = 49 
    [30.000, 32.500) = 33 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.436 ms/op
     p(50.0000) =      3.879 ms/op
     p(90.0000) =      4.702 ms/op
     p(95.0000) =      5.095 ms/op
     p(99.0000) =      6.914 ms/op
     p(99.9000) =     24.310 ms/op
     p(99.9900) =     30.385 ms/op
     p(99.9990) =     32.088 ms/op
     p(99.9999) =     32.145 ms/op
    p(100.0000) =     32.145 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 11.107 ±(99.9%) 0.145 ms/op
# Warmup Iteration   2: 4.469 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.113 ±(99.9%) 0.014 ms/op
Iteration   1: 4.130 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.470 ms/op
                 existUser·p0.50:   3.994 ms/op
                 existUser·p0.90:   4.858 ms/op
                 existUser·p0.95:   5.226 ms/op
                 existUser·p0.99:   6.767 ms/op
                 existUser·p0.999:  24.609 ms/op
                 existUser·p0.9999: 26.583 ms/op
                 existUser·p1.00:   27.066 ms/op

Iteration   2: 4.002 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.849 ms/op
                 existUser·p0.50:   3.842 ms/op
                 existUser·p0.90:   4.620 ms/op
                 existUser·p0.95:   5.095 ms/op
                 existUser·p0.99:   7.848 ms/op
                 existUser·p0.999:  14.077 ms/op
                 existUser·p0.9999: 26.379 ms/op
                 existUser·p1.00:   27.132 ms/op

Iteration   3: 3.907 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.870 ms/op
                 existUser·p0.50:   3.740 ms/op
                 existUser·p0.90:   4.317 ms/op
                 existUser·p0.95:   4.702 ms/op
                 existUser·p0.99:   7.266 ms/op
                 existUser·p0.999:  13.795 ms/op
                 existUser·p0.9999: 31.681 ms/op
                 existUser·p1.00:   32.276 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 239183
  mean =      4.011 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 228 
    [ 2.500,  5.000) = 225448 
    [ 5.000,  7.500) = 11347 
    [ 7.500, 10.000) = 1273 
    [10.000, 12.500) = 470 
    [12.500, 15.000) = 168 
    [15.000, 17.500) = 16 
    [17.500, 20.000) = 9 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 67 
    [25.000, 27.500) = 93 
    [27.500, 30.000) = 35 
    [30.000, 32.500) = 29 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.470 ms/op
     p(50.0000) =      3.834 ms/op
     p(90.0000) =      4.645 ms/op
     p(95.0000) =      5.087 ms/op
     p(99.0000) =      7.283 ms/op
     p(99.9000) =     15.889 ms/op
     p(99.9900) =     30.381 ms/op
     p(99.9990) =     32.100 ms/op
     p(99.9999) =     32.276 ms/op
    p(100.0000) =     32.276 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 12.093 ±(99.9%) 0.168 ms/op
# Warmup Iteration   2: 4.454 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.414 ±(99.9%) 0.017 ms/op
Iteration   1: 4.075 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.319 ms/op
                 getUser·p0.50:   3.916 ms/op
                 getUser·p0.90:   4.456 ms/op
                 getUser·p0.95:   4.751 ms/op
                 getUser·p0.99:   7.610 ms/op
                 getUser·p0.999:  24.909 ms/op
                 getUser·p0.9999: 27.591 ms/op
                 getUser·p1.00:   28.541 ms/op

Iteration   2: 4.124 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.722 ms/op
                 getUser·p0.50:   3.994 ms/op
                 getUser·p0.90:   4.596 ms/op
                 getUser·p0.95:   4.866 ms/op
                 getUser·p0.99:   7.016 ms/op
                 getUser·p0.999:  16.408 ms/op
                 getUser·p0.9999: 27.271 ms/op
                 getUser·p1.00:   28.639 ms/op

Iteration   3: 4.216 ±(99.9%) 0.016 ms/op
                 getUser·p0.00:   1.843 ms/op
                 getUser·p0.50:   3.916 ms/op
                 getUser·p0.90:   4.973 ms/op
                 getUser·p0.95:   5.972 ms/op
                 getUser·p0.99:   8.536 ms/op
                 getUser·p0.999:  27.594 ms/op
                 getUser·p0.9999: 34.564 ms/op
                 getUser·p1.00:   35.783 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 231873
  mean =      4.137 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 50 
    [ 2.500,  5.000) = 218252 
    [ 5.000,  7.500) = 10696 
    [ 7.500, 10.000) = 1936 
    [10.000, 12.500) = 429 
    [12.500, 15.000) = 145 
    [15.000, 17.500) = 97 
    [17.500, 20.000) = 7 
    [20.000, 22.500) = 5 
    [22.500, 25.000) = 29 
    [25.000, 27.500) = 136 
    [27.500, 30.000) = 56 
    [30.000, 32.500) = 4 
    [32.500, 35.000) = 28 
    [35.000, 37.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      1.319 ms/op
     p(50.0000) =      3.940 ms/op
     p(90.0000) =      4.604 ms/op
     p(95.0000) =      5.243 ms/op
     p(99.0000) =      7.873 ms/op
     p(99.9000) =     24.875 ms/op
     p(99.9900) =     32.702 ms/op
     p(99.9990) =     35.062 ms/op
     p(99.9999) =     35.783 ms/op
    p(100.0000) =     35.783 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 15.111 ±(99.9%) 0.231 ms/op
# Warmup Iteration   2: 5.894 ±(99.9%) 0.031 ms/op
# Warmup Iteration   3: 5.193 ±(99.9%) 0.018 ms/op
Iteration   1: 4.960 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   2.363 ms/op
                 listUser·p0.50:   4.727 ms/op
                 listUser·p0.90:   5.628 ms/op
                 listUser·p0.95:   6.021 ms/op
                 listUser·p0.99:   8.798 ms/op
                 listUser·p0.999:  25.478 ms/op
                 listUser·p0.9999: 29.164 ms/op
                 listUser·p1.00:   29.557 ms/op

Iteration   2: 4.750 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   2.220 ms/op
                 listUser·p0.50:   4.563 ms/op
                 listUser·p0.90:   5.186 ms/op
                 listUser·p0.95:   5.718 ms/op
                 listUser·p0.99:   8.700 ms/op
                 listUser·p0.999:  19.603 ms/op
                 listUser·p0.9999: 24.298 ms/op
                 listUser·p1.00:   28.180 ms/op

Iteration   3: 4.833 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.495 ms/op
                 listUser·p0.50:   4.686 ms/op
                 listUser·p0.90:   5.317 ms/op
                 listUser·p0.95:   5.693 ms/op
                 listUser·p0.99:   8.315 ms/op
                 listUser·p0.999:  17.292 ms/op
                 listUser·p0.9999: 19.588 ms/op
                 listUser·p1.00:   20.054 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 197974
  mean =      4.846 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13 
    [ 2.500,  5.000) = 149493 
    [ 5.000,  7.500) = 43701 
    [ 7.500, 10.000) = 3744 
    [10.000, 12.500) = 318 
    [12.500, 15.000) = 161 
    [15.000, 17.500) = 216 
    [17.500, 20.000) = 138 
    [20.000, 22.500) = 31 
    [22.500, 25.000) = 81 
    [25.000, 27.500) = 60 

  Percentiles, ms/op:
      p(0.0000) =      1.495 ms/op
     p(50.0000) =      4.628 ms/op
     p(90.0000) =      5.431 ms/op
     p(95.0000) =      5.874 ms/op
     p(99.0000) =      8.651 ms/op
     p(99.9000) =     19.630 ms/op
     p(99.9900) =     27.388 ms/op
     p(99.9990) =     29.396 ms/op
     p(99.9999) =     29.557 ms/op
    p(100.0000) =     29.557 ms/op


# Run complete. Total time: 00:13:17

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   7.689 ± 4.512  ops/ms
ClientPb.existUser                       thrpt       3   8.163 ± 3.163  ops/ms
ClientPb.getUser                         thrpt       3   7.822 ± 2.225  ops/ms
ClientPb.listUser                        thrpt       3   6.597 ± 0.700  ops/ms
ClientPb.createUser                       avgt       3   4.082 ± 1.499   ms/op
ClientPb.existUser                        avgt       3   3.991 ± 2.557   ms/op
ClientPb.getUser                          avgt       3   4.026 ± 0.748   ms/op
ClientPb.listUser                         avgt       3   4.793 ± 0.567   ms/op
ClientPb.createUser                     sample  237223   4.047 ± 0.007   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.436           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.879           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.702           ms/op
ClientPb.createUser:createUser·p0.95    sample           5.095           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.914           ms/op
ClientPb.createUser:createUser·p0.999   sample          24.310           ms/op
ClientPb.createUser:createUser·p0.9999  sample          30.385           ms/op
ClientPb.createUser:createUser·p1.00    sample          32.145           ms/op
ClientPb.existUser                      sample  239183   4.011 ± 0.007   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.470           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.834           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.645           ms/op
ClientPb.existUser:existUser·p0.95      sample           5.087           ms/op
ClientPb.existUser:existUser·p0.99      sample           7.283           ms/op
ClientPb.existUser:existUser·p0.999     sample          15.889           ms/op
ClientPb.existUser:existUser·p0.9999    sample          30.381           ms/op
ClientPb.existUser:existUser·p1.00      sample          32.276           ms/op
ClientPb.getUser                        sample  231873   4.137 ± 0.008   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.319           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.940           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.604           ms/op
ClientPb.getUser:getUser·p0.95          sample           5.243           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.873           ms/op
ClientPb.getUser:getUser·p0.999         sample          24.875           ms/op
ClientPb.getUser:getUser·p0.9999        sample          32.702           ms/op
ClientPb.getUser:getUser·p1.00          sample          35.783           ms/op
ClientPb.listUser                       sample  197974   4.846 ± 0.008   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.495           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.628           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.431           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.874           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.651           ms/op
ClientPb.listUser:listUser·p0.999       sample          19.630           ms/op
ClientPb.listUser:listUser·p0.9999      sample          27.388           ms/op
ClientPb.listUser:listUser·p1.00        sample          29.557           ms/op
