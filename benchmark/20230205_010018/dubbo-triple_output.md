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
# Warmup Iteration   1: 2.615 ops/ms
# Warmup Iteration   2: 6.831 ops/ms
# Warmup Iteration   3: 9.325 ops/ms
Iteration   1: 10.002 ops/ms
Iteration   2: 9.922 ops/ms
Iteration   3: 9.385 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.770 ±(99.9%) 6.124 ops/ms [Average]
  (min, avg, max) = (9.385, 9.770, 10.002), stdev = 0.336
  CI (99.9%): [3.646, 15.894] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 4.176 ops/ms
# Warmup Iteration   2: 9.356 ops/ms
# Warmup Iteration   3: 10.550 ops/ms
Iteration   1: 10.063 ops/ms
Iteration   2: 10.028 ops/ms
Iteration   3: 10.363 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.151 ±(99.9%) 3.364 ops/ms [Average]
  (min, avg, max) = (10.028, 10.151, 10.363), stdev = 0.184
  CI (99.9%): [6.787, 13.515] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.116 ops/ms
# Warmup Iteration   2: 8.381 ops/ms
# Warmup Iteration   3: 9.965 ops/ms
Iteration   1: 10.091 ops/ms
Iteration   2: 10.049 ops/ms
Iteration   3: 10.236 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  10.125 ±(99.9%) 1.795 ops/ms [Average]
  (min, avg, max) = (10.049, 10.125, 10.236), stdev = 0.098
  CI (99.9%): [8.330, 11.920] (assumes normal distribution)


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
# Warmup Iteration   1: 3.481 ops/ms
# Warmup Iteration   2: 8.141 ops/ms
# Warmup Iteration   3: 8.556 ops/ms
Iteration   1: 8.540 ops/ms
Iteration   2: 8.716 ops/ms
Iteration   3: 8.249 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.502 ±(99.9%) 4.302 ops/ms [Average]
  (min, avg, max) = (8.249, 8.502, 8.716), stdev = 0.236
  CI (99.9%): [4.200, 12.804] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 8.147 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 3.485 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.395 ±(99.9%) 0.009 ms/op
Iteration   1: 3.264 ±(99.9%) 0.005 ms/op
Iteration   2: 3.150 ±(99.9%) 0.010 ms/op
Iteration   3: 3.211 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.208 ±(99.9%) 1.034 ms/op [Average]
  (min, avg, max) = (3.150, 3.208, 3.264), stdev = 0.057
  CI (99.9%): [2.174, 4.242] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 7.241 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 3.313 ±(99.9%) 0.001 ms/op
# Warmup Iteration   3: 3.170 ±(99.9%) 0.007 ms/op
Iteration   1: 3.064 ±(99.9%) 0.005 ms/op
Iteration   2: 2.953 ±(99.9%) 0.006 ms/op
Iteration   3: 2.966 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.995 ±(99.9%) 1.107 ms/op [Average]
  (min, avg, max) = (2.953, 2.995, 3.064), stdev = 0.061
  CI (99.9%): [1.887, 4.102] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 7.756 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 3.607 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.402 ±(99.9%) 0.002 ms/op
Iteration   1: 3.370 ±(99.9%) 0.004 ms/op
Iteration   2: 3.299 ±(99.9%) 0.008 ms/op
Iteration   3: 3.112 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.260 ±(99.9%) 2.435 ms/op [Average]
  (min, avg, max) = (3.112, 3.260, 3.370), stdev = 0.133
  CI (99.9%): [0.826, 5.695] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 8.672 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 4.115 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.728 ±(99.9%) 0.007 ms/op
Iteration   1: 3.719 ±(99.9%) 0.010 ms/op
Iteration   2: 3.593 ±(99.9%) 0.011 ms/op
Iteration   3: 3.584 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.632 ±(99.9%) 1.372 ms/op [Average]
  (min, avg, max) = (3.584, 3.632, 3.719), stdev = 0.075
  CI (99.9%): [2.260, 5.003] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 7.582 ±(99.9%) 0.093 ms/op
# Warmup Iteration   2: 3.683 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.268 ±(99.9%) 0.009 ms/op
Iteration   1: 3.316 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.118 ms/op
                 createUser·p0.50:   3.215 ms/op
                 createUser·p0.90:   3.772 ms/op
                 createUser·p0.95:   4.157 ms/op
                 createUser·p0.99:   5.743 ms/op
                 createUser·p0.999:  19.057 ms/op
                 createUser·p0.9999: 25.377 ms/op
                 createUser·p1.00:   28.049 ms/op

Iteration   2: 3.226 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.071 ms/op
                 createUser·p0.50:   3.219 ms/op
                 createUser·p0.90:   3.441 ms/op
                 createUser·p0.95:   3.801 ms/op
                 createUser·p0.99:   5.251 ms/op
                 createUser·p0.999:  11.923 ms/op
                 createUser·p0.9999: 26.219 ms/op
                 createUser·p1.00:   26.968 ms/op

Iteration   3: 3.194 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   1.495 ms/op
                 createUser·p0.50:   3.076 ms/op
                 createUser·p0.90:   3.609 ms/op
                 createUser·p0.95:   3.863 ms/op
                 createUser·p0.99:   5.267 ms/op
                 createUser·p0.999:  12.962 ms/op
                 createUser·p0.9999: 19.301 ms/op
                 createUser·p1.00:   25.199 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 295593
  mean =      3.245 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 19128 
    [ 2.500,  5.000) = 270781 
    [ 5.000,  7.500) = 4888 
    [ 7.500, 10.000) = 311 
    [10.000, 12.500) = 119 
    [12.500, 15.000) = 54 
    [15.000, 17.500) = 38 
    [17.500, 20.000) = 157 
    [20.000, 22.500) = 40 
    [22.500, 25.000) = 38 
    [25.000, 27.500) = 38 

  Percentiles, ms/op:
      p(0.0000) =      1.071 ms/op
     p(50.0000) =      3.195 ms/op
     p(90.0000) =      3.629 ms/op
     p(95.0000) =      3.949 ms/op
     p(99.0000) =      5.464 ms/op
     p(99.9000) =     15.588 ms/op
     p(99.9900) =     25.344 ms/op
     p(99.9990) =     26.811 ms/op
     p(99.9999) =     28.049 ms/op
    p(100.0000) =     28.049 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 6.575 ±(99.9%) 0.073 ms/op
# Warmup Iteration   2: 3.412 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.069 ±(99.9%) 0.008 ms/op
Iteration   1: 3.008 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   1.573 ms/op
                 existUser·p0.50:   3.015 ms/op
                 existUser·p0.90:   3.125 ms/op
                 existUser·p0.95:   3.195 ms/op
                 existUser·p0.99:   5.120 ms/op
                 existUser·p0.999:  10.874 ms/op
                 existUser·p0.9999: 19.935 ms/op
                 existUser·p1.00:   20.283 ms/op

Iteration   2: 3.104 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.456 ms/op
                 existUser·p0.50:   3.105 ms/op
                 existUser·p0.90:   3.248 ms/op
                 existUser·p0.95:   3.502 ms/op
                 existUser·p0.99:   5.423 ms/op
                 existUser·p0.999:  10.698 ms/op
                 existUser·p0.9999: 21.967 ms/op
                 existUser·p1.00:   22.315 ms/op

Iteration   3: 3.046 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   1.497 ms/op
                 existUser·p0.50:   3.006 ms/op
                 existUser·p0.90:   3.240 ms/op
                 existUser·p0.95:   3.457 ms/op
                 existUser·p0.99:   5.226 ms/op
                 existUser·p0.999:  9.814 ms/op
                 existUser·p0.9999: 19.088 ms/op
                 existUser·p1.00:   19.923 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 314300
  mean =      3.052 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 28730 
    [ 2.500,  5.000) = 281317 
    [ 5.000,  7.500) = 3655 
    [ 7.500, 10.000) = 258 
    [10.000, 12.500) = 52 
    [12.500, 15.000) = 9 
    [15.000, 17.500) = 48 
    [17.500, 20.000) = 143 
    [20.000, 22.500) = 88 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.456 ms/op
     p(50.0000) =      3.052 ms/op
     p(90.0000) =      3.203 ms/op
     p(95.0000) =      3.416 ms/op
     p(99.0000) =      5.226 ms/op
     p(99.9000) =     10.437 ms/op
     p(99.9900) =     21.383 ms/op
     p(99.9990) =     22.249 ms/op
     p(99.9999) =     22.315 ms/op
    p(100.0000) =     22.315 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 7.647 ±(99.9%) 0.101 ms/op
# Warmup Iteration   2: 3.549 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.436 ±(99.9%) 0.010 ms/op
Iteration   1: 3.221 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.958 ms/op
                 getUser·p0.50:   3.092 ms/op
                 getUser·p0.90:   3.564 ms/op
                 getUser·p0.95:   4.017 ms/op
                 getUser·p0.99:   6.275 ms/op
                 getUser·p0.999:  18.569 ms/op
                 getUser·p0.9999: 20.875 ms/op
                 getUser·p1.00:   21.725 ms/op

Iteration   2: 3.134 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.313 ms/op
                 getUser·p0.50:   3.056 ms/op
                 getUser·p0.90:   3.391 ms/op
                 getUser·p0.95:   3.604 ms/op
                 getUser·p0.99:   5.407 ms/op
                 getUser·p0.999:  9.060 ms/op
                 getUser·p0.9999: 29.362 ms/op
                 getUser·p1.00:   30.015 ms/op

Iteration   3: 3.145 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   1.438 ms/op
                 getUser·p0.50:   3.076 ms/op
                 getUser·p0.90:   3.396 ms/op
                 getUser·p0.95:   3.539 ms/op
                 getUser·p0.99:   5.317 ms/op
                 getUser·p0.999:  11.653 ms/op
                 getUser·p0.9999: 21.414 ms/op
                 getUser·p1.00:   21.823 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 303022
  mean =      3.166 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10817 
    [ 2.500,  5.000) = 286533 
    [ 5.000,  7.500) = 4742 
    [ 7.500, 10.000) = 461 
    [10.000, 12.500) = 120 
    [12.500, 15.000) = 2 
    [15.000, 17.500) = 15 
    [17.500, 20.000) = 174 
    [20.000, 22.500) = 109 
    [22.500, 25.000) = 18 
    [25.000, 27.500) = 4 
    [27.500, 30.000) = 26 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.958 ms/op
     p(50.0000) =      3.072 ms/op
     p(90.0000) =      3.441 ms/op
     p(95.0000) =      3.674 ms/op
     p(99.0000) =      5.571 ms/op
     p(99.9000) =     18.185 ms/op
     p(99.9900) =     26.195 ms/op
     p(99.9990) =     29.687 ms/op
     p(99.9999) =     30.015 ms/op
    p(100.0000) =     30.015 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 8.730 ±(99.9%) 0.121 ms/op
# Warmup Iteration   2: 4.207 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.742 ±(99.9%) 0.010 ms/op
Iteration   1: 3.708 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.444 ms/op
                 listUser·p0.50:   3.584 ms/op
                 listUser·p0.90:   4.028 ms/op
                 listUser·p0.95:   4.219 ms/op
                 listUser·p0.99:   6.865 ms/op
                 listUser·p0.999:  16.234 ms/op
                 listUser·p0.9999: 25.473 ms/op
                 listUser·p1.00:   25.723 ms/op

Iteration   2: 3.784 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.454 ms/op
                 listUser·p0.50:   3.678 ms/op
                 listUser·p0.90:   3.965 ms/op
                 listUser·p0.95:   4.415 ms/op
                 listUser·p0.99:   8.086 ms/op
                 listUser·p0.999:  13.910 ms/op
                 listUser·p0.9999: 17.577 ms/op
                 listUser·p1.00:   17.924 ms/op

Iteration   3: 3.695 ±(99.9%) 0.007 ms/op
                 listUser·p0.00:   2.286 ms/op
                 listUser·p0.50:   3.699 ms/op
                 listUser·p0.90:   3.805 ms/op
                 listUser·p0.95:   4.043 ms/op
                 listUser·p0.99:   6.169 ms/op
                 listUser·p0.999:  13.402 ms/op
                 listUser·p0.9999: 17.957 ms/op
                 listUser·p1.00:   18.022 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 257281
  mean =      3.728 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 72 
    [ 2.500,  5.000) = 250637 
    [ 5.000,  7.500) = 4720 
    [ 7.500, 10.000) = 1013 
    [10.000, 12.500) = 242 
    [12.500, 15.000) = 380 
    [15.000, 17.500) = 153 
    [17.500, 20.000) = 32 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 19 
    [25.000, 27.500) = 13 

  Percentiles, ms/op:
      p(0.0000) =      1.444 ms/op
     p(50.0000) =      3.674 ms/op
     p(90.0000) =      3.936 ms/op
     p(95.0000) =      4.202 ms/op
     p(99.0000) =      6.865 ms/op
     p(99.9000) =     14.729 ms/op
     p(99.9900) =     23.757 ms/op
     p(99.9990) =     25.704 ms/op
     p(99.9999) =     25.723 ms/op
    p(100.0000) =     25.723 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.770 ± 6.124  ops/ms
ClientPb.existUser                       thrpt       3  10.151 ± 3.364  ops/ms
ClientPb.getUser                         thrpt       3  10.125 ± 1.795  ops/ms
ClientPb.listUser                        thrpt       3   8.502 ± 4.302  ops/ms
ClientPb.createUser                       avgt       3   3.208 ± 1.034   ms/op
ClientPb.existUser                        avgt       3   2.995 ± 1.107   ms/op
ClientPb.getUser                          avgt       3   3.260 ± 2.435   ms/op
ClientPb.listUser                         avgt       3   3.632 ± 1.372   ms/op
ClientPb.createUser                     sample  295593   3.245 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.071           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.195           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.629           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.949           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.464           ms/op
ClientPb.createUser:createUser·p0.999   sample          15.588           ms/op
ClientPb.createUser:createUser·p0.9999  sample          25.344           ms/op
ClientPb.createUser:createUser·p1.00    sample          28.049           ms/op
ClientPb.existUser                      sample  314300   3.052 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.456           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.052           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.203           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.416           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.226           ms/op
ClientPb.existUser:existUser·p0.999     sample          10.437           ms/op
ClientPb.existUser:existUser·p0.9999    sample          21.383           ms/op
ClientPb.existUser:existUser·p1.00      sample          22.315           ms/op
ClientPb.getUser                        sample  303022   3.166 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.958           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.072           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.441           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.674           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.571           ms/op
ClientPb.getUser:getUser·p0.999         sample          18.185           ms/op
ClientPb.getUser:getUser·p0.9999        sample          26.195           ms/op
ClientPb.getUser:getUser·p1.00          sample          30.015           ms/op
ClientPb.listUser                       sample  257281   3.728 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.444           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.674           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.936           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.202           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.865           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.729           ms/op
ClientPb.listUser:listUser·p0.9999      sample          23.757           ms/op
ClientPb.listUser:listUser·p1.00        sample          25.723           ms/op
