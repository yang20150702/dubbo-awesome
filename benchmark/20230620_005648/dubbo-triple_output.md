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
# Warmup Iteration   1: 2.023 ops/ms
# Warmup Iteration   2: 4.914 ops/ms
# Warmup Iteration   3: 8.293 ops/ms
Iteration   1: 9.090 ops/ms
Iteration   2: 9.396 ops/ms
Iteration   3: 9.474 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.320 ±(99.9%) 3.699 ops/ms [Average]
  (min, avg, max) = (9.090, 9.320, 9.474), stdev = 0.203
  CI (99.9%): [5.622, 13.019] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 3.253 ops/ms
# Warmup Iteration   2: 8.888 ops/ms
# Warmup Iteration   3: 9.661 ops/ms
Iteration   1: 9.690 ops/ms
Iteration   2: 9.807 ops/ms
Iteration   3: 9.989 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.829 ±(99.9%) 2.756 ops/ms [Average]
  (min, avg, max) = (9.690, 9.829, 9.989), stdev = 0.151
  CI (99.9%): [7.073, 12.585] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 2.628 ops/ms
# Warmup Iteration   2: 7.639 ops/ms
# Warmup Iteration   3: 8.908 ops/ms
Iteration   1: 9.175 ops/ms
Iteration   2: 9.692 ops/ms
Iteration   3: 9.536 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.468 ±(99.9%) 4.838 ops/ms [Average]
  (min, avg, max) = (9.175, 9.468, 9.692), stdev = 0.265
  CI (99.9%): [4.630, 14.306] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:49
# Fork: 1 of 1
# Warmup Iteration   1: 3.103 ops/ms
# Warmup Iteration   2: 7.194 ops/ms
# Warmup Iteration   3: 7.805 ops/ms
Iteration   1: 7.931 ops/ms
Iteration   2: 8.015 ops/ms
Iteration   3: 8.191 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.046 ±(99.9%) 2.425 ops/ms [Average]
  (min, avg, max) = (7.931, 8.046, 8.191), stdev = 0.133
  CI (99.9%): [5.621, 10.470] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:42
# Fork: 1 of 1
# Warmup Iteration   1: 10.142 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.647 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.530 ±(99.9%) 0.009 ms/op
Iteration   1: 3.590 ±(99.9%) 0.009 ms/op
Iteration   2: 3.372 ±(99.9%) 0.005 ms/op
Iteration   3: 3.381 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.447 ±(99.9%) 2.254 ms/op [Average]
  (min, avg, max) = (3.372, 3.447, 3.590), stdev = 0.124
  CI (99.9%): [1.194, 5.701] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:38
# Fork: 1 of 1
# Warmup Iteration   1: 9.292 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 3.625 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.488 ±(99.9%) 0.009 ms/op
Iteration   1: 3.274 ±(99.9%) 0.011 ms/op
Iteration   2: 3.326 ±(99.9%) 0.003 ms/op
Iteration   3: 3.319 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.306 ±(99.9%) 0.523 ms/op [Average]
  (min, avg, max) = (3.274, 3.306, 3.326), stdev = 0.029
  CI (99.9%): [2.783, 3.830] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 8.776 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.632 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.576 ±(99.9%) 0.004 ms/op
Iteration   1: 3.452 ±(99.9%) 0.004 ms/op
Iteration   2: 3.417 ±(99.9%) 0.008 ms/op
Iteration   3: 3.491 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.453 ±(99.9%) 0.676 ms/op [Average]
  (min, avg, max) = (3.417, 3.453, 3.491), stdev = 0.037
  CI (99.9%): [2.777, 4.129] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 11.175 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 4.338 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.964 ±(99.9%) 0.015 ms/op
Iteration   1: 3.934 ±(99.9%) 0.014 ms/op
Iteration   2: 4.047 ±(99.9%) 0.007 ms/op
Iteration   3: 3.930 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.970 ±(99.9%) 1.219 ms/op [Average]
  (min, avg, max) = (3.930, 3.970, 4.047), stdev = 0.067
  CI (99.9%): [2.751, 5.190] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 9.678 ±(99.9%) 0.117 ms/op
# Warmup Iteration   2: 4.107 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 3.447 ±(99.9%) 0.011 ms/op
Iteration   1: 3.371 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.350 ms/op
                 createUser·p0.50:   3.260 ms/op
                 createUser·p0.90:   3.760 ms/op
                 createUser·p0.95:   4.063 ms/op
                 createUser·p0.99:   6.504 ms/op
                 createUser·p0.999:  20.827 ms/op
                 createUser·p0.9999: 31.381 ms/op
                 createUser·p1.00:   32.408 ms/op

Iteration   2: 3.421 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.696 ms/op
                 createUser·p0.50:   3.285 ms/op
                 createUser·p0.90:   3.912 ms/op
                 createUser·p0.95:   4.190 ms/op
                 createUser·p0.99:   5.707 ms/op
                 createUser·p0.999:  20.892 ms/op
                 createUser·p0.9999: 24.958 ms/op
                 createUser·p1.00:   26.083 ms/op

Iteration   3: 3.457 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.413 ms/op
                 createUser·p0.50:   3.318 ms/op
                 createUser·p0.90:   3.903 ms/op
                 createUser·p0.95:   4.194 ms/op
                 createUser·p0.99:   6.390 ms/op
                 createUser·p0.999:  21.154 ms/op
                 createUser·p0.9999: 27.813 ms/op
                 createUser·p1.00:   28.508 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 280670
  mean =      3.416 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6718 
    [ 2.500,  5.000) = 267540 
    [ 5.000,  7.500) = 5252 
    [ 7.500, 10.000) = 770 
    [10.000, 12.500) = 84 
    [12.500, 15.000) = 16 
    [15.000, 17.500) = 2 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 87 
    [22.500, 25.000) = 94 
    [25.000, 27.500) = 32 
    [27.500, 30.000) = 55 
    [30.000, 32.500) = 20 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.350 ms/op
     p(50.0000) =      3.285 ms/op
     p(90.0000) =      3.863 ms/op
     p(95.0000) =      4.166 ms/op
     p(99.0000) =      6.128 ms/op
     p(99.9000) =     20.928 ms/op
     p(99.9900) =     29.849 ms/op
     p(99.9990) =     32.328 ms/op
     p(99.9999) =     32.408 ms/op
    p(100.0000) =     32.408 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 10.238 ±(99.9%) 0.115 ms/op
# Warmup Iteration   2: 3.806 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.335 ±(99.9%) 0.009 ms/op
Iteration   1: 3.376 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.470 ms/op
                 existUser·p0.50:   3.224 ms/op
                 existUser·p0.90:   3.817 ms/op
                 existUser·p0.95:   4.588 ms/op
                 existUser·p0.99:   6.767 ms/op
                 existUser·p0.999:  18.742 ms/op
                 existUser·p0.9999: 23.582 ms/op
                 existUser·p1.00:   25.887 ms/op

Iteration   2: 3.354 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.147 ms/op
                 existUser·p0.50:   3.240 ms/op
                 existUser·p0.90:   3.793 ms/op
                 existUser·p0.95:   4.235 ms/op
                 existUser·p0.99:   6.062 ms/op
                 existUser·p0.999:  20.951 ms/op
                 existUser·p0.9999: 24.231 ms/op
                 existUser·p1.00:   24.969 ms/op

Iteration   3: 3.253 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.303 ms/op
                 existUser·p0.50:   3.191 ms/op
                 existUser·p0.90:   3.559 ms/op
                 existUser·p0.95:   3.797 ms/op
                 existUser·p0.99:   5.538 ms/op
                 existUser·p0.999:  11.333 ms/op
                 existUser·p0.9999: 32.271 ms/op
                 existUser·p1.00:   32.932 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 288457
  mean =      3.327 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11642 
    [ 2.500,  5.000) = 269520 
    [ 5.000,  7.500) = 5946 
    [ 7.500, 10.000) = 829 
    [10.000, 12.500) = 246 
    [12.500, 15.000) = 18 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 18 
    [20.000, 22.500) = 90 
    [22.500, 25.000) = 95 
    [25.000, 27.500) = 21 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 26 
    [32.500, 35.000) = 6 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.147 ms/op
     p(50.0000) =      3.211 ms/op
     p(90.0000) =      3.715 ms/op
     p(95.0000) =      4.157 ms/op
     p(99.0000) =      6.013 ms/op
     p(99.9000) =     12.412 ms/op
     p(99.9900) =     30.663 ms/op
     p(99.9990) =     32.706 ms/op
     p(99.9999) =     32.932 ms/op
    p(100.0000) =     32.932 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 8.933 ±(99.9%) 0.117 ms/op
# Warmup Iteration   2: 3.745 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.479 ±(99.9%) 0.010 ms/op
Iteration   1: 3.399 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.137 ms/op
                 getUser·p0.50:   3.244 ms/op
                 getUser·p0.90:   3.703 ms/op
                 getUser·p0.95:   3.965 ms/op
                 getUser·p0.99:   6.289 ms/op
                 getUser·p0.999:  21.190 ms/op
                 getUser·p0.9999: 27.806 ms/op
                 getUser·p1.00:   28.967 ms/op

Iteration   2: 3.418 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.198 ms/op
                 getUser·p0.50:   3.301 ms/op
                 getUser·p0.90:   3.850 ms/op
                 getUser·p0.95:   4.088 ms/op
                 getUser·p0.99:   5.497 ms/op
                 getUser·p0.999:  22.364 ms/op
                 getUser·p0.9999: 28.528 ms/op
                 getUser·p1.00:   29.098 ms/op

Iteration   3: 3.386 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.739 ms/op
                 getUser·p0.50:   3.265 ms/op
                 getUser·p0.90:   3.695 ms/op
                 getUser·p0.95:   3.924 ms/op
                 getUser·p0.99:   5.865 ms/op
                 getUser·p0.999:  17.813 ms/op
                 getUser·p0.9999: 27.090 ms/op
                 getUser·p1.00:   27.820 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 282229
  mean =      3.401 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3110 
    [ 2.500,  5.000) = 272456 
    [ 5.000,  7.500) = 5551 
    [ 7.500, 10.000) = 661 
    [10.000, 12.500) = 109 
    [12.500, 15.000) = 36 
    [15.000, 17.500) = 18 
    [17.500, 20.000) = 32 
    [20.000, 22.500) = 46 
    [22.500, 25.000) = 114 
    [25.000, 27.500) = 45 

  Percentiles, ms/op:
      p(0.0000) =      1.137 ms/op
     p(50.0000) =      3.269 ms/op
     p(90.0000) =      3.756 ms/op
     p(95.0000) =      4.014 ms/op
     p(99.0000) =      5.931 ms/op
     p(99.9000) =     18.126 ms/op
     p(99.9900) =     28.002 ms/op
     p(99.9990) =     29.011 ms/op
     p(99.9999) =     29.098 ms/op
    p(100.0000) =     29.098 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 9.956 ±(99.9%) 0.150 ms/op
# Warmup Iteration   2: 4.193 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.167 ±(99.9%) 0.014 ms/op
Iteration   1: 4.011 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   2.179 ms/op
                 listUser·p0.50:   3.793 ms/op
                 listUser·p0.90:   4.383 ms/op
                 listUser·p0.95:   4.891 ms/op
                 listUser·p0.99:   7.881 ms/op
                 listUser·p0.999:  19.333 ms/op
                 listUser·p0.9999: 36.372 ms/op
                 listUser·p1.00:   37.421 ms/op

Iteration   2: 3.825 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.327 ms/op
                 listUser·p0.50:   3.813 ms/op
                 listUser·p0.90:   3.924 ms/op
                 listUser·p0.95:   4.309 ms/op
                 listUser·p0.99:   6.562 ms/op
                 listUser·p0.999:  15.653 ms/op
                 listUser·p0.9999: 18.448 ms/op
                 listUser·p1.00:   18.481 ms/op

Iteration   3: 4.123 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.404 ms/op
                 listUser·p0.50:   3.879 ms/op
                 listUser·p0.90:   4.858 ms/op
                 listUser·p0.95:   5.235 ms/op
                 listUser·p0.99:   7.309 ms/op
                 listUser·p0.999:  14.554 ms/op
                 listUser·p0.9999: 17.178 ms/op
                 listUser·p1.00:   17.596 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 240912
  mean =      3.983 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 40 
    [ 2.500,  5.000) = 229860 
    [ 5.000,  7.500) = 8900 
    [ 7.500, 10.000) = 1407 
    [10.000, 12.500) = 211 
    [12.500, 15.000) = 216 
    [15.000, 17.500) = 164 
    [17.500, 20.000) = 56 
    [20.000, 22.500) = 11 
    [22.500, 25.000) = 15 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 12 
    [35.000, 37.500) = 20 

  Percentiles, ms/op:
      p(0.0000) =      2.179 ms/op
     p(50.0000) =      3.830 ms/op
     p(90.0000) =      4.530 ms/op
     p(95.0000) =      4.932 ms/op
     p(99.0000) =      7.250 ms/op
     p(99.9000) =     15.338 ms/op
     p(99.9900) =     34.603 ms/op
     p(99.9990) =     37.210 ms/op
     p(99.9999) =     37.421 ms/op
    p(100.0000) =     37.421 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.320 ± 3.699  ops/ms
ClientPb.existUser                       thrpt       3   9.829 ± 2.756  ops/ms
ClientPb.getUser                         thrpt       3   9.468 ± 4.838  ops/ms
ClientPb.listUser                        thrpt       3   8.046 ± 2.425  ops/ms
ClientPb.createUser                       avgt       3   3.447 ± 2.254   ms/op
ClientPb.existUser                        avgt       3   3.306 ± 0.523   ms/op
ClientPb.getUser                          avgt       3   3.453 ± 0.676   ms/op
ClientPb.listUser                         avgt       3   3.970 ± 1.219   ms/op
ClientPb.createUser                     sample  280670   3.416 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.350           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.285           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.863           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.166           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.128           ms/op
ClientPb.createUser:createUser·p0.999   sample          20.928           ms/op
ClientPb.createUser:createUser·p0.9999  sample          29.849           ms/op
ClientPb.createUser:createUser·p1.00    sample          32.408           ms/op
ClientPb.existUser                      sample  288457   3.327 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.147           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.211           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.715           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.157           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.013           ms/op
ClientPb.existUser:existUser·p0.999     sample          12.412           ms/op
ClientPb.existUser:existUser·p0.9999    sample          30.663           ms/op
ClientPb.existUser:existUser·p1.00      sample          32.932           ms/op
ClientPb.getUser                        sample  282229   3.401 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.137           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.269           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.756           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.014           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.931           ms/op
ClientPb.getUser:getUser·p0.999         sample          18.126           ms/op
ClientPb.getUser:getUser·p0.9999        sample          28.002           ms/op
ClientPb.getUser:getUser·p1.00          sample          29.098           ms/op
ClientPb.listUser                       sample  240912   3.983 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.179           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.830           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.530           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.932           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.250           ms/op
ClientPb.listUser:listUser·p0.999       sample          15.338           ms/op
ClientPb.listUser:listUser·p0.9999      sample          34.603           ms/op
ClientPb.listUser:listUser·p1.00        sample          37.421           ms/op
