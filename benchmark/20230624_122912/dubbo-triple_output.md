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
# Warmup Iteration   1: 2.266 ops/ms
# Warmup Iteration   2: 5.990 ops/ms
# Warmup Iteration   3: 8.771 ops/ms
Iteration   1: 9.515 ops/ms
Iteration   2: 9.421 ops/ms
Iteration   3: 9.518 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.485 ±(99.9%) 1.005 ops/ms [Average]
  (min, avg, max) = (9.421, 9.485, 9.518), stdev = 0.055
  CI (99.9%): [8.480, 10.490] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:07
# Fork: 1 of 1
# Warmup Iteration   1: 3.160 ops/ms
# Warmup Iteration   2: 8.569 ops/ms
# Warmup Iteration   3: 9.433 ops/ms
Iteration   1: 10.072 ops/ms
Iteration   2: 9.142 ops/ms
Iteration   3: 10.062 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.759 ±(99.9%) 9.747 ops/ms [Average]
  (min, avg, max) = (9.142, 9.759, 10.072), stdev = 0.534
  CI (99.9%): [0.012, 19.505] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:55
# Fork: 1 of 1
# Warmup Iteration   1: 3.030 ops/ms
# Warmup Iteration   2: 8.368 ops/ms
# Warmup Iteration   3: 9.185 ops/ms
Iteration   1: 9.477 ops/ms
Iteration   2: 9.623 ops/ms
Iteration   3: 8.967 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.355 ±(99.9%) 6.279 ops/ms [Average]
  (min, avg, max) = (8.967, 9.355, 9.623), stdev = 0.344
  CI (99.9%): [3.076, 15.635] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 2.924 ops/ms
# Warmup Iteration   2: 7.490 ops/ms
# Warmup Iteration   3: 8.098 ops/ms
Iteration   1: 8.018 ops/ms
Iteration   2: 8.221 ops/ms
Iteration   3: 8.269 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.169 ±(99.9%) 2.433 ops/ms [Average]
  (min, avg, max) = (8.018, 8.169, 8.269), stdev = 0.133
  CI (99.9%): [5.736, 10.603] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 9.740 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 3.931 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.540 ±(99.9%) 0.005 ms/op
Iteration   1: 3.296 ±(99.9%) 0.010 ms/op
Iteration   2: 3.318 ±(99.9%) 0.012 ms/op
Iteration   3: 3.322 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.312 ±(99.9%) 0.257 ms/op [Average]
  (min, avg, max) = (3.296, 3.312, 3.322), stdev = 0.014
  CI (99.9%): [3.055, 3.569] (assumes normal distribution)


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
# Warmup Iteration   1: 8.349 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 3.509 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.339 ±(99.9%) 0.005 ms/op
Iteration   1: 3.172 ±(99.9%) 0.009 ms/op
Iteration   2: 3.356 ±(99.9%) 0.003 ms/op
Iteration   3: 3.264 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.264 ±(99.9%) 1.682 ms/op [Average]
  (min, avg, max) = (3.172, 3.264, 3.356), stdev = 0.092
  CI (99.9%): [1.582, 4.946] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 8.767 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 3.578 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.456 ±(99.9%) 0.003 ms/op
Iteration   1: 3.506 ±(99.9%) 0.004 ms/op
Iteration   2: 3.325 ±(99.9%) 0.008 ms/op
Iteration   3: 3.448 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.426 ±(99.9%) 1.682 ms/op [Average]
  (min, avg, max) = (3.325, 3.426, 3.506), stdev = 0.092
  CI (99.9%): [1.744, 5.109] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 11.140 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 4.268 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.072 ±(99.9%) 0.008 ms/op
Iteration   1: 3.964 ±(99.9%) 0.007 ms/op
Iteration   2: 3.958 ±(99.9%) 0.006 ms/op
Iteration   3: 3.948 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.957 ±(99.9%) 0.139 ms/op [Average]
  (min, avg, max) = (3.948, 3.957, 3.964), stdev = 0.008
  CI (99.9%): [3.817, 4.096] (assumes normal distribution)


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
# Warmup Iteration   1: 9.157 ±(99.9%) 0.105 ms/op
# Warmup Iteration   2: 4.613 ±(99.9%) 0.025 ms/op
# Warmup Iteration   3: 3.415 ±(99.9%) 0.010 ms/op
Iteration   1: 3.349 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.348 ms/op
                 createUser·p0.50:   3.248 ms/op
                 createUser·p0.90:   3.760 ms/op
                 createUser·p0.95:   4.145 ms/op
                 createUser·p0.99:   6.128 ms/op
                 createUser·p0.999:  19.773 ms/op
                 createUser·p0.9999: 23.896 ms/op
                 createUser·p1.00:   25.362 ms/op

Iteration   2: 3.400 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.331 ms/op
                 createUser·p0.50:   3.351 ms/op
                 createUser·p0.90:   3.801 ms/op
                 createUser·p0.95:   4.133 ms/op
                 createUser·p0.99:   5.644 ms/op
                 createUser·p0.999:  20.346 ms/op
                 createUser·p0.9999: 24.516 ms/op
                 createUser·p1.00:   25.657 ms/op

Iteration   3: 3.358 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.243 ms/op
                 createUser·p0.50:   3.248 ms/op
                 createUser·p0.90:   3.830 ms/op
                 createUser·p0.95:   4.092 ms/op
                 createUser·p0.99:   5.489 ms/op
                 createUser·p0.999:  15.840 ms/op
                 createUser·p0.9999: 25.083 ms/op
                 createUser·p1.00:   26.116 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 284825
  mean =      3.369 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10739 
    [ 2.500,  5.000) = 268475 
    [ 5.000,  7.500) = 4421 
    [ 7.500, 10.000) = 611 
    [10.000, 12.500) = 223 
    [12.500, 15.000) = 58 
    [15.000, 17.500) = 31 
    [17.500, 20.000) = 43 
    [20.000, 22.500) = 115 
    [22.500, 25.000) = 92 
    [25.000, 27.500) = 17 

  Percentiles, ms/op:
      p(0.0000) =      1.243 ms/op
     p(50.0000) =      3.265 ms/op
     p(90.0000) =      3.805 ms/op
     p(95.0000) =      4.116 ms/op
     p(99.0000) =      5.710 ms/op
     p(99.9000) =     16.166 ms/op
     p(99.9900) =     24.626 ms/op
     p(99.9990) =     26.028 ms/op
     p(99.9999) =     26.116 ms/op
    p(100.0000) =     26.116 ms/op


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
# Warmup Iteration   1: 7.775 ±(99.9%) 0.105 ms/op
# Warmup Iteration   2: 3.488 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.298 ±(99.9%) 0.008 ms/op
Iteration   1: 3.323 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.651 ms/op
                 existUser·p0.50:   3.277 ms/op
                 existUser·p0.90:   3.543 ms/op
                 existUser·p0.95:   4.051 ms/op
                 existUser·p0.99:   5.759 ms/op
                 existUser·p0.999:  19.699 ms/op
                 existUser·p0.9999: 22.348 ms/op
                 existUser·p1.00:   22.643 ms/op

Iteration   2: 3.235 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.126 ms/op
                 existUser·p0.50:   3.142 ms/op
                 existUser·p0.90:   3.637 ms/op
                 existUser·p0.95:   3.838 ms/op
                 existUser·p0.99:   4.588 ms/op
                 existUser·p0.999:  9.447 ms/op
                 existUser·p0.9999: 24.141 ms/op
                 existUser·p1.00:   24.871 ms/op

Iteration   3: 3.440 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   0.768 ms/op
                 existUser·p0.50:   3.224 ms/op
                 existUser·p0.90:   4.182 ms/op
                 existUser·p0.95:   4.661 ms/op
                 existUser·p0.99:   6.767 ms/op
                 existUser·p0.999:  18.907 ms/op
                 existUser·p0.9999: 25.910 ms/op
                 existUser·p1.00:   26.968 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 287910
  mean =      3.331 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10399 
    [ 2.500,  5.000) = 272164 
    [ 5.000,  7.500) = 4076 
    [ 7.500, 10.000) = 745 
    [10.000, 12.500) = 139 
    [12.500, 15.000) = 92 
    [15.000, 17.500) = 17 
    [17.500, 20.000) = 47 
    [20.000, 22.500) = 152 
    [22.500, 25.000) = 64 
    [25.000, 27.500) = 15 

  Percentiles, ms/op:
      p(0.0000) =      0.768 ms/op
     p(50.0000) =      3.236 ms/op
     p(90.0000) =      3.723 ms/op
     p(95.0000) =      4.243 ms/op
     p(99.0000) =      5.825 ms/op
     p(99.9000) =     15.811 ms/op
     p(99.9900) =     24.550 ms/op
     p(99.9990) =     26.554 ms/op
     p(99.9999) =     26.968 ms/op
    p(100.0000) =     26.968 ms/op


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
# Warmup Iteration   1: 10.631 ±(99.9%) 0.128 ms/op
# Warmup Iteration   2: 3.845 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.534 ±(99.9%) 0.011 ms/op
Iteration   1: 3.426 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.350 ms/op
                 getUser·p0.50:   3.269 ms/op
                 getUser·p0.90:   3.891 ms/op
                 getUser·p0.95:   4.612 ms/op
                 getUser·p0.99:   7.012 ms/op
                 getUser·p0.999:  19.301 ms/op
                 getUser·p0.9999: 23.702 ms/op
                 getUser·p1.00:   25.657 ms/op

Iteration   2: 3.414 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.972 ms/op
                 getUser·p0.50:   3.326 ms/op
                 getUser·p0.90:   3.764 ms/op
                 getUser·p0.95:   3.928 ms/op
                 getUser·p0.99:   5.614 ms/op
                 getUser·p0.999:  21.376 ms/op
                 getUser·p0.9999: 23.941 ms/op
                 getUser·p1.00:   25.133 ms/op

Iteration   3: 3.397 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.671 ms/op
                 getUser·p0.50:   3.285 ms/op
                 getUser·p0.90:   3.768 ms/op
                 getUser·p0.95:   4.211 ms/op
                 getUser·p0.99:   6.365 ms/op
                 getUser·p0.999:  17.193 ms/op
                 getUser·p0.9999: 24.216 ms/op
                 getUser·p1.00:   24.609 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 281092
  mean =      3.412 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11730 
    [ 2.500,  5.000) = 261053 
    [ 5.000,  7.500) = 6990 
    [ 7.500, 10.000) = 774 
    [10.000, 12.500) = 177 
    [12.500, 15.000) = 25 
    [15.000, 17.500) = 46 
    [17.500, 20.000) = 78 
    [20.000, 22.500) = 95 
    [22.500, 25.000) = 116 
    [25.000, 27.500) = 8 

  Percentiles, ms/op:
      p(0.0000) =      1.350 ms/op
     p(50.0000) =      3.289 ms/op
     p(90.0000) =      3.793 ms/op
     p(95.0000) =      4.157 ms/op
     p(99.0000) =      6.472 ms/op
     p(99.9000) =     17.787 ms/op
     p(99.9900) =     24.015 ms/op
     p(99.9990) =     25.506 ms/op
     p(99.9999) =     25.657 ms/op
    p(100.0000) =     25.657 ms/op


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
# Warmup Iteration   1: 10.428 ±(99.9%) 0.155 ms/op
# Warmup Iteration   2: 4.230 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.956 ±(99.9%) 0.011 ms/op
Iteration   1: 3.858 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.370 ms/op
                 listUser·p0.50:   3.756 ms/op
                 listUser·p0.90:   4.129 ms/op
                 listUser·p0.95:   4.448 ms/op
                 listUser·p0.99:   6.980 ms/op
                 listUser·p0.999:  19.303 ms/op
                 listUser·p0.9999: 29.378 ms/op
                 listUser·p1.00:   31.195 ms/op

Iteration   2: 3.829 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.290 ms/op
                 listUser·p0.50:   3.813 ms/op
                 listUser·p0.90:   3.965 ms/op
                 listUser·p0.95:   4.162 ms/op
                 listUser·p0.99:   6.373 ms/op
                 listUser·p0.999:  15.663 ms/op
                 listUser·p0.9999: 19.759 ms/op
                 listUser·p1.00:   20.709 ms/op

Iteration   3: 3.903 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.372 ms/op
                 listUser·p0.50:   3.764 ms/op
                 listUser·p0.90:   4.260 ms/op
                 listUser·p0.95:   4.424 ms/op
                 listUser·p0.99:   7.012 ms/op
                 listUser·p0.999:  16.384 ms/op
                 listUser·p0.9999: 18.573 ms/op
                 listUser·p1.00:   19.169 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 248354
  mean =      3.863 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 59 
    [ 2.500,  5.000) = 242617 
    [ 5.000,  7.500) = 4150 
    [ 7.500, 10.000) = 935 
    [10.000, 12.500) = 114 
    [12.500, 15.000) = 74 
    [15.000, 17.500) = 219 
    [17.500, 20.000) = 114 
    [20.000, 22.500) = 12 
    [22.500, 25.000) = 24 
    [25.000, 27.500) = 5 
    [27.500, 30.000) = 24 
    [30.000, 32.500) = 7 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.370 ms/op
     p(50.0000) =      3.789 ms/op
     p(90.0000) =      4.153 ms/op
     p(95.0000) =      4.407 ms/op
     p(99.0000) =      6.808 ms/op
     p(99.9000) =     16.530 ms/op
     p(99.9900) =     28.601 ms/op
     p(99.9990) =     30.760 ms/op
     p(99.9999) =     31.195 ms/op
    p(100.0000) =     31.195 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.485 ± 1.005  ops/ms
ClientPb.existUser                       thrpt       3   9.759 ± 9.747  ops/ms
ClientPb.getUser                         thrpt       3   9.355 ± 6.279  ops/ms
ClientPb.listUser                        thrpt       3   8.169 ± 2.433  ops/ms
ClientPb.createUser                       avgt       3   3.312 ± 0.257   ms/op
ClientPb.existUser                        avgt       3   3.264 ± 1.682   ms/op
ClientPb.getUser                          avgt       3   3.426 ± 1.682   ms/op
ClientPb.listUser                         avgt       3   3.957 ± 0.139   ms/op
ClientPb.createUser                     sample  284825   3.369 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.243           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.265           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.805           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.116           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.710           ms/op
ClientPb.createUser:createUser·p0.999   sample          16.166           ms/op
ClientPb.createUser:createUser·p0.9999  sample          24.626           ms/op
ClientPb.createUser:createUser·p1.00    sample          26.116           ms/op
ClientPb.existUser                      sample  287910   3.331 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.768           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.236           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.723           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.243           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.825           ms/op
ClientPb.existUser:existUser·p0.999     sample          15.811           ms/op
ClientPb.existUser:existUser·p0.9999    sample          24.550           ms/op
ClientPb.existUser:existUser·p1.00      sample          26.968           ms/op
ClientPb.getUser                        sample  281092   3.412 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.350           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.289           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.793           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.157           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.472           ms/op
ClientPb.getUser:getUser·p0.999         sample          17.787           ms/op
ClientPb.getUser:getUser·p0.9999        sample          24.015           ms/op
ClientPb.getUser:getUser·p1.00          sample          25.657           ms/op
ClientPb.listUser                       sample  248354   3.863 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.370           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.789           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.153           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.407           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.808           ms/op
ClientPb.listUser:listUser·p0.999       sample          16.530           ms/op
ClientPb.listUser:listUser·p0.9999      sample          28.601           ms/op
ClientPb.listUser:listUser·p1.00        sample          31.195           ms/op
