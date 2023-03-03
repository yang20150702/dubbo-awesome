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
# Warmup Iteration   1: 2.662 ops/ms
# Warmup Iteration   2: 6.489 ops/ms
# Warmup Iteration   3: 9.343 ops/ms
Iteration   1: 9.674 ops/ms
Iteration   2: 9.850 ops/ms
Iteration   3: 9.811 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.778 ±(99.9%) 1.687 ops/ms [Average]
  (min, avg, max) = (9.674, 9.778, 9.850), stdev = 0.092
  CI (99.9%): [8.091, 11.465] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:07
# Fork: 1 of 1
# Warmup Iteration   1: 3.679 ops/ms
# Warmup Iteration   2: 9.004 ops/ms
# Warmup Iteration   3: 10.009 ops/ms
Iteration   1: 10.915 ops/ms
Iteration   2: 10.372 ops/ms
Iteration   3: 10.073 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.453 ±(99.9%) 7.785 ops/ms [Average]
  (min, avg, max) = (10.073, 10.453, 10.915), stdev = 0.427
  CI (99.9%): [2.669, 18.238] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:55
# Fork: 1 of 1
# Warmup Iteration   1: 4.110 ops/ms
# Warmup Iteration   2: 8.845 ops/ms
# Warmup Iteration   3: 9.287 ops/ms
Iteration   1: 10.413 ops/ms
Iteration   2: 10.440 ops/ms
Iteration   3: 9.674 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  10.176 ±(99.9%) 7.928 ops/ms [Average]
  (min, avg, max) = (9.674, 10.176, 10.440), stdev = 0.435
  CI (99.9%): [2.247, 18.104] (assumes normal distribution)


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
# Warmup Iteration   1: 3.674 ops/ms
# Warmup Iteration   2: 7.823 ops/ms
# Warmup Iteration   3: 8.612 ops/ms
Iteration   1: 8.692 ops/ms
Iteration   2: 8.570 ops/ms
Iteration   3: 8.631 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.631 ±(99.9%) 1.112 ops/ms [Average]
  (min, avg, max) = (8.570, 8.631, 8.692), stdev = 0.061
  CI (99.9%): [7.519, 9.743] (assumes normal distribution)


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
# Warmup Iteration   1: 9.003 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 3.477 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.235 ±(99.9%) 0.009 ms/op
Iteration   1: 3.072 ±(99.9%) 0.006 ms/op
Iteration   2: 3.091 ±(99.9%) 0.002 ms/op
Iteration   3: 3.052 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.072 ±(99.9%) 0.362 ms/op [Average]
  (min, avg, max) = (3.052, 3.072, 3.091), stdev = 0.020
  CI (99.9%): [2.709, 3.434] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 7.133 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 3.230 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.053 ±(99.9%) 0.002 ms/op
Iteration   1: 3.168 ±(99.9%) 0.006 ms/op
Iteration   2: 2.988 ±(99.9%) 0.006 ms/op
Iteration   3: 2.935 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.031 ±(99.9%) 2.227 ms/op [Average]
  (min, avg, max) = (2.935, 3.031, 3.168), stdev = 0.122
  CI (99.9%): [0.804, 5.258] (assumes normal distribution)


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
# Warmup Iteration   1: 9.469 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.524 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.317 ±(99.9%) 0.003 ms/op
Iteration   1: 3.173 ±(99.9%) 0.004 ms/op
Iteration   2: 3.106 ±(99.9%) 0.004 ms/op
Iteration   3: 3.208 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.163 ±(99.9%) 0.942 ms/op [Average]
  (min, avg, max) = (3.106, 3.163, 3.208), stdev = 0.052
  CI (99.9%): [2.221, 4.104] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 10.390 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 4.140 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.798 ±(99.9%) 0.008 ms/op
Iteration   1: 3.627 ±(99.9%) 0.008 ms/op
Iteration   2: 3.666 ±(99.9%) 0.004 ms/op
Iteration   3: 3.750 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.681 ±(99.9%) 1.149 ms/op [Average]
  (min, avg, max) = (3.627, 3.681, 3.750), stdev = 0.063
  CI (99.9%): [2.532, 4.830] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 7.481 ±(99.9%) 0.089 ms/op
# Warmup Iteration   2: 3.762 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.403 ±(99.9%) 0.009 ms/op
Iteration   1: 3.326 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.487 ms/op
                 createUser·p0.50:   3.244 ms/op
                 createUser·p0.90:   3.936 ms/op
                 createUser·p0.95:   4.538 ms/op
                 createUser·p0.99:   5.480 ms/op
                 createUser·p0.999:  15.385 ms/op
                 createUser·p0.9999: 23.943 ms/op
                 createUser·p1.00:   24.412 ms/op

Iteration   2: 3.218 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.065 ms/op
                 createUser·p0.50:   3.146 ms/op
                 createUser·p0.90:   3.658 ms/op
                 createUser·p0.95:   3.981 ms/op
                 createUser·p0.99:   5.300 ms/op
                 createUser·p0.999:  9.760 ms/op
                 createUser·p0.9999: 28.742 ms/op
                 createUser·p1.00:   32.178 ms/op

Iteration   3: 3.210 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.920 ms/op
                 createUser·p0.50:   3.080 ms/op
                 createUser·p0.90:   3.596 ms/op
                 createUser·p0.95:   4.051 ms/op
                 createUser·p0.99:   6.241 ms/op
                 createUser·p0.999:  15.753 ms/op
                 createUser·p0.9999: 20.514 ms/op
                 createUser·p1.00:   21.037 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 295234
  mean =      3.251 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 19864 
    [ 2.500,  5.000) = 268818 
    [ 5.000,  7.500) = 5625 
    [ 7.500, 10.000) = 565 
    [10.000, 12.500) = 20 
    [12.500, 15.000) = 34 
    [15.000, 17.500) = 47 
    [17.500, 20.000) = 107 
    [20.000, 22.500) = 96 
    [22.500, 25.000) = 26 
    [25.000, 27.500) = 7 
    [27.500, 30.000) = 24 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.920 ms/op
     p(50.0000) =      3.166 ms/op
     p(90.0000) =      3.707 ms/op
     p(95.0000) =      4.350 ms/op
     p(99.0000) =      5.628 ms/op
     p(99.9000) =     15.577 ms/op
     p(99.9900) =     27.196 ms/op
     p(99.9990) =     29.288 ms/op
     p(99.9999) =     32.178 ms/op
    p(100.0000) =     32.178 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 6.710 ±(99.9%) 0.079 ms/op
# Warmup Iteration   2: 3.201 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.021 ±(99.9%) 0.006 ms/op
Iteration   1: 3.076 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.143 ms/op
                 existUser·p0.50:   3.101 ms/op
                 existUser·p0.90:   3.211 ms/op
                 existUser·p0.95:   3.457 ms/op
                 existUser·p0.99:   5.128 ms/op
                 existUser·p0.999:  9.961 ms/op
                 existUser·p0.9999: 20.256 ms/op
                 existUser·p1.00:   21.037 ms/op

Iteration   2: 3.028 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.727 ms/op
                 existUser·p0.50:   2.957 ms/op
                 existUser·p0.90:   3.178 ms/op
                 existUser·p0.95:   3.346 ms/op
                 existUser·p0.99:   5.243 ms/op
                 existUser·p0.999:  15.723 ms/op
                 existUser·p0.9999: 26.523 ms/op
                 existUser·p1.00:   27.001 ms/op

Iteration   3: 3.076 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.483 ms/op
                 existUser·p0.50:   2.961 ms/op
                 existUser·p0.90:   3.404 ms/op
                 existUser·p0.95:   3.617 ms/op
                 existUser·p0.99:   5.120 ms/op
                 existUser·p0.999:  14.123 ms/op
                 existUser·p0.9999: 23.182 ms/op
                 existUser·p1.00:   24.084 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 313576
  mean =      3.060 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 22454 
    [ 2.500,  5.000) = 286936 
    [ 5.000,  7.500) = 3265 
    [ 7.500, 10.000) = 435 
    [10.000, 12.500) = 185 
    [12.500, 15.000) = 42 
    [15.000, 17.500) = 53 
    [17.500, 20.000) = 109 
    [20.000, 22.500) = 54 
    [22.500, 25.000) = 19 
    [25.000, 27.500) = 24 

  Percentiles, ms/op:
      p(0.0000) =      0.727 ms/op
     p(50.0000) =      3.039 ms/op
     p(90.0000) =      3.273 ms/op
     p(95.0000) =      3.506 ms/op
     p(99.0000) =      5.186 ms/op
     p(99.9000) =     11.843 ms/op
     p(99.9900) =     23.581 ms/op
     p(99.9990) =     26.950 ms/op
     p(99.9999) =     27.001 ms/op
    p(100.0000) =     27.001 ms/op


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
# Warmup Iteration   1: 7.853 ±(99.9%) 0.088 ms/op
# Warmup Iteration   2: 3.453 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.347 ±(99.9%) 0.010 ms/op
Iteration   1: 3.347 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   0.952 ms/op
                 getUser·p0.50:   3.166 ms/op
                 getUser·p0.90:   3.990 ms/op
                 getUser·p0.95:   5.038 ms/op
                 getUser·p0.99:   6.709 ms/op
                 getUser·p0.999:  17.055 ms/op
                 getUser·p0.9999: 25.770 ms/op
                 getUser·p1.00:   26.509 ms/op

Iteration   2: 3.172 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.777 ms/op
                 getUser·p0.50:   3.113 ms/op
                 getUser·p0.90:   3.518 ms/op
                 getUser·p0.95:   3.817 ms/op
                 getUser·p0.99:   5.505 ms/op
                 getUser·p0.999:  10.452 ms/op
                 getUser·p0.9999: 21.722 ms/op
                 getUser·p1.00:   23.298 ms/op

Iteration   3: 3.147 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.898 ms/op
                 getUser·p0.50:   3.019 ms/op
                 getUser·p0.90:   3.416 ms/op
                 getUser·p0.95:   3.686 ms/op
                 getUser·p0.99:   5.775 ms/op
                 getUser·p0.999:  14.398 ms/op
                 getUser·p0.9999: 20.011 ms/op
                 getUser·p1.00:   20.808 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 298033
  mean =      3.220 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15078 
    [ 2.500,  5.000) = 273507 
    [ 5.000,  7.500) = 8246 
    [ 7.500, 10.000) = 713 
    [10.000, 12.500) = 124 
    [12.500, 15.000) = 56 
    [15.000, 17.500) = 101 
    [17.500, 20.000) = 137 
    [20.000, 22.500) = 34 
    [22.500, 25.000) = 12 
    [25.000, 27.500) = 25 

  Percentiles, ms/op:
      p(0.0000) =      0.777 ms/op
     p(50.0000) =      3.101 ms/op
     p(90.0000) =      3.617 ms/op
     p(95.0000) =      4.137 ms/op
     p(99.0000) =      6.316 ms/op
     p(99.9000) =     15.581 ms/op
     p(99.9900) =     24.648 ms/op
     p(99.9990) =     26.251 ms/op
     p(99.9999) =     26.509 ms/op
    p(100.0000) =     26.509 ms/op


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
# Warmup Iteration   1: 9.070 ±(99.9%) 0.119 ms/op
# Warmup Iteration   2: 4.035 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.805 ±(99.9%) 0.012 ms/op
Iteration   1: 3.663 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.520 ms/op
                 listUser·p0.50:   3.539 ms/op
                 listUser·p0.90:   3.924 ms/op
                 listUser·p0.95:   4.149 ms/op
                 listUser·p0.99:   6.423 ms/op
                 listUser·p0.999:  15.335 ms/op
                 listUser·p0.9999: 18.293 ms/op
                 listUser·p1.00:   19.628 ms/op

Iteration   2: 3.732 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.966 ms/op
                 listUser·p0.50:   3.576 ms/op
                 listUser·p0.90:   3.981 ms/op
                 listUser·p0.95:   4.268 ms/op
                 listUser·p0.99:   7.758 ms/op
                 listUser·p0.999:  13.245 ms/op
                 listUser·p0.9999: 15.126 ms/op
                 listUser·p1.00:   19.104 ms/op

Iteration   3: 3.688 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.150 ms/op
                 listUser·p0.50:   3.637 ms/op
                 listUser·p0.90:   3.940 ms/op
                 listUser·p0.95:   4.190 ms/op
                 listUser·p0.99:   6.545 ms/op
                 listUser·p0.999:  12.895 ms/op
                 listUser·p0.9999: 18.547 ms/op
                 listUser·p1.00:   18.711 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 259527
  mean =      3.694 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 0 
    [ 1.250,  2.500) = 109 
    [ 2.500,  3.750) = 201187 
    [ 3.750,  5.000) = 50680 
    [ 5.000,  6.250) = 2687 
    [ 6.250,  7.500) = 2958 
    [ 7.500,  8.750) = 791 
    [ 8.750, 10.000) = 333 
    [10.000, 11.250) = 237 
    [11.250, 12.500) = 136 
    [12.500, 13.750) = 203 
    [13.750, 15.000) = 58 
    [15.000, 16.250) = 82 
    [16.250, 17.500) = 28 
    [17.500, 18.750) = 35 

  Percentiles, ms/op:
      p(0.0000) =      1.520 ms/op
     p(50.0000) =      3.576 ms/op
     p(90.0000) =      3.953 ms/op
     p(95.0000) =      4.202 ms/op
     p(99.0000) =      6.726 ms/op
     p(99.9000) =     13.255 ms/op
     p(99.9900) =     18.222 ms/op
     p(99.9990) =     18.909 ms/op
     p(99.9999) =     19.628 ms/op
    p(100.0000) =     19.628 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.778 ± 1.687  ops/ms
ClientPb.existUser                       thrpt       3  10.453 ± 7.785  ops/ms
ClientPb.getUser                         thrpt       3  10.176 ± 7.928  ops/ms
ClientPb.listUser                        thrpt       3   8.631 ± 1.112  ops/ms
ClientPb.createUser                       avgt       3   3.072 ± 0.362   ms/op
ClientPb.existUser                        avgt       3   3.031 ± 2.227   ms/op
ClientPb.getUser                          avgt       3   3.163 ± 0.942   ms/op
ClientPb.listUser                         avgt       3   3.681 ± 1.149   ms/op
ClientPb.createUser                     sample  295234   3.251 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.920           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.166           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.707           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.350           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.628           ms/op
ClientPb.createUser:createUser·p0.999   sample          15.577           ms/op
ClientPb.createUser:createUser·p0.9999  sample          27.196           ms/op
ClientPb.createUser:createUser·p1.00    sample          32.178           ms/op
ClientPb.existUser                      sample  313576   3.060 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.727           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.039           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.273           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.506           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.186           ms/op
ClientPb.existUser:existUser·p0.999     sample          11.843           ms/op
ClientPb.existUser:existUser·p0.9999    sample          23.581           ms/op
ClientPb.existUser:existUser·p1.00      sample          27.001           ms/op
ClientPb.getUser                        sample  298033   3.220 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.777           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.101           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.617           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.137           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.316           ms/op
ClientPb.getUser:getUser·p0.999         sample          15.581           ms/op
ClientPb.getUser:getUser·p0.9999        sample          24.648           ms/op
ClientPb.getUser:getUser·p1.00          sample          26.509           ms/op
ClientPb.listUser                       sample  259527   3.694 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.520           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.576           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.953           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.202           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.726           ms/op
ClientPb.listUser:listUser·p0.999       sample          13.255           ms/op
ClientPb.listUser:listUser·p0.9999      sample          18.222           ms/op
ClientPb.listUser:listUser·p1.00        sample          19.628           ms/op
