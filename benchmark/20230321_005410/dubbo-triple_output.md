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
# Warmup Iteration   1: 1.899 ops/ms
# Warmup Iteration   2: 4.391 ops/ms
# Warmup Iteration   3: 7.762 ops/ms
Iteration   1: 8.296 ops/ms
Iteration   2: 8.915 ops/ms
Iteration   3: 8.834 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  8.682 ±(99.9%) 6.143 ops/ms [Average]
  (min, avg, max) = (8.296, 8.682, 8.915), stdev = 0.337
  CI (99.9%): [2.539, 14.824] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.577 ops/ms
# Warmup Iteration   2: 7.312 ops/ms
# Warmup Iteration   3: 8.680 ops/ms
Iteration   1: 8.896 ops/ms
Iteration   2: 9.027 ops/ms
Iteration   3: 9.027 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.983 ±(99.9%) 1.383 ops/ms [Average]
  (min, avg, max) = (8.896, 8.983, 9.027), stdev = 0.076
  CI (99.9%): [7.600, 10.367] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:54
# Fork: 1 of 1
# Warmup Iteration   1: 2.285 ops/ms
# Warmup Iteration   2: 7.397 ops/ms
# Warmup Iteration   3: 8.616 ops/ms
Iteration   1: 8.463 ops/ms
Iteration   2: 8.572 ops/ms
Iteration   3: 8.655 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  8.563 ±(99.9%) 1.752 ops/ms [Average]
  (min, avg, max) = (8.463, 8.563, 8.655), stdev = 0.096
  CI (99.9%): [6.811, 10.316] (assumes normal distribution)


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
# Warmup Iteration   1: 2.475 ops/ms
# Warmup Iteration   2: 6.677 ops/ms
# Warmup Iteration   3: 7.235 ops/ms
Iteration   1: 7.413 ops/ms
Iteration   2: 7.285 ops/ms
Iteration   3: 7.486 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.395 ±(99.9%) 1.855 ops/ms [Average]
  (min, avg, max) = (7.285, 7.395, 7.486), stdev = 0.102
  CI (99.9%): [5.540, 9.250] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:47
# Fork: 1 of 1
# Warmup Iteration   1: 11.537 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 4.178 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.803 ±(99.9%) 0.007 ms/op
Iteration   1: 3.764 ±(99.9%) 0.008 ms/op
Iteration   2: 3.710 ±(99.9%) 0.009 ms/op
Iteration   3: 3.629 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.701 ±(99.9%) 1.244 ms/op [Average]
  (min, avg, max) = (3.629, 3.701, 3.764), stdev = 0.068
  CI (99.9%): [2.457, 4.945] (assumes normal distribution)


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
# Warmup Iteration   1: 10.418 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.936 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.540 ±(99.9%) 0.014 ms/op
Iteration   1: 3.595 ±(99.9%) 0.006 ms/op
Iteration   2: 3.476 ±(99.9%) 0.008 ms/op
Iteration   3: 3.628 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.566 ±(99.9%) 1.460 ms/op [Average]
  (min, avg, max) = (3.476, 3.566, 3.628), stdev = 0.080
  CI (99.9%): [2.106, 5.027] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:36
# Fork: 1 of 1
# Warmup Iteration   1: 12.369 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 4.258 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.718 ±(99.9%) 0.010 ms/op
Iteration   1: 3.615 ±(99.9%) 0.005 ms/op
Iteration   2: 3.739 ±(99.9%) 0.008 ms/op
Iteration   3: 3.754 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.703 ±(99.9%) 1.394 ms/op [Average]
  (min, avg, max) = (3.615, 3.703, 3.754), stdev = 0.076
  CI (99.9%): [2.309, 5.097] (assumes normal distribution)


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
# Warmup Iteration   1: 13.473 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 4.959 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.381 ±(99.9%) 0.010 ms/op
Iteration   1: 4.390 ±(99.9%) 0.014 ms/op
Iteration   2: 4.415 ±(99.9%) 0.011 ms/op
Iteration   3: 4.379 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.395 ±(99.9%) 0.342 ms/op [Average]
  (min, avg, max) = (4.379, 4.395, 4.415), stdev = 0.019
  CI (99.9%): [4.053, 4.737] (assumes normal distribution)


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
# Warmup Iteration   1: 11.628 ±(99.9%) 0.146 ms/op
# Warmup Iteration   2: 4.394 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 4.065 ±(99.9%) 0.015 ms/op
Iteration   1: 3.656 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.661 ms/op
                 createUser·p0.50:   3.547 ms/op
                 createUser·p0.90:   4.194 ms/op
                 createUser·p0.95:   4.604 ms/op
                 createUser·p0.99:   6.521 ms/op
                 createUser·p0.999:  12.770 ms/op
                 createUser·p0.9999: 23.691 ms/op
                 createUser·p1.00:   24.117 ms/op

Iteration   2: 3.753 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.585 ms/op
                 createUser·p0.50:   3.629 ms/op
                 createUser·p0.90:   4.186 ms/op
                 createUser·p0.95:   4.850 ms/op
                 createUser·p0.99:   8.012 ms/op
                 createUser·p0.999:  24.605 ms/op
                 createUser·p0.9999: 30.147 ms/op
                 createUser·p1.00:   31.228 ms/op

Iteration   3: 3.797 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.503 ms/op
                 createUser·p0.50:   3.678 ms/op
                 createUser·p0.90:   4.235 ms/op
                 createUser·p0.95:   5.038 ms/op
                 createUser·p0.99:   7.701 ms/op
                 createUser·p0.999:  22.712 ms/op
                 createUser·p0.9999: 38.601 ms/op
                 createUser·p1.00:   39.780 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 256991
  mean =      3.734 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2841 
    [ 2.500,  5.000) = 243179 
    [ 5.000,  7.500) = 8510 
    [ 7.500, 10.000) = 1657 
    [10.000, 12.500) = 331 
    [12.500, 15.000) = 146 
    [15.000, 17.500) = 50 
    [17.500, 20.000) = 13 
    [20.000, 22.500) = 46 
    [22.500, 25.000) = 74 
    [25.000, 27.500) = 39 
    [27.500, 30.000) = 61 
    [30.000, 32.500) = 12 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 10 

  Percentiles, ms/op:
      p(0.0000) =      1.503 ms/op
     p(50.0000) =      3.617 ms/op
     p(90.0000) =      4.202 ms/op
     p(95.0000) =      4.784 ms/op
     p(99.0000) =      7.422 ms/op
     p(99.9000) =     21.529 ms/op
     p(99.9900) =     37.179 ms/op
     p(99.9990) =     39.640 ms/op
     p(99.9999) =     39.780 ms/op
    p(100.0000) =     39.780 ms/op


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
# Warmup Iteration   1: 10.815 ±(99.9%) 0.155 ms/op
# Warmup Iteration   2: 4.013 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.587 ±(99.9%) 0.010 ms/op
Iteration   1: 3.640 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.298 ms/op
                 existUser·p0.50:   3.584 ms/op
                 existUser·p0.90:   4.071 ms/op
                 existUser·p0.95:   4.645 ms/op
                 existUser·p0.99:   6.808 ms/op
                 existUser·p0.999:  17.929 ms/op
                 existUser·p0.9999: 26.275 ms/op
                 existUser·p1.00:   26.837 ms/op

Iteration   2: 3.782 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   0.357 ms/op
                 existUser·p0.50:   3.613 ms/op
                 existUser·p0.90:   4.489 ms/op
                 existUser·p0.95:   5.038 ms/op
                 existUser·p0.99:   7.143 ms/op
                 existUser·p0.999:  24.784 ms/op
                 existUser·p0.9999: 34.944 ms/op
                 existUser·p1.00:   35.914 ms/op

Iteration   3: 3.524 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   0.868 ms/op
                 existUser·p0.50:   3.457 ms/op
                 existUser·p0.90:   3.920 ms/op
                 existUser·p0.95:   4.182 ms/op
                 existUser·p0.99:   6.472 ms/op
                 existUser·p0.999:  22.938 ms/op
                 existUser·p0.9999: 30.987 ms/op
                 existUser·p1.00:   32.375 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 263200
  mean =      3.646 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3058 
    [ 2.500,  5.000) = 250904 
    [ 5.000,  7.500) = 7625 
    [ 7.500, 10.000) = 1085 
    [10.000, 12.500) = 180 
    [12.500, 15.000) = 55 
    [15.000, 17.500) = 12 
    [17.500, 20.000) = 22 
    [20.000, 22.500) = 11 
    [22.500, 25.000) = 86 
    [25.000, 27.500) = 34 
    [27.500, 30.000) = 68 
    [30.000, 32.500) = 30 
    [32.500, 35.000) = 22 
    [35.000, 37.500) = 8 

  Percentiles, ms/op:
      p(0.0000) =      0.357 ms/op
     p(50.0000) =      3.543 ms/op
     p(90.0000) =      4.178 ms/op
     p(95.0000) =      4.637 ms/op
     p(99.0000) =      6.799 ms/op
     p(99.9000) =     19.261 ms/op
     p(99.9900) =     34.058 ms/op
     p(99.9990) =     35.545 ms/op
     p(99.9999) =     35.914 ms/op
    p(100.0000) =     35.914 ms/op


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
# Warmup Iteration   1: 12.923 ±(99.9%) 0.169 ms/op
# Warmup Iteration   2: 4.152 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.676 ±(99.9%) 0.011 ms/op
Iteration   1: 4.011 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   1.845 ms/op
                 getUser·p0.50:   3.801 ms/op
                 getUser·p0.90:   4.735 ms/op
                 getUser·p0.95:   6.070 ms/op
                 getUser·p0.99:   8.700 ms/op
                 getUser·p0.999:  11.855 ms/op
                 getUser·p0.9999: 24.412 ms/op
                 getUser·p1.00:   25.362 ms/op

Iteration   2: 3.639 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.569 ms/op
                 getUser·p0.50:   3.555 ms/op
                 getUser·p0.90:   4.141 ms/op
                 getUser·p0.95:   4.415 ms/op
                 getUser·p0.99:   6.005 ms/op
                 getUser·p0.999:  23.625 ms/op
                 getUser·p0.9999: 29.000 ms/op
                 getUser·p1.00:   30.048 ms/op

Iteration   3: 3.690 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.452 ms/op
                 getUser·p0.50:   3.559 ms/op
                 getUser·p0.90:   4.108 ms/op
                 getUser·p0.95:   4.506 ms/op
                 getUser·p0.99:   7.487 ms/op
                 getUser·p0.999:  25.906 ms/op
                 getUser·p0.9999: 30.736 ms/op
                 getUser·p1.00:   31.490 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 254259
  mean =      3.773 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2382 
    [ 2.500,  5.000) = 240035 
    [ 5.000,  7.500) = 8677 
    [ 7.500, 10.000) = 2413 
    [10.000, 12.500) = 439 
    [12.500, 15.000) = 56 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 14 
    [22.500, 25.000) = 82 
    [25.000, 27.500) = 53 
    [27.500, 30.000) = 92 
    [30.000, 32.500) = 15 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.452 ms/op
     p(50.0000) =      3.617 ms/op
     p(90.0000) =      4.358 ms/op
     p(95.0000) =      4.907 ms/op
     p(99.0000) =      7.840 ms/op
     p(99.9000) =     21.627 ms/op
     p(99.9900) =     29.262 ms/op
     p(99.9990) =     31.315 ms/op
     p(99.9999) =     31.490 ms/op
    p(100.0000) =     31.490 ms/op


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
# Warmup Iteration   1: 11.893 ±(99.9%) 0.177 ms/op
# Warmup Iteration   2: 4.773 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 4.590 ±(99.9%) 0.017 ms/op
Iteration   1: 4.356 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.716 ms/op
                 listUser·p0.50:   4.202 ms/op
                 listUser·p0.90:   4.907 ms/op
                 listUser·p0.95:   5.431 ms/op
                 listUser·p0.99:   8.651 ms/op
                 listUser·p0.999:  21.882 ms/op
                 listUser·p0.9999: 25.876 ms/op
                 listUser·p1.00:   27.263 ms/op

Iteration   2: 4.509 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.794 ms/op
                 listUser·p0.50:   4.284 ms/op
                 listUser·p0.90:   5.325 ms/op
                 listUser·p0.95:   5.964 ms/op
                 listUser·p0.99:   8.405 ms/op
                 listUser·p0.999:  16.663 ms/op
                 listUser·p0.9999: 19.658 ms/op
                 listUser·p1.00:   20.414 ms/op

Iteration   3: 4.353 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   2.294 ms/op
                 listUser·p0.50:   4.194 ms/op
                 listUser·p0.90:   4.915 ms/op
                 listUser·p0.95:   5.358 ms/op
                 listUser·p0.99:   8.520 ms/op
                 listUser·p0.999:  16.147 ms/op
                 listUser·p0.9999: 20.731 ms/op
                 listUser·p1.00:   22.905 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 217843
  mean =      4.405 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 35 
    [ 2.500,  5.000) = 192800 
    [ 5.000,  7.500) = 21082 
    [ 7.500, 10.000) = 2920 
    [10.000, 12.500) = 468 
    [12.500, 15.000) = 147 
    [15.000, 17.500) = 131 
    [17.500, 20.000) = 107 
    [20.000, 22.500) = 84 
    [22.500, 25.000) = 40 
    [25.000, 27.500) = 29 

  Percentiles, ms/op:
      p(0.0000) =      1.716 ms/op
     p(50.0000) =      4.219 ms/op
     p(90.0000) =      5.079 ms/op
     p(95.0000) =      5.603 ms/op
     p(99.0000) =      8.520 ms/op
     p(99.9000) =     18.612 ms/op
     p(99.9900) =     25.238 ms/op
     p(99.9990) =     26.801 ms/op
     p(99.9999) =     27.263 ms/op
    p(100.0000) =     27.263 ms/op


# Run complete. Total time: 00:13:12

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   8.682 ± 6.143  ops/ms
ClientPb.existUser                       thrpt       3   8.983 ± 1.383  ops/ms
ClientPb.getUser                         thrpt       3   8.563 ± 1.752  ops/ms
ClientPb.listUser                        thrpt       3   7.395 ± 1.855  ops/ms
ClientPb.createUser                       avgt       3   3.701 ± 1.244   ms/op
ClientPb.existUser                        avgt       3   3.566 ± 1.460   ms/op
ClientPb.getUser                          avgt       3   3.703 ± 1.394   ms/op
ClientPb.listUser                         avgt       3   4.395 ± 0.342   ms/op
ClientPb.createUser                     sample  256991   3.734 ± 0.007   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.503           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.617           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.202           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.784           ms/op
ClientPb.createUser:createUser·p0.99    sample           7.422           ms/op
ClientPb.createUser:createUser·p0.999   sample          21.529           ms/op
ClientPb.createUser:createUser·p0.9999  sample          37.179           ms/op
ClientPb.createUser:createUser·p1.00    sample          39.780           ms/op
ClientPb.existUser                      sample  263200   3.646 ± 0.007   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.357           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.543           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.178           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.637           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.799           ms/op
ClientPb.existUser:existUser·p0.999     sample          19.261           ms/op
ClientPb.existUser:existUser·p0.9999    sample          34.058           ms/op
ClientPb.existUser:existUser·p1.00      sample          35.914           ms/op
ClientPb.getUser                        sample  254259   3.773 ± 0.007   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.452           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.617           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.358           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.907           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.840           ms/op
ClientPb.getUser:getUser·p0.999         sample          21.627           ms/op
ClientPb.getUser:getUser·p0.9999        sample          29.262           ms/op
ClientPb.getUser:getUser·p1.00          sample          31.490           ms/op
ClientPb.listUser                       sample  217843   4.405 ± 0.008   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.716           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.219           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.079           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.603           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.520           ms/op
ClientPb.listUser:listUser·p0.999       sample          18.612           ms/op
ClientPb.listUser:listUser·p0.9999      sample          25.238           ms/op
ClientPb.listUser:listUser·p1.00        sample          27.263           ms/op
