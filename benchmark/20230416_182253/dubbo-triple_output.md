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
# Warmup Iteration   1: 1.118 ops/ms
# Warmup Iteration   2: 2.677 ops/ms
# Warmup Iteration   3: 5.325 ops/ms
Iteration   1: 5.409 ops/ms
Iteration   2: 5.691 ops/ms
Iteration   3: 5.628 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.576 ±(99.9%) 2.704 ops/ms [Average]
  (min, avg, max) = (5.409, 5.576, 5.691), stdev = 0.148
  CI (99.9%): [2.872, 8.281] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:14
# Fork: 1 of 1
# Warmup Iteration   1: 1.678 ops/ms
# Warmup Iteration   2: 4.613 ops/ms
# Warmup Iteration   3: 5.866 ops/ms
Iteration   1: 5.991 ops/ms
Iteration   2: 6.038 ops/ms
Iteration   3: 5.921 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.983 ±(99.9%) 1.077 ops/ms [Average]
  (min, avg, max) = (5.921, 5.983, 6.038), stdev = 0.059
  CI (99.9%): [4.906, 7.060] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:07
# Fork: 1 of 1
# Warmup Iteration   1: 1.728 ops/ms
# Warmup Iteration   2: 4.616 ops/ms
# Warmup Iteration   3: 5.418 ops/ms
Iteration   1: 5.842 ops/ms
Iteration   2: 5.510 ops/ms
Iteration   3: 5.787 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.713 ±(99.9%) 3.240 ops/ms [Average]
  (min, avg, max) = (5.510, 5.713, 5.842), stdev = 0.178
  CI (99.9%): [2.473, 8.953] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:57
# Fork: 1 of 1
# Warmup Iteration   1: 1.489 ops/ms
# Warmup Iteration   2: 3.799 ops/ms
# Warmup Iteration   3: 4.916 ops/ms
Iteration   1: 4.911 ops/ms
Iteration   2: 4.933 ops/ms
Iteration   3: 4.870 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.905 ±(99.9%) 0.589 ops/ms [Average]
  (min, avg, max) = (4.870, 4.905, 4.933), stdev = 0.032
  CI (99.9%): [4.316, 5.493] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:52
# Fork: 1 of 1
# Warmup Iteration   1: 18.806 ±(99.9%) 0.187 ms/op
# Warmup Iteration   2: 6.778 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 6.016 ±(99.9%) 0.009 ms/op
Iteration   1: 5.832 ±(99.9%) 0.008 ms/op
Iteration   2: 5.667 ±(99.9%) 0.014 ms/op
Iteration   3: 5.609 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.703 ±(99.9%) 2.112 ms/op [Average]
  (min, avg, max) = (5.609, 5.703, 5.832), stdev = 0.116
  CI (99.9%): [3.590, 7.815] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:44
# Fork: 1 of 1
# Warmup Iteration   1: 17.457 ±(99.9%) 0.101 ms/op
# Warmup Iteration   2: 6.313 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 5.638 ±(99.9%) 0.009 ms/op
Iteration   1: 5.349 ±(99.9%) 0.011 ms/op
Iteration   2: 5.487 ±(99.9%) 0.006 ms/op
Iteration   3: 5.576 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.471 ±(99.9%) 2.089 ms/op [Average]
  (min, avg, max) = (5.349, 5.471, 5.576), stdev = 0.114
  CI (99.9%): [3.382, 7.559] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:38
# Fork: 1 of 1
# Warmup Iteration   1: 18.319 ±(99.9%) 0.082 ms/op
# Warmup Iteration   2: 6.789 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 5.746 ±(99.9%) 0.010 ms/op
Iteration   1: 5.730 ±(99.9%) 0.012 ms/op
Iteration   2: 5.753 ±(99.9%) 0.007 ms/op
Iteration   3: 5.608 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.697 ±(99.9%) 1.416 ms/op [Average]
  (min, avg, max) = (5.608, 5.697, 5.753), stdev = 0.078
  CI (99.9%): [4.281, 7.113] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:32
# Fork: 1 of 1
# Warmup Iteration   1: 20.279 ±(99.9%) 0.076 ms/op
# Warmup Iteration   2: 8.004 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 6.489 ±(99.9%) 0.015 ms/op
Iteration   1: 6.561 ±(99.9%) 0.020 ms/op
Iteration   2: 6.482 ±(99.9%) 0.013 ms/op
Iteration   3: 6.415 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.486 ±(99.9%) 1.337 ms/op [Average]
  (min, avg, max) = (6.415, 6.486, 6.561), stdev = 0.073
  CI (99.9%): [5.149, 7.823] (assumes normal distribution)


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
# Warmup Iteration   1: 16.555 ±(99.9%) 0.262 ms/op
# Warmup Iteration   2: 8.462 ±(99.9%) 0.065 ms/op
# Warmup Iteration   3: 6.448 ±(99.9%) 0.032 ms/op
Iteration   1: 5.638 ±(99.9%) 0.020 ms/op
                 createUser·p0.00:   2.449 ms/op
                 createUser·p0.50:   5.399 ms/op
                 createUser·p0.90:   6.816 ms/op
                 createUser·p0.95:   7.643 ms/op
                 createUser·p0.99:   10.699 ms/op
                 createUser·p0.999:  26.878 ms/op
                 createUser·p0.9999: 29.983 ms/op
                 createUser·p1.00:   30.671 ms/op

Iteration   2: 5.594 ±(99.9%) 0.019 ms/op
                 createUser·p0.00:   1.872 ms/op
                 createUser·p0.50:   5.407 ms/op
                 createUser·p0.90:   6.693 ms/op
                 createUser·p0.95:   7.307 ms/op
                 createUser·p0.99:   9.603 ms/op
                 createUser·p0.999:  24.741 ms/op
                 createUser·p0.9999: 34.755 ms/op
                 createUser·p1.00:   36.897 ms/op

Iteration   3: 5.628 ±(99.9%) 0.020 ms/op
                 createUser·p0.00:   1.214 ms/op
                 createUser·p0.50:   5.399 ms/op
                 createUser·p0.90:   6.799 ms/op
                 createUser·p0.95:   7.479 ms/op
                 createUser·p0.99:   10.240 ms/op
                 createUser·p0.999:  28.606 ms/op
                 createUser·p0.9999: 31.588 ms/op
                 createUser·p1.00:   32.375 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 170751
  mean =      5.620 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 20 
    [ 2.500,  5.000) = 45235 
    [ 5.000,  7.500) = 117266 
    [ 7.500, 10.000) = 6302 
    [10.000, 12.500) = 1236 
    [12.500, 15.000) = 367 
    [15.000, 17.500) = 89 
    [17.500, 20.000) = 43 
    [20.000, 22.500) = 5 
    [22.500, 25.000) = 5 
    [25.000, 27.500) = 32 
    [27.500, 30.000) = 83 
    [30.000, 32.500) = 46 
    [32.500, 35.000) = 17 
    [35.000, 37.500) = 5 

  Percentiles, ms/op:
      p(0.0000) =      1.214 ms/op
     p(50.0000) =      5.399 ms/op
     p(90.0000) =      6.775 ms/op
     p(95.0000) =      7.455 ms/op
     p(99.0000) =     10.297 ms/op
     p(99.9000) =     26.820 ms/op
     p(99.9900) =     33.828 ms/op
     p(99.9990) =     36.804 ms/op
     p(99.9999) =     36.897 ms/op
    p(100.0000) =     36.897 ms/op


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
# Warmup Iteration   1: 17.100 ±(99.9%) 0.268 ms/op
# Warmup Iteration   2: 6.205 ±(99.9%) 0.035 ms/op
# Warmup Iteration   3: 5.414 ±(99.9%) 0.020 ms/op
Iteration   1: 5.418 ±(99.9%) 0.019 ms/op
                 existUser·p0.00:   2.273 ms/op
                 existUser·p0.50:   5.112 ms/op
                 existUser·p0.90:   6.791 ms/op
                 existUser·p0.95:   7.897 ms/op
                 existUser·p0.99:   10.682 ms/op
                 existUser·p0.999:  22.577 ms/op
                 existUser·p0.9999: 26.575 ms/op
                 existUser·p1.00:   27.656 ms/op

Iteration   2: 5.192 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   2.154 ms/op
                 existUser·p0.50:   4.948 ms/op
                 existUser·p0.90:   6.300 ms/op
                 existUser·p0.95:   6.980 ms/op
                 existUser·p0.99:   9.437 ms/op
                 existUser·p0.999:  14.711 ms/op
                 existUser·p0.9999: 34.114 ms/op
                 existUser·p1.00:   35.193 ms/op

Iteration   3: 5.643 ±(99.9%) 0.022 ms/op
                 existUser·p0.00:   2.073 ms/op
                 existUser·p0.50:   5.308 ms/op
                 existUser·p0.90:   7.012 ms/op
                 existUser·p0.95:   7.995 ms/op
                 existUser·p0.99:   11.190 ms/op
                 existUser·p0.999:  29.326 ms/op
                 existUser·p0.9999: 33.838 ms/op
                 existUser·p1.00:   34.734 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 177230
  mean =      5.411 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 29 
    [ 2.500,  5.000) = 77988 
    [ 5.000,  7.500) = 89450 
    [ 7.500, 10.000) = 7457 
    [10.000, 12.500) = 1612 
    [12.500, 15.000) = 390 
    [15.000, 17.500) = 79 
    [17.500, 20.000) = 37 
    [20.000, 22.500) = 28 
    [22.500, 25.000) = 41 
    [25.000, 27.500) = 21 
    [27.500, 30.000) = 15 
    [30.000, 32.500) = 44 
    [32.500, 35.000) = 38 
    [35.000, 37.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      2.073 ms/op
     p(50.0000) =      5.112 ms/op
     p(90.0000) =      6.685 ms/op
     p(95.0000) =      7.651 ms/op
     p(99.0000) =     10.519 ms/op
     p(99.9000) =     21.234 ms/op
     p(99.9900) =     33.704 ms/op
     p(99.9990) =     34.990 ms/op
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
# Warmup Iteration   1: 17.117 ±(99.9%) 0.265 ms/op
# Warmup Iteration   2: 6.737 ±(99.9%) 0.041 ms/op
# Warmup Iteration   3: 5.741 ±(99.9%) 0.020 ms/op
Iteration   1: 5.889 ±(99.9%) 0.025 ms/op
                 getUser·p0.00:   0.454 ms/op
                 getUser·p0.50:   5.489 ms/op
                 getUser·p0.90:   7.348 ms/op
                 getUser·p0.95:   8.798 ms/op
                 getUser·p0.99:   13.025 ms/op
                 getUser·p0.999:  24.705 ms/op
                 getUser·p0.9999: 36.934 ms/op
                 getUser·p1.00:   37.224 ms/op

Iteration   2: 5.742 ±(99.9%) 0.023 ms/op
                 getUser·p0.00:   2.417 ms/op
                 getUser·p0.50:   5.390 ms/op
                 getUser·p0.90:   6.898 ms/op
                 getUser·p0.95:   8.520 ms/op
                 getUser·p0.99:   11.518 ms/op
                 getUser·p0.999:  27.306 ms/op
                 getUser·p0.9999: 30.540 ms/op
                 getUser·p1.00:   30.835 ms/op

Iteration   3: 5.660 ±(99.9%) 0.021 ms/op
                 getUser·p0.00:   2.695 ms/op
                 getUser·p0.50:   5.399 ms/op
                 getUser·p0.90:   6.767 ms/op
                 getUser·p0.95:   7.954 ms/op
                 getUser·p0.99:   10.555 ms/op
                 getUser·p0.999:  29.329 ms/op
                 getUser·p0.9999: 33.840 ms/op
                 getUser·p1.00:   35.258 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 166449
  mean =      5.762 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8 
    [ 2.500,  5.000) = 42535 
    [ 5.000,  7.500) = 111486 
    [ 7.500, 10.000) = 8750 
    [10.000, 12.500) = 2385 
    [12.500, 15.000) = 743 
    [15.000, 17.500) = 231 
    [17.500, 20.000) = 59 
    [20.000, 22.500) = 21 
    [22.500, 25.000) = 35 
    [25.000, 27.500) = 45 
    [27.500, 30.000) = 57 
    [30.000, 32.500) = 60 
    [32.500, 35.000) = 12 
    [35.000, 37.500) = 22 

  Percentiles, ms/op:
      p(0.0000) =      0.454 ms/op
     p(50.0000) =      5.423 ms/op
     p(90.0000) =      7.004 ms/op
     p(95.0000) =      8.380 ms/op
     p(99.0000) =     11.764 ms/op
     p(99.9000) =     27.052 ms/op
     p(99.9900) =     35.918 ms/op
     p(99.9990) =     37.224 ms/op
     p(99.9999) =     37.224 ms/op
    p(100.0000) =     37.224 ms/op


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
# Warmup Iteration   1: 20.416 ±(99.9%) 0.344 ms/op
# Warmup Iteration   2: 7.745 ±(99.9%) 0.052 ms/op
# Warmup Iteration   3: 7.076 ±(99.9%) 0.033 ms/op
Iteration   1: 6.434 ±(99.9%) 0.024 ms/op
                 listUser·p0.00:   3.084 ms/op
                 listUser·p0.50:   6.103 ms/op
                 listUser·p0.90:   7.537 ms/op
                 listUser·p0.95:   8.815 ms/op
                 listUser·p0.99:   12.829 ms/op
                 listUser·p0.999:  27.329 ms/op
                 listUser·p0.9999: 29.950 ms/op
                 listUser·p1.00:   30.605 ms/op

Iteration   2: 6.504 ±(99.9%) 0.025 ms/op
                 listUser·p0.00:   2.707 ms/op
                 listUser·p0.50:   6.218 ms/op
                 listUser·p0.90:   7.627 ms/op
                 listUser·p0.95:   8.454 ms/op
                 listUser·p0.99:   11.844 ms/op
                 listUser·p0.999:  30.507 ms/op
                 listUser·p0.9999: 33.691 ms/op
                 listUser·p1.00:   34.079 ms/op

Iteration   3: 6.391 ±(99.9%) 0.022 ms/op
                 listUser·p0.00:   2.826 ms/op
                 listUser·p0.50:   6.103 ms/op
                 listUser·p0.90:   7.422 ms/op
                 listUser·p0.95:   8.454 ms/op
                 listUser·p0.99:   12.206 ms/op
                 listUser·p0.999:  24.183 ms/op
                 listUser·p0.9999: 30.044 ms/op
                 listUser·p1.00:   31.523 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 148963
  mean =      6.443 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 4486 
    [ 5.000,  7.500) = 128963 
    [ 7.500, 10.000) = 11519 
    [10.000, 12.500) = 2583 
    [12.500, 15.000) = 754 
    [15.000, 17.500) = 246 
    [17.500, 20.000) = 62 
    [20.000, 22.500) = 41 
    [22.500, 25.000) = 70 
    [25.000, 27.500) = 83 
    [27.500, 30.000) = 91 
    [30.000, 32.500) = 55 
    [32.500, 35.000) = 10 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.707 ms/op
     p(50.0000) =      6.136 ms/op
     p(90.0000) =      7.545 ms/op
     p(95.0000) =      8.552 ms/op
     p(99.0000) =     12.321 ms/op
     p(99.9000) =     27.690 ms/op
     p(99.9900) =     32.251 ms/op
     p(99.9990) =     33.950 ms/op
     p(99.9999) =     34.079 ms/op
    p(100.0000) =     34.079 ms/op


# Run complete. Total time: 00:13:18

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.576 ± 2.704  ops/ms
ClientPb.existUser                       thrpt       3   5.983 ± 1.077  ops/ms
ClientPb.getUser                         thrpt       3   5.713 ± 3.240  ops/ms
ClientPb.listUser                        thrpt       3   4.905 ± 0.589  ops/ms
ClientPb.createUser                       avgt       3   5.703 ± 2.112   ms/op
ClientPb.existUser                        avgt       3   5.471 ± 2.089   ms/op
ClientPb.getUser                          avgt       3   5.697 ± 1.416   ms/op
ClientPb.listUser                         avgt       3   6.486 ± 1.337   ms/op
ClientPb.createUser                     sample  170751   5.620 ± 0.011   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.214           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.399           ms/op
ClientPb.createUser:createUser·p0.90    sample           6.775           ms/op
ClientPb.createUser:createUser·p0.95    sample           7.455           ms/op
ClientPb.createUser:createUser·p0.99    sample          10.297           ms/op
ClientPb.createUser:createUser·p0.999   sample          26.820           ms/op
ClientPb.createUser:createUser·p0.9999  sample          33.828           ms/op
ClientPb.createUser:createUser·p1.00    sample          36.897           ms/op
ClientPb.existUser                      sample  177230   5.411 ± 0.011   ms/op
ClientPb.existUser:existUser·p0.00      sample           2.073           ms/op
ClientPb.existUser:existUser·p0.50      sample           5.112           ms/op
ClientPb.existUser:existUser·p0.90      sample           6.685           ms/op
ClientPb.existUser:existUser·p0.95      sample           7.651           ms/op
ClientPb.existUser:existUser·p0.99      sample          10.519           ms/op
ClientPb.existUser:existUser·p0.999     sample          21.234           ms/op
ClientPb.existUser:existUser·p0.9999    sample          33.704           ms/op
ClientPb.existUser:existUser·p1.00      sample          35.193           ms/op
ClientPb.getUser                        sample  166449   5.762 ± 0.013   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.454           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.423           ms/op
ClientPb.getUser:getUser·p0.90          sample           7.004           ms/op
ClientPb.getUser:getUser·p0.95          sample           8.380           ms/op
ClientPb.getUser:getUser·p0.99          sample          11.764           ms/op
ClientPb.getUser:getUser·p0.999         sample          27.052           ms/op
ClientPb.getUser:getUser·p0.9999        sample          35.918           ms/op
ClientPb.getUser:getUser·p1.00          sample          37.224           ms/op
ClientPb.listUser                       sample  148963   6.443 ± 0.014   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.707           ms/op
ClientPb.listUser:listUser·p0.50        sample           6.136           ms/op
ClientPb.listUser:listUser·p0.90        sample           7.545           ms/op
ClientPb.listUser:listUser·p0.95        sample           8.552           ms/op
ClientPb.listUser:listUser·p0.99        sample          12.321           ms/op
ClientPb.listUser:listUser·p0.999       sample          27.690           ms/op
ClientPb.listUser:listUser·p0.9999      sample          32.251           ms/op
ClientPb.listUser:listUser·p1.00        sample          34.079           ms/op
