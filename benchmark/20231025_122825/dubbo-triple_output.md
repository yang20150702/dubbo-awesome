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
# Warmup Iteration   1: 2.362 ops/ms
# Warmup Iteration   2: 5.570 ops/ms
# Warmup Iteration   3: 9.465 ops/ms
Iteration   1: 9.772 ops/ms
Iteration   2: 9.877 ops/ms
Iteration   3: 9.726 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.792 ±(99.9%) 1.417 ops/ms [Average]
  (min, avg, max) = (9.726, 9.792, 9.877), stdev = 0.078
  CI (99.9%): [8.375, 11.208] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:08
# Fork: 1 of 1
# Warmup Iteration   1: 3.414 ops/ms
# Warmup Iteration   2: 9.426 ops/ms
# Warmup Iteration   3: 10.033 ops/ms
Iteration   1: 10.076 ops/ms
Iteration   2: 10.240 ops/ms
Iteration   3: 10.194 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.170 ±(99.9%) 1.541 ops/ms [Average]
  (min, avg, max) = (10.076, 10.170, 10.240), stdev = 0.084
  CI (99.9%): [8.629, 11.711] (assumes normal distribution)


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
# Warmup Iteration   1: 3.340 ops/ms
# Warmup Iteration   2: 8.965 ops/ms
# Warmup Iteration   3: 9.539 ops/ms
Iteration   1: 9.792 ops/ms
Iteration   2: 10.091 ops/ms
Iteration   3: 9.719 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.867 ±(99.9%) 3.601 ops/ms [Average]
  (min, avg, max) = (9.719, 9.867, 10.091), stdev = 0.197
  CI (99.9%): [6.266, 13.469] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:55
# Fork: 1 of 1
# Warmup Iteration   1: 3.021 ops/ms
# Warmup Iteration   2: 7.589 ops/ms
# Warmup Iteration   3: 8.376 ops/ms
Iteration   1: 8.277 ops/ms
Iteration   2: 8.420 ops/ms
Iteration   3: 8.558 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.418 ±(99.9%) 2.568 ops/ms [Average]
  (min, avg, max) = (8.277, 8.418, 8.558), stdev = 0.141
  CI (99.9%): [5.851, 10.986] (assumes normal distribution)


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
# Warmup Iteration   1: 9.258 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.561 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.378 ±(99.9%) 0.003 ms/op
Iteration   1: 3.222 ±(99.9%) 0.005 ms/op
Iteration   2: 3.301 ±(99.9%) 0.005 ms/op
Iteration   3: 3.220 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.248 ±(99.9%) 0.838 ms/op [Average]
  (min, avg, max) = (3.220, 3.248, 3.301), stdev = 0.046
  CI (99.9%): [2.410, 4.086] (assumes normal distribution)


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
# Warmup Iteration   1: 6.774 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 3.394 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.108 ±(99.9%) 0.002 ms/op
Iteration   1: 3.160 ±(99.9%) 0.003 ms/op
Iteration   2: 3.164 ±(99.9%) 0.002 ms/op
Iteration   3: 3.159 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.161 ±(99.9%) 0.050 ms/op [Average]
  (min, avg, max) = (3.159, 3.161, 3.164), stdev = 0.003
  CI (99.9%): [3.111, 3.211] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:36
# Fork: 1 of 1
# Warmup Iteration   1: 8.543 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 3.463 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.342 ±(99.9%) 0.003 ms/op
Iteration   1: 3.191 ±(99.9%) 0.003 ms/op
Iteration   2: 3.210 ±(99.9%) 0.002 ms/op
Iteration   3: 3.226 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.209 ±(99.9%) 0.317 ms/op [Average]
  (min, avg, max) = (3.191, 3.209, 3.226), stdev = 0.017
  CI (99.9%): [2.892, 3.526] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:30
# Fork: 1 of 1
# Warmup Iteration   1: 9.447 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 4.112 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.914 ±(99.9%) 0.002 ms/op
Iteration   1: 3.883 ±(99.9%) 0.005 ms/op
Iteration   2: 3.768 ±(99.9%) 0.005 ms/op
Iteration   3: 3.773 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.808 ±(99.9%) 1.193 ms/op [Average]
  (min, avg, max) = (3.768, 3.808, 3.883), stdev = 0.065
  CI (99.9%): [2.615, 5.001] (assumes normal distribution)


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
# Warmup Iteration   1: 8.240 ±(99.9%) 0.108 ms/op
# Warmup Iteration   2: 3.774 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.322 ±(99.9%) 0.007 ms/op
Iteration   1: 3.212 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.409 ms/op
                 createUser·p0.50:   3.109 ms/op
                 createUser·p0.90:   3.506 ms/op
                 createUser·p0.95:   3.764 ms/op
                 createUser·p0.99:   5.620 ms/op
                 createUser·p0.999:  17.327 ms/op
                 createUser·p0.9999: 19.169 ms/op
                 createUser·p1.00:   19.595 ms/op

Iteration   2: 3.246 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.956 ms/op
                 createUser·p0.50:   3.133 ms/op
                 createUser·p0.90:   3.621 ms/op
                 createUser·p0.95:   3.858 ms/op
                 createUser·p0.99:   5.554 ms/op
                 createUser·p0.999:  16.283 ms/op
                 createUser·p0.9999: 21.402 ms/op
                 createUser·p1.00:   23.757 ms/op

Iteration   3: 3.281 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   1.518 ms/op
                 createUser·p0.50:   3.256 ms/op
                 createUser·p0.90:   3.637 ms/op
                 createUser·p0.95:   3.928 ms/op
                 createUser·p0.99:   5.349 ms/op
                 createUser·p0.999:  15.646 ms/op
                 createUser·p0.9999: 20.039 ms/op
                 createUser·p1.00:   21.725 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 295423
  mean =      3.246 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12962 
    [ 2.500,  5.000) = 277744 
    [ 5.000,  7.500) = 3770 
    [ 7.500, 10.000) = 343 
    [10.000, 12.500) = 195 
    [12.500, 15.000) = 45 
    [15.000, 17.500) = 113 
    [17.500, 20.000) = 204 
    [20.000, 22.500) = 46 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.956 ms/op
     p(50.0000) =      3.170 ms/op
     p(90.0000) =      3.596 ms/op
     p(95.0000) =      3.858 ms/op
     p(99.0000) =      5.489 ms/op
     p(99.9000) =     16.724 ms/op
     p(99.9900) =     20.692 ms/op
     p(99.9990) =     21.823 ms/op
     p(99.9999) =     23.757 ms/op
    p(100.0000) =     23.757 ms/op


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
# Warmup Iteration   1: 7.264 ±(99.9%) 0.081 ms/op
# Warmup Iteration   2: 3.370 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.189 ±(99.9%) 0.008 ms/op
Iteration   1: 3.176 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.100 ms/op
                 existUser·p0.50:   3.117 ms/op
                 existUser·p0.90:   3.482 ms/op
                 existUser·p0.95:   3.785 ms/op
                 existUser·p0.99:   5.399 ms/op
                 existUser·p0.999:  13.891 ms/op
                 existUser·p0.9999: 19.825 ms/op
                 existUser·p1.00:   20.709 ms/op

Iteration   2: 3.197 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.241 ms/op
                 existUser·p0.50:   3.129 ms/op
                 existUser·p0.90:   3.547 ms/op
                 existUser·p0.95:   3.801 ms/op
                 existUser·p0.99:   5.464 ms/op
                 existUser·p0.999:  18.121 ms/op
                 existUser·p0.9999: 22.708 ms/op
                 existUser·p1.00:   23.331 ms/op

Iteration   3: 3.195 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.350 ms/op
                 existUser·p0.50:   3.146 ms/op
                 existUser·p0.90:   3.523 ms/op
                 existUser·p0.95:   3.830 ms/op
                 existUser·p0.99:   5.439 ms/op
                 existUser·p0.999:  14.008 ms/op
                 existUser·p0.9999: 21.887 ms/op
                 existUser·p1.00:   22.905 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 300713
  mean =      3.189 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14238 
    [ 2.500,  5.000) = 281945 
    [ 5.000,  7.500) = 3688 
    [ 7.500, 10.000) = 138 
    [10.000, 12.500) = 209 
    [12.500, 15.000) = 213 
    [15.000, 17.500) = 28 
    [17.500, 20.000) = 95 
    [20.000, 22.500) = 136 
    [22.500, 25.000) = 23 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.100 ms/op
     p(50.0000) =      3.129 ms/op
     p(90.0000) =      3.518 ms/op
     p(95.0000) =      3.805 ms/op
     p(99.0000) =      5.407 ms/op
     p(99.9000) =     14.542 ms/op
     p(99.9900) =     22.282 ms/op
     p(99.9990) =     23.134 ms/op
     p(99.9999) =     23.331 ms/op
    p(100.0000) =     23.331 ms/op


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
# Warmup Iteration   1: 9.231 ±(99.9%) 0.160 ms/op
# Warmup Iteration   2: 3.547 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.285 ±(99.9%) 0.010 ms/op
Iteration   1: 3.312 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.509 ms/op
                 getUser·p0.50:   3.228 ms/op
                 getUser·p0.90:   3.707 ms/op
                 getUser·p0.95:   4.097 ms/op
                 getUser·p0.99:   5.898 ms/op
                 getUser·p0.999:  16.710 ms/op
                 getUser·p0.9999: 21.212 ms/op
                 getUser·p1.00:   22.053 ms/op

Iteration   2: 3.222 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   1.063 ms/op
                 getUser·p0.50:   3.195 ms/op
                 getUser·p0.90:   3.564 ms/op
                 getUser·p0.95:   3.785 ms/op
                 getUser·p0.99:   5.210 ms/op
                 getUser·p0.999:  9.142 ms/op
                 getUser·p0.9999: 22.252 ms/op
                 getUser·p1.00:   23.560 ms/op

Iteration   3: 3.282 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.626 ms/op
                 getUser·p0.50:   3.215 ms/op
                 getUser·p0.90:   3.674 ms/op
                 getUser·p0.95:   3.994 ms/op
                 getUser·p0.99:   6.005 ms/op
                 getUser·p0.999:  12.361 ms/op
                 getUser·p0.9999: 22.151 ms/op
                 getUser·p1.00:   22.610 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 293438
  mean =      3.271 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 19182 
    [ 2.500,  5.000) = 268584 
    [ 5.000,  7.500) = 4898 
    [ 7.500, 10.000) = 272 
    [10.000, 12.500) = 130 
    [12.500, 15.000) = 93 
    [15.000, 17.500) = 51 
    [17.500, 20.000) = 92 
    [20.000, 22.500) = 131 
    [22.500, 25.000) = 5 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.063 ms/op
     p(50.0000) =      3.215 ms/op
     p(90.0000) =      3.650 ms/op
     p(95.0000) =      3.949 ms/op
     p(99.0000) =      5.767 ms/op
     p(99.9000) =     14.431 ms/op
     p(99.9900) =     21.758 ms/op
     p(99.9990) =     22.681 ms/op
     p(99.9999) =     23.560 ms/op
    p(100.0000) =     23.560 ms/op


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
# Warmup Iteration   1: 8.244 ±(99.9%) 0.106 ms/op
# Warmup Iteration   2: 4.138 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.901 ±(99.9%) 0.012 ms/op
Iteration   1: 3.828 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.236 ms/op
                 listUser·p0.50:   3.699 ms/op
                 listUser·p0.90:   4.080 ms/op
                 listUser·p0.95:   4.301 ms/op
                 listUser·p0.99:   7.062 ms/op
                 listUser·p0.999:  15.357 ms/op
                 listUser·p0.9999: 18.732 ms/op
                 listUser·p1.00:   24.052 ms/op

Iteration   2: 3.843 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.437 ms/op
                 listUser·p0.50:   3.736 ms/op
                 listUser·p0.90:   4.182 ms/op
                 listUser·p0.95:   4.366 ms/op
                 listUser·p0.99:   6.357 ms/op
                 listUser·p0.999:  13.054 ms/op
                 listUser·p0.9999: 14.647 ms/op
                 listUser·p1.00:   14.729 ms/op

Iteration   3: 3.843 ±(99.9%) 0.007 ms/op
                 listUser·p0.00:   2.261 ms/op
                 listUser·p0.50:   3.793 ms/op
                 listUser·p0.90:   4.149 ms/op
                 listUser·p0.95:   4.317 ms/op
                 listUser·p0.99:   6.463 ms/op
                 listUser·p0.999:  12.153 ms/op
                 listUser·p0.9999: 13.828 ms/op
                 listUser·p1.00:   14.893 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 249991
  mean =      3.838 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 23 
    [ 2.500,  5.000) = 243853 
    [ 5.000,  7.500) = 4738 
    [ 7.500, 10.000) = 656 
    [10.000, 12.500) = 323 
    [12.500, 15.000) = 300 
    [15.000, 17.500) = 68 
    [17.500, 20.000) = 28 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.236 ms/op
     p(50.0000) =      3.744 ms/op
     p(90.0000) =      4.145 ms/op
     p(95.0000) =      4.334 ms/op
     p(99.0000) =      6.685 ms/op
     p(99.9000) =     13.517 ms/op
     p(99.9900) =     17.596 ms/op
     p(99.9990) =     21.775 ms/op
     p(99.9999) =     24.052 ms/op
    p(100.0000) =     24.052 ms/op


# Run complete. Total time: 00:13:13

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.792 ± 1.417  ops/ms
ClientPb.existUser                       thrpt       3  10.170 ± 1.541  ops/ms
ClientPb.getUser                         thrpt       3   9.867 ± 3.601  ops/ms
ClientPb.listUser                        thrpt       3   8.418 ± 2.568  ops/ms
ClientPb.createUser                       avgt       3   3.248 ± 0.838   ms/op
ClientPb.existUser                        avgt       3   3.161 ± 0.050   ms/op
ClientPb.getUser                          avgt       3   3.209 ± 0.317   ms/op
ClientPb.listUser                         avgt       3   3.808 ± 1.193   ms/op
ClientPb.createUser                     sample  295423   3.246 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.956           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.170           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.596           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.858           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.489           ms/op
ClientPb.createUser:createUser·p0.999   sample          16.724           ms/op
ClientPb.createUser:createUser·p0.9999  sample          20.692           ms/op
ClientPb.createUser:createUser·p1.00    sample          23.757           ms/op
ClientPb.existUser                      sample  300713   3.189 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.100           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.129           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.518           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.805           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.407           ms/op
ClientPb.existUser:existUser·p0.999     sample          14.542           ms/op
ClientPb.existUser:existUser·p0.9999    sample          22.282           ms/op
ClientPb.existUser:existUser·p1.00      sample          23.331           ms/op
ClientPb.getUser                        sample  293438   3.271 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.063           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.215           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.650           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.949           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.767           ms/op
ClientPb.getUser:getUser·p0.999         sample          14.431           ms/op
ClientPb.getUser:getUser·p0.9999        sample          21.758           ms/op
ClientPb.getUser:getUser·p1.00          sample          23.560           ms/op
ClientPb.listUser                       sample  249991   3.838 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.236           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.744           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.145           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.334           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.685           ms/op
ClientPb.listUser:listUser·p0.999       sample          13.517           ms/op
ClientPb.listUser:listUser·p0.9999      sample          17.596           ms/op
ClientPb.listUser:listUser·p1.00        sample          24.052           ms/op
