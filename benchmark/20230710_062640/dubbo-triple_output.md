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
# Warmup Iteration   1: 1.887 ops/ms
# Warmup Iteration   2: 5.519 ops/ms
# Warmup Iteration   3: 8.481 ops/ms
Iteration   1: 9.228 ops/ms
Iteration   2: 9.182 ops/ms
Iteration   3: 9.289 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.233 ±(99.9%) 0.983 ops/ms [Average]
  (min, avg, max) = (9.182, 9.233, 9.289), stdev = 0.054
  CI (99.9%): [8.250, 10.216] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 2.843 ops/ms
# Warmup Iteration   2: 8.687 ops/ms
# Warmup Iteration   3: 9.104 ops/ms
Iteration   1: 9.466 ops/ms
Iteration   2: 9.637 ops/ms
Iteration   3: 9.484 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.529 ±(99.9%) 1.716 ops/ms [Average]
  (min, avg, max) = (9.466, 9.529, 9.637), stdev = 0.094
  CI (99.9%): [7.813, 11.245] (assumes normal distribution)


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
# Warmup Iteration   1: 2.789 ops/ms
# Warmup Iteration   2: 7.967 ops/ms
# Warmup Iteration   3: 8.715 ops/ms
Iteration   1: 9.144 ops/ms
Iteration   2: 9.188 ops/ms
Iteration   3: 9.375 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.235 ±(99.9%) 2.238 ops/ms [Average]
  (min, avg, max) = (9.144, 9.235, 9.375), stdev = 0.123
  CI (99.9%): [6.998, 11.473] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 2.870 ops/ms
# Warmup Iteration   2: 7.385 ops/ms
# Warmup Iteration   3: 7.717 ops/ms
Iteration   1: 7.971 ops/ms
Iteration   2: 7.849 ops/ms
Iteration   3: 8.052 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.957 ±(99.9%) 1.866 ops/ms [Average]
  (min, avg, max) = (7.849, 7.957, 8.052), stdev = 0.102
  CI (99.9%): [6.091, 9.824] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:45
# Fork: 1 of 1
# Warmup Iteration   1: 10.255 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 4.146 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.536 ±(99.9%) 0.006 ms/op
Iteration   1: 3.564 ±(99.9%) 0.006 ms/op
Iteration   2: 3.395 ±(99.9%) 0.007 ms/op
Iteration   3: 3.478 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.479 ±(99.9%) 1.540 ms/op [Average]
  (min, avg, max) = (3.395, 3.479, 3.564), stdev = 0.084
  CI (99.9%): [1.939, 5.019] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 8.785 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 3.558 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.360 ±(99.9%) 0.006 ms/op
Iteration   1: 3.217 ±(99.9%) 0.012 ms/op
Iteration   2: 3.279 ±(99.9%) 0.004 ms/op
Iteration   3: 3.344 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.280 ±(99.9%) 1.158 ms/op [Average]
  (min, avg, max) = (3.217, 3.280, 3.344), stdev = 0.063
  CI (99.9%): [2.122, 4.438] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 9.378 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.721 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.458 ±(99.9%) 0.007 ms/op
Iteration   1: 3.316 ±(99.9%) 0.008 ms/op
Iteration   2: 3.335 ±(99.9%) 0.003 ms/op
Iteration   3: 3.373 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.341 ±(99.9%) 0.526 ms/op [Average]
  (min, avg, max) = (3.316, 3.341, 3.373), stdev = 0.029
  CI (99.9%): [2.815, 3.867] (assumes normal distribution)


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
# Warmup Iteration   1: 10.936 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 4.590 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.107 ±(99.9%) 0.004 ms/op
Iteration   1: 3.995 ±(99.9%) 0.011 ms/op
Iteration   2: 3.957 ±(99.9%) 0.013 ms/op
Iteration   3: 3.884 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.945 ±(99.9%) 1.030 ms/op [Average]
  (min, avg, max) = (3.884, 3.945, 3.995), stdev = 0.056
  CI (99.9%): [2.915, 4.976] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 10.448 ±(99.9%) 0.151 ms/op
# Warmup Iteration   2: 3.948 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.635 ±(99.9%) 0.013 ms/op
Iteration   1: 3.386 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.901 ms/op
                 createUser·p0.50:   3.281 ms/op
                 createUser·p0.90:   3.699 ms/op
                 createUser·p0.95:   4.473 ms/op
                 createUser·p0.99:   6.316 ms/op
                 createUser·p0.999:  19.557 ms/op
                 createUser·p0.9999: 24.463 ms/op
                 createUser·p1.00:   24.773 ms/op

Iteration   2: 3.436 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.255 ms/op
                 createUser·p0.50:   3.387 ms/op
                 createUser·p0.90:   3.809 ms/op
                 createUser·p0.95:   4.084 ms/op
                 createUser·p0.99:   5.734 ms/op
                 createUser·p0.999:  19.917 ms/op
                 createUser·p0.9999: 22.610 ms/op
                 createUser·p1.00:   24.216 ms/op

Iteration   3: 3.329 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.440 ms/op
                 createUser·p0.50:   3.355 ms/op
                 createUser·p0.90:   3.498 ms/op
                 createUser·p0.95:   3.678 ms/op
                 createUser·p0.99:   5.325 ms/op
                 createUser·p0.999:  16.302 ms/op
                 createUser·p0.9999: 24.487 ms/op
                 createUser·p1.00:   25.428 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 283515
  mean =      3.383 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14985 
    [ 2.500,  5.000) = 263094 
    [ 5.000,  7.500) = 4387 
    [ 7.500, 10.000) = 552 
    [10.000, 12.500) = 124 
    [12.500, 15.000) = 51 
    [15.000, 17.500) = 36 
    [17.500, 20.000) = 66 
    [20.000, 22.500) = 144 
    [22.500, 25.000) = 72 
    [25.000, 27.500) = 4 

  Percentiles, ms/op:
      p(0.0000) =      1.255 ms/op
     p(50.0000) =      3.342 ms/op
     p(90.0000) =      3.674 ms/op
     p(95.0000) =      4.026 ms/op
     p(99.0000) =      5.816 ms/op
     p(99.9000) =     17.842 ms/op
     p(99.9900) =     24.138 ms/op
     p(99.9990) =     25.286 ms/op
     p(99.9999) =     25.428 ms/op
    p(100.0000) =     25.428 ms/op


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
# Warmup Iteration   1: 9.706 ±(99.9%) 0.120 ms/op
# Warmup Iteration   2: 3.750 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.332 ±(99.9%) 0.008 ms/op
Iteration   1: 3.428 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.563 ms/op
                 existUser·p0.50:   3.305 ms/op
                 existUser·p0.90:   4.039 ms/op
                 existUser·p0.95:   4.432 ms/op
                 existUser·p0.99:   5.849 ms/op
                 existUser·p0.999:  19.268 ms/op
                 existUser·p0.9999: 21.518 ms/op
                 existUser·p1.00:   22.151 ms/op

Iteration   2: 3.277 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.540 ms/op
                 existUser·p0.50:   3.191 ms/op
                 existUser·p0.90:   3.568 ms/op
                 existUser·p0.95:   3.846 ms/op
                 existUser·p0.99:   4.964 ms/op
                 existUser·p0.999:  14.218 ms/op
                 existUser·p0.9999: 27.155 ms/op
                 existUser·p1.00:   27.689 ms/op

Iteration   3: 3.404 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.775 ms/op
                 existUser·p0.50:   3.363 ms/op
                 existUser·p0.90:   3.748 ms/op
                 existUser·p0.95:   4.071 ms/op
                 existUser·p0.99:   5.636 ms/op
                 existUser·p0.999:  16.454 ms/op
                 existUser·p0.9999: 25.644 ms/op
                 existUser·p1.00:   26.214 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 284742
  mean =      3.369 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9230 
    [ 2.500,  5.000) = 270444 
    [ 5.000,  7.500) = 4173 
    [ 7.500, 10.000) = 478 
    [10.000, 12.500) = 103 
    [12.500, 15.000) = 24 
    [15.000, 17.500) = 23 
    [17.500, 20.000) = 36 
    [20.000, 22.500) = 153 
    [22.500, 25.000) = 34 
    [25.000, 27.500) = 41 

  Percentiles, ms/op:
      p(0.0000) =      0.563 ms/op
     p(50.0000) =      3.285 ms/op
     p(90.0000) =      3.781 ms/op
     p(95.0000) =      4.166 ms/op
     p(99.0000) =      5.587 ms/op
     p(99.9000) =     16.519 ms/op
     p(99.9900) =     26.182 ms/op
     p(99.9990) =     27.601 ms/op
     p(99.9999) =     27.689 ms/op
    p(100.0000) =     27.689 ms/op


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
# Warmup Iteration   1: 10.280 ±(99.9%) 0.137 ms/op
# Warmup Iteration   2: 3.794 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.574 ±(99.9%) 0.011 ms/op
Iteration   1: 3.498 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.124 ms/op
                 getUser·p0.50:   3.359 ms/op
                 getUser·p0.90:   3.822 ms/op
                 getUser·p0.95:   4.043 ms/op
                 getUser·p0.99:   6.553 ms/op
                 getUser·p0.999:  17.432 ms/op
                 getUser·p0.9999: 21.945 ms/op
                 getUser·p1.00:   22.610 ms/op

Iteration   2: 3.399 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.360 ms/op
                 getUser·p0.50:   3.310 ms/op
                 getUser·p0.90:   3.748 ms/op
                 getUser·p0.95:   3.994 ms/op
                 getUser·p0.99:   5.956 ms/op
                 getUser·p0.999:  18.146 ms/op
                 getUser·p0.9999: 23.192 ms/op
                 getUser·p1.00:   24.183 ms/op

Iteration   3: 3.449 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.520 ms/op
                 getUser·p0.50:   3.404 ms/op
                 getUser·p0.90:   3.879 ms/op
                 getUser·p0.95:   4.219 ms/op
                 getUser·p0.99:   5.988 ms/op
                 getUser·p0.999:  18.656 ms/op
                 getUser·p0.9999: 25.681 ms/op
                 getUser·p1.00:   26.378 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 278175
  mean =      3.448 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7671 
    [ 2.500,  5.000) = 264094 
    [ 5.000,  7.500) = 5145 
    [ 7.500, 10.000) = 759 
    [10.000, 12.500) = 193 
    [12.500, 15.000) = 25 
    [15.000, 17.500) = 6 
    [17.500, 20.000) = 99 
    [20.000, 22.500) = 118 
    [22.500, 25.000) = 49 
    [25.000, 27.500) = 16 

  Percentiles, ms/op:
      p(0.0000) =      1.124 ms/op
     p(50.0000) =      3.367 ms/op
     p(90.0000) =      3.817 ms/op
     p(95.0000) =      4.084 ms/op
     p(99.0000) =      6.087 ms/op
     p(99.9000) =     17.891 ms/op
     p(99.9900) =     23.331 ms/op
     p(99.9990) =     26.222 ms/op
     p(99.9999) =     26.378 ms/op
    p(100.0000) =     26.378 ms/op


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
# Warmup Iteration   1: 10.854 ±(99.9%) 0.132 ms/op
# Warmup Iteration   2: 4.451 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.173 ±(99.9%) 0.013 ms/op
Iteration   1: 4.010 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.620 ms/op
                 listUser·p0.50:   3.908 ms/op
                 listUser·p0.90:   4.309 ms/op
                 listUser·p0.95:   4.506 ms/op
                 listUser·p0.99:   6.627 ms/op
                 listUser·p0.999:  20.241 ms/op
                 listUser·p0.9999: 25.428 ms/op
                 listUser·p1.00:   26.018 ms/op

Iteration   2: 4.073 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.950 ms/op
                 listUser·p0.50:   3.908 ms/op
                 listUser·p0.90:   4.596 ms/op
                 listUser·p0.95:   5.022 ms/op
                 listUser·p0.99:   7.963 ms/op
                 listUser·p0.999:  14.959 ms/op
                 listUser·p0.9999: 18.448 ms/op
                 listUser·p1.00:   18.874 ms/op

Iteration   3: 3.978 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.343 ms/op
                 listUser·p0.50:   3.883 ms/op
                 listUser·p0.90:   4.383 ms/op
                 listUser·p0.95:   4.678 ms/op
                 listUser·p0.99:   7.029 ms/op
                 listUser·p0.999:  14.811 ms/op
                 listUser·p0.9999: 15.073 ms/op
                 listUser·p1.00:   15.876 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 238664
  mean =      4.020 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 28 
    [ 2.500,  5.000) = 230068 
    [ 5.000,  7.500) = 6617 
    [ 7.500, 10.000) = 1210 
    [10.000, 12.500) = 244 
    [12.500, 15.000) = 235 
    [15.000, 17.500) = 117 
    [17.500, 20.000) = 63 
    [20.000, 22.500) = 27 
    [22.500, 25.000) = 38 
    [25.000, 27.500) = 17 

  Percentiles, ms/op:
      p(0.0000) =      1.620 ms/op
     p(50.0000) =      3.895 ms/op
     p(90.0000) =      4.415 ms/op
     p(95.0000) =      4.743 ms/op
     p(99.0000) =      7.111 ms/op
     p(99.9000) =     15.308 ms/op
     p(99.9900) =     24.478 ms/op
     p(99.9990) =     25.887 ms/op
     p(99.9999) =     26.018 ms/op
    p(100.0000) =     26.018 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.233 ± 0.983  ops/ms
ClientPb.existUser                       thrpt       3   9.529 ± 1.716  ops/ms
ClientPb.getUser                         thrpt       3   9.235 ± 2.238  ops/ms
ClientPb.listUser                        thrpt       3   7.957 ± 1.866  ops/ms
ClientPb.createUser                       avgt       3   3.479 ± 1.540   ms/op
ClientPb.existUser                        avgt       3   3.280 ± 1.158   ms/op
ClientPb.getUser                          avgt       3   3.341 ± 0.526   ms/op
ClientPb.listUser                         avgt       3   3.945 ± 1.030   ms/op
ClientPb.createUser                     sample  283515   3.383 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.255           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.342           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.674           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.026           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.816           ms/op
ClientPb.createUser:createUser·p0.999   sample          17.842           ms/op
ClientPb.createUser:createUser·p0.9999  sample          24.138           ms/op
ClientPb.createUser:createUser·p1.00    sample          25.428           ms/op
ClientPb.existUser                      sample  284742   3.369 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.563           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.285           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.781           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.166           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.587           ms/op
ClientPb.existUser:existUser·p0.999     sample          16.519           ms/op
ClientPb.existUser:existUser·p0.9999    sample          26.182           ms/op
ClientPb.existUser:existUser·p1.00      sample          27.689           ms/op
ClientPb.getUser                        sample  278175   3.448 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.124           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.367           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.817           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.084           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.087           ms/op
ClientPb.getUser:getUser·p0.999         sample          17.891           ms/op
ClientPb.getUser:getUser·p0.9999        sample          23.331           ms/op
ClientPb.getUser:getUser·p1.00          sample          26.378           ms/op
ClientPb.listUser                       sample  238664   4.020 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.620           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.895           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.415           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.743           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.111           ms/op
ClientPb.listUser:listUser·p0.999       sample          15.308           ms/op
ClientPb.listUser:listUser·p0.9999      sample          24.478           ms/op
ClientPb.listUser:listUser·p1.00        sample          26.018           ms/op
