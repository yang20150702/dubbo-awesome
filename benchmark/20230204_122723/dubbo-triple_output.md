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
# Warmup Iteration   1: 2.052 ops/ms
# Warmup Iteration   2: 5.573 ops/ms
# Warmup Iteration   3: 8.600 ops/ms
Iteration   1: 9.428 ops/ms
Iteration   2: 9.334 ops/ms
Iteration   3: 9.905 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.556 ±(99.9%) 5.582 ops/ms [Average]
  (min, avg, max) = (9.334, 9.556, 9.905), stdev = 0.306
  CI (99.9%): [3.974, 15.137] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:08
# Fork: 1 of 1
# Warmup Iteration   1: 3.335 ops/ms
# Warmup Iteration   2: 8.924 ops/ms
# Warmup Iteration   3: 9.465 ops/ms
Iteration   1: 9.546 ops/ms
Iteration   2: 9.909 ops/ms
Iteration   3: 9.797 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.751 ±(99.9%) 3.388 ops/ms [Average]
  (min, avg, max) = (9.546, 9.751, 9.909), stdev = 0.186
  CI (99.9%): [6.362, 13.139] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.773 ops/ms
# Warmup Iteration   2: 8.103 ops/ms
# Warmup Iteration   3: 8.944 ops/ms
Iteration   1: 9.700 ops/ms
Iteration   2: 9.268 ops/ms
Iteration   3: 9.543 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.504 ±(99.9%) 3.989 ops/ms [Average]
  (min, avg, max) = (9.268, 9.504, 9.700), stdev = 0.219
  CI (99.9%): [5.515, 13.493] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:54
# Fork: 1 of 1
# Warmup Iteration   1: 2.842 ops/ms
# Warmup Iteration   2: 7.241 ops/ms
# Warmup Iteration   3: 7.954 ops/ms
Iteration   1: 8.063 ops/ms
Iteration   2: 8.120 ops/ms
Iteration   3: 8.140 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.108 ±(99.9%) 0.728 ops/ms [Average]
  (min, avg, max) = (8.063, 8.108, 8.140), stdev = 0.040
  CI (99.9%): [7.379, 8.836] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:48
# Fork: 1 of 1
# Warmup Iteration   1: 9.786 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.727 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.703 ±(99.9%) 0.003 ms/op
Iteration   1: 3.390 ±(99.9%) 0.011 ms/op
Iteration   2: 3.381 ±(99.9%) 0.012 ms/op
Iteration   3: 3.522 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.431 ±(99.9%) 1.442 ms/op [Average]
  (min, avg, max) = (3.381, 3.431, 3.522), stdev = 0.079
  CI (99.9%): [1.989, 4.873] (assumes normal distribution)


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
# Warmup Iteration   1: 9.417 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.642 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.299 ±(99.9%) 0.003 ms/op
Iteration   1: 3.317 ±(99.9%) 0.004 ms/op
Iteration   2: 3.217 ±(99.9%) 0.008 ms/op
Iteration   3: 3.271 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.268 ±(99.9%) 0.914 ms/op [Average]
  (min, avg, max) = (3.217, 3.268, 3.317), stdev = 0.050
  CI (99.9%): [2.354, 4.182] (assumes normal distribution)


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
# Warmup Iteration   1: 9.464 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.721 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.504 ±(99.9%) 0.004 ms/op
Iteration   1: 3.455 ±(99.9%) 0.004 ms/op
Iteration   2: 3.361 ±(99.9%) 0.005 ms/op
Iteration   3: 3.373 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.396 ±(99.9%) 0.934 ms/op [Average]
  (min, avg, max) = (3.361, 3.396, 3.455), stdev = 0.051
  CI (99.9%): [2.462, 4.331] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 10.754 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 4.352 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.944 ±(99.9%) 0.007 ms/op
Iteration   1: 3.990 ±(99.9%) 0.007 ms/op
Iteration   2: 3.954 ±(99.9%) 0.013 ms/op
Iteration   3: 3.788 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.911 ±(99.9%) 1.968 ms/op [Average]
  (min, avg, max) = (3.788, 3.911, 3.990), stdev = 0.108
  CI (99.9%): [1.943, 5.878] (assumes normal distribution)


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
# Warmup Iteration   1: 8.749 ±(99.9%) 0.115 ms/op
# Warmup Iteration   2: 3.917 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.446 ±(99.9%) 0.010 ms/op
Iteration   1: 3.366 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.516 ms/op
                 createUser·p0.50:   3.228 ms/op
                 createUser·p0.90:   3.744 ms/op
                 createUser·p0.95:   4.108 ms/op
                 createUser·p0.99:   5.644 ms/op
                 createUser·p0.999:  19.663 ms/op
                 createUser·p0.9999: 24.369 ms/op
                 createUser·p1.00:   25.461 ms/op

Iteration   2: 3.494 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.520 ms/op
                 createUser·p0.50:   3.383 ms/op
                 createUser·p0.90:   4.112 ms/op
                 createUser·p0.95:   4.489 ms/op
                 createUser·p0.99:   5.579 ms/op
                 createUser·p0.999:  21.704 ms/op
                 createUser·p0.9999: 23.719 ms/op
                 createUser·p1.00:   25.264 ms/op

Iteration   3: 3.482 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.470 ms/op
                 createUser·p0.50:   3.359 ms/op
                 createUser·p0.90:   4.076 ms/op
                 createUser·p0.95:   4.342 ms/op
                 createUser·p0.99:   5.423 ms/op
                 createUser·p0.999:  17.683 ms/op
                 createUser·p0.9999: 26.256 ms/op
                 createUser·p1.00:   27.132 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 278421
  mean =      3.446 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9479 
    [ 2.500,  5.000) = 263335 
    [ 5.000,  7.500) = 4578 
    [ 7.500, 10.000) = 588 
    [10.000, 12.500) = 121 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 2 
    [17.500, 20.000) = 41 
    [20.000, 22.500) = 132 
    [22.500, 25.000) = 91 
    [25.000, 27.500) = 22 

  Percentiles, ms/op:
      p(0.0000) =      1.470 ms/op
     p(50.0000) =      3.330 ms/op
     p(90.0000) =      4.002 ms/op
     p(95.0000) =      4.366 ms/op
     p(99.0000) =      5.579 ms/op
     p(99.9000) =     18.019 ms/op
     p(99.9900) =     24.816 ms/op
     p(99.9990) =     26.592 ms/op
     p(99.9999) =     27.132 ms/op
    p(100.0000) =     27.132 ms/op


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
# Warmup Iteration   1: 8.407 ±(99.9%) 0.117 ms/op
# Warmup Iteration   2: 3.601 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.367 ±(99.9%) 0.009 ms/op
Iteration   1: 3.292 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.118 ms/op
                 existUser·p0.50:   3.199 ms/op
                 existUser·p0.90:   3.670 ms/op
                 existUser·p0.95:   4.088 ms/op
                 existUser·p0.99:   5.267 ms/op
                 existUser·p0.999:  9.266 ms/op
                 existUser·p0.9999: 22.577 ms/op
                 existUser·p1.00:   23.593 ms/op

Iteration   2: 3.366 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.196 ms/op
                 existUser·p0.50:   3.273 ms/op
                 existUser·p0.90:   3.731 ms/op
                 existUser·p0.95:   4.194 ms/op
                 existUser·p0.99:   5.628 ms/op
                 existUser·p0.999:  10.139 ms/op
                 existUser·p0.9999: 25.116 ms/op
                 existUser·p1.00:   26.018 ms/op

Iteration   3: 3.369 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.350 ms/op
                 existUser·p0.50:   3.228 ms/op
                 existUser·p0.90:   3.822 ms/op
                 existUser·p0.95:   4.489 ms/op
                 existUser·p0.99:   5.915 ms/op
                 existUser·p0.999:  22.577 ms/op
                 existUser·p0.9999: 26.018 ms/op
                 existUser·p1.00:   27.034 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 287369
  mean =      3.342 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7924 
    [ 2.500,  5.000) = 273517 
    [ 5.000,  7.500) = 5100 
    [ 7.500, 10.000) = 404 
    [10.000, 12.500) = 144 
    [12.500, 15.000) = 15 
    [15.000, 17.500) = 9 
    [17.500, 20.000) = 5 
    [20.000, 22.500) = 80 
    [22.500, 25.000) = 131 
    [25.000, 27.500) = 40 

  Percentiles, ms/op:
      p(0.0000) =      1.118 ms/op
     p(50.0000) =      3.232 ms/op
     p(90.0000) =      3.731 ms/op
     p(95.0000) =      4.252 ms/op
     p(99.0000) =      5.612 ms/op
     p(99.9000) =     12.429 ms/op
     p(99.9900) =     25.174 ms/op
     p(99.9990) =     26.878 ms/op
     p(99.9999) =     27.034 ms/op
    p(100.0000) =     27.034 ms/op


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
# Warmup Iteration   1: 9.261 ±(99.9%) 0.120 ms/op
# Warmup Iteration   2: 3.752 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.485 ±(99.9%) 0.010 ms/op
Iteration   1: 3.419 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.038 ms/op
                 getUser·p0.50:   3.232 ms/op
                 getUser·p0.90:   3.822 ms/op
                 getUser·p0.95:   4.597 ms/op
                 getUser·p0.99:   6.693 ms/op
                 getUser·p0.999:  18.266 ms/op
                 getUser·p0.9999: 20.504 ms/op
                 getUser·p1.00:   24.412 ms/op

Iteration   2: 3.370 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.618 ms/op
                 getUser·p0.50:   3.301 ms/op
                 getUser·p0.90:   3.641 ms/op
                 getUser·p0.95:   3.781 ms/op
                 getUser·p0.99:   4.866 ms/op
                 getUser·p0.999:  19.211 ms/op
                 getUser·p0.9999: 21.906 ms/op
                 getUser·p1.00:   23.036 ms/op

Iteration   3: 3.400 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.743 ms/op
                 getUser·p0.50:   3.273 ms/op
                 getUser·p0.90:   3.740 ms/op
                 getUser·p0.95:   4.076 ms/op
                 getUser·p0.99:   5.907 ms/op
                 getUser·p0.999:  16.959 ms/op
                 getUser·p0.9999: 23.192 ms/op
                 getUser·p1.00:   25.002 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 282557
  mean =      3.396 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4527 
    [ 2.500,  5.000) = 270173 
    [ 5.000,  7.500) = 6740 
    [ 7.500, 10.000) = 643 
    [10.000, 12.500) = 74 
    [12.500, 15.000) = 57 
    [15.000, 17.500) = 36 
    [17.500, 20.000) = 166 
    [20.000, 22.500) = 113 
    [22.500, 25.000) = 27 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.038 ms/op
     p(50.0000) =      3.269 ms/op
     p(90.0000) =      3.719 ms/op
     p(95.0000) =      4.002 ms/op
     p(99.0000) =      6.275 ms/op
     p(99.9000) =     18.004 ms/op
     p(99.9900) =     22.495 ms/op
     p(99.9990) =     24.418 ms/op
     p(99.9999) =     25.002 ms/op
    p(100.0000) =     25.002 ms/op


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
# Warmup Iteration   1: 11.117 ±(99.9%) 0.154 ms/op
# Warmup Iteration   2: 4.590 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.066 ±(99.9%) 0.013 ms/op
Iteration   1: 4.089 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.470 ms/op
                 listUser·p0.50:   3.949 ms/op
                 listUser·p0.90:   4.514 ms/op
                 listUser·p0.95:   4.915 ms/op
                 listUser·p0.99:   7.709 ms/op
                 listUser·p0.999:  20.152 ms/op
                 listUser·p0.9999: 23.601 ms/op
                 listUser·p1.00:   25.756 ms/op

Iteration   2: 3.962 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.298 ms/op
                 listUser·p0.50:   3.838 ms/op
                 listUser·p0.90:   4.481 ms/op
                 listUser·p0.95:   4.678 ms/op
                 listUser·p0.99:   6.796 ms/op
                 listUser·p0.999:  14.516 ms/op
                 listUser·p0.9999: 16.876 ms/op
                 listUser·p1.00:   16.941 ms/op

Iteration   3: 3.935 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.306 ms/op
                 listUser·p0.50:   3.793 ms/op
                 listUser·p0.90:   4.268 ms/op
                 listUser·p0.95:   4.514 ms/op
                 listUser·p0.99:   7.086 ms/op
                 listUser·p0.999:  15.117 ms/op
                 listUser·p0.9999: 16.344 ms/op
                 listUser·p1.00:   19.005 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 240176
  mean =      3.994 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 36 
    [ 2.500,  5.000) = 232314 
    [ 5.000,  7.500) = 5710 
    [ 7.500, 10.000) = 1474 
    [10.000, 12.500) = 122 
    [12.500, 15.000) = 232 
    [15.000, 17.500) = 185 
    [17.500, 20.000) = 22 
    [20.000, 22.500) = 68 
    [22.500, 25.000) = 12 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.470 ms/op
     p(50.0000) =      3.858 ms/op
     p(90.0000) =      4.424 ms/op
     p(95.0000) =      4.702 ms/op
     p(99.0000) =      7.225 ms/op
     p(99.9000) =     15.349 ms/op
     p(99.9900) =     21.986 ms/op
     p(99.9990) =     24.137 ms/op
     p(99.9999) =     25.756 ms/op
    p(100.0000) =     25.756 ms/op


# Run complete. Total time: 00:13:13

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.556 ± 5.582  ops/ms
ClientPb.existUser                       thrpt       3   9.751 ± 3.388  ops/ms
ClientPb.getUser                         thrpt       3   9.504 ± 3.989  ops/ms
ClientPb.listUser                        thrpt       3   8.108 ± 0.728  ops/ms
ClientPb.createUser                       avgt       3   3.431 ± 1.442   ms/op
ClientPb.existUser                        avgt       3   3.268 ± 0.914   ms/op
ClientPb.getUser                          avgt       3   3.396 ± 0.934   ms/op
ClientPb.listUser                         avgt       3   3.911 ± 1.968   ms/op
ClientPb.createUser                     sample  278421   3.446 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.470           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.330           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.002           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.366           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.579           ms/op
ClientPb.createUser:createUser·p0.999   sample          18.019           ms/op
ClientPb.createUser:createUser·p0.9999  sample          24.816           ms/op
ClientPb.createUser:createUser·p1.00    sample          27.132           ms/op
ClientPb.existUser                      sample  287369   3.342 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.118           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.232           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.731           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.252           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.612           ms/op
ClientPb.existUser:existUser·p0.999     sample          12.429           ms/op
ClientPb.existUser:existUser·p0.9999    sample          25.174           ms/op
ClientPb.existUser:existUser·p1.00      sample          27.034           ms/op
ClientPb.getUser                        sample  282557   3.396 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.038           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.269           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.719           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.002           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.275           ms/op
ClientPb.getUser:getUser·p0.999         sample          18.004           ms/op
ClientPb.getUser:getUser·p0.9999        sample          22.495           ms/op
ClientPb.getUser:getUser·p1.00          sample          25.002           ms/op
ClientPb.listUser                       sample  240176   3.994 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.470           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.858           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.424           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.702           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.225           ms/op
ClientPb.listUser:listUser·p0.999       sample          15.349           ms/op
ClientPb.listUser:listUser·p0.9999      sample          21.986           ms/op
ClientPb.listUser:listUser·p1.00        sample          25.756           ms/op
