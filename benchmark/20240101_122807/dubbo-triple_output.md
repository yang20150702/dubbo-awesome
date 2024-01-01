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
# Warmup Iteration   1: 4.559 ops/ms
# Warmup Iteration   2: 12.372 ops/ms
# Warmup Iteration   3: 12.815 ops/ms
Iteration   1: 12.806 ops/ms
Iteration   2: 12.684 ops/ms
Iteration   3: 12.987 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.826 ±(99.9%) 2.781 ops/ms [Average]
  (min, avg, max) = (12.684, 12.826, 12.987), stdev = 0.152
  CI (99.9%): [10.045, 15.606] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:52
# Fork: 1 of 1
# Warmup Iteration   1: 8.598 ops/ms
# Warmup Iteration   2: 13.284 ops/ms
# Warmup Iteration   3: 13.181 ops/ms
Iteration   1: 13.048 ops/ms
Iteration   2: 13.150 ops/ms
Iteration   3: 13.197 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.132 ±(99.9%) 1.387 ops/ms [Average]
  (min, avg, max) = (13.048, 13.132, 13.197), stdev = 0.076
  CI (99.9%): [11.745, 14.519] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 8.033 ops/ms
# Warmup Iteration   2: 12.736 ops/ms
# Warmup Iteration   3: 12.878 ops/ms
Iteration   1: 12.912 ops/ms
Iteration   2: 12.839 ops/ms
Iteration   3: 12.871 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.874 ±(99.9%) 0.667 ops/ms [Average]
  (min, avg, max) = (12.839, 12.874, 12.912), stdev = 0.037
  CI (99.9%): [12.207, 13.541] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:44
# Fork: 1 of 1
# Warmup Iteration   1: 6.671 ops/ms
# Warmup Iteration   2: 10.203 ops/ms
# Warmup Iteration   3: 10.444 ops/ms
Iteration   1: 10.629 ops/ms
Iteration   2: 10.554 ops/ms
Iteration   3: 10.546 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.576 ±(99.9%) 0.840 ops/ms [Average]
  (min, avg, max) = (10.546, 10.576, 10.629), stdev = 0.046
  CI (99.9%): [9.736, 11.416] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:39
# Fork: 1 of 1
# Warmup Iteration   1: 3.957 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.585 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.516 ±(99.9%) 0.004 ms/op
Iteration   1: 2.542 ±(99.9%) 0.004 ms/op
Iteration   2: 2.521 ±(99.9%) 0.004 ms/op
Iteration   3: 2.533 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.532 ±(99.9%) 0.192 ms/op [Average]
  (min, avg, max) = (2.521, 2.532, 2.542), stdev = 0.011
  CI (99.9%): [2.340, 2.724] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:33
# Fork: 1 of 1
# Warmup Iteration   1: 3.551 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.411 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.408 ±(99.9%) 0.003 ms/op
Iteration   1: 2.412 ±(99.9%) 0.003 ms/op
Iteration   2: 2.432 ±(99.9%) 0.005 ms/op
Iteration   3: 2.413 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.419 ±(99.9%) 0.209 ms/op [Average]
  (min, avg, max) = (2.412, 2.419, 2.432), stdev = 0.011
  CI (99.9%): [2.210, 2.628] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:28
# Fork: 1 of 1
# Warmup Iteration   1: 3.829 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.527 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.450 ±(99.9%) 0.004 ms/op
Iteration   1: 2.477 ±(99.9%) 0.004 ms/op
Iteration   2: 2.453 ±(99.9%) 0.005 ms/op
Iteration   3: 2.434 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.455 ±(99.9%) 0.396 ms/op [Average]
  (min, avg, max) = (2.434, 2.455, 2.477), stdev = 0.022
  CI (99.9%): [2.059, 2.850] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:23
# Fork: 1 of 1
# Warmup Iteration   1: 4.770 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.063 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.016 ±(99.9%) 0.005 ms/op
Iteration   1: 3.007 ±(99.9%) 0.005 ms/op
Iteration   2: 3.052 ±(99.9%) 0.006 ms/op
Iteration   3: 2.997 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.019 ±(99.9%) 0.539 ms/op [Average]
  (min, avg, max) = (2.997, 3.019, 3.052), stdev = 0.030
  CI (99.9%): [2.479, 3.558] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:19
# Fork: 1 of 1
# Warmup Iteration   1: 4.036 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 2.630 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.475 ±(99.9%) 0.005 ms/op
Iteration   1: 2.485 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.876 ms/op
                 createUser·p0.50:   2.527 ms/op
                 createUser·p0.90:   3.023 ms/op
                 createUser·p0.95:   3.150 ms/op
                 createUser·p0.99:   3.811 ms/op
                 createUser·p0.999:  11.004 ms/op
                 createUser·p0.9999: 14.008 ms/op
                 createUser·p1.00:   14.254 ms/op

Iteration   2: 2.464 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.063 ms/op
                 createUser·p0.50:   2.527 ms/op
                 createUser·p0.90:   3.002 ms/op
                 createUser·p0.95:   3.105 ms/op
                 createUser·p0.99:   3.547 ms/op
                 createUser·p0.999:  7.265 ms/op
                 createUser·p0.9999: 11.748 ms/op
                 createUser·p1.00:   12.714 ms/op

Iteration   3: 2.493 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.926 ms/op
                 createUser·p0.50:   2.515 ms/op
                 createUser·p0.90:   3.043 ms/op
                 createUser·p0.95:   3.183 ms/op
                 createUser·p0.99:   3.953 ms/op
                 createUser·p0.999:  8.328 ms/op
                 createUser·p0.9999: 10.387 ms/op
                 createUser·p1.00:   12.534 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 386616
  mean =      2.480 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 52 
    [ 1.250,  2.500) = 191255 
    [ 2.500,  3.750) = 191406 
    [ 3.750,  5.000) = 3086 
    [ 5.000,  6.250) = 302 
    [ 6.250,  7.500) = 62 
    [ 7.500,  8.750) = 68 
    [ 8.750, 10.000) = 120 
    [10.000, 11.250) = 96 
    [11.250, 12.500) = 75 
    [12.500, 13.750) = 66 
    [13.750, 15.000) = 28 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.876 ms/op
     p(50.0000) =      2.523 ms/op
     p(90.0000) =      3.023 ms/op
     p(95.0000) =      3.146 ms/op
     p(99.0000) =      3.756 ms/op
     p(99.9000) =      8.739 ms/op
     p(99.9900) =     13.156 ms/op
     p(99.9990) =     14.115 ms/op
     p(99.9999) =     14.254 ms/op
    p(100.0000) =     14.254 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.904 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 2.451 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.452 ±(99.9%) 0.005 ms/op
Iteration   1: 2.436 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.978 ms/op
                 existUser·p0.50:   2.499 ms/op
                 existUser·p0.90:   2.957 ms/op
                 existUser·p0.95:   3.060 ms/op
                 existUser·p0.99:   3.506 ms/op
                 existUser·p0.999:  7.605 ms/op
                 existUser·p0.9999: 14.068 ms/op
                 existUser·p1.00:   14.746 ms/op

Iteration   2: 2.448 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.880 ms/op
                 existUser·p0.50:   2.490 ms/op
                 existUser·p0.90:   2.994 ms/op
                 existUser·p0.95:   3.113 ms/op
                 existUser·p0.99:   3.535 ms/op
                 existUser·p0.999:  8.517 ms/op
                 existUser·p0.9999: 12.516 ms/op
                 existUser·p1.00:   13.304 ms/op

Iteration   3: 2.436 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.973 ms/op
                 existUser·p0.50:   2.486 ms/op
                 existUser·p0.90:   2.966 ms/op
                 existUser·p0.95:   3.080 ms/op
                 existUser·p0.99:   3.682 ms/op
                 existUser·p0.999:  8.878 ms/op
                 existUser·p0.9999: 11.527 ms/op
                 existUser·p1.00:   12.894 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 392911
  mean =      2.440 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 49 
    [ 1.250,  2.500) = 197289 
    [ 2.500,  3.750) = 192587 
    [ 3.750,  5.000) = 2083 
    [ 5.000,  6.250) = 402 
    [ 6.250,  7.500) = 70 
    [ 7.500,  8.750) = 38 
    [ 8.750, 10.000) = 108 
    [10.000, 11.250) = 102 
    [11.250, 12.500) = 98 
    [12.500, 13.750) = 58 
    [13.750, 15.000) = 27 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.880 ms/op
     p(50.0000) =      2.490 ms/op
     p(90.0000) =      2.974 ms/op
     p(95.0000) =      3.084 ms/op
     p(99.0000) =      3.580 ms/op
     p(99.9000) =      8.847 ms/op
     p(99.9900) =     13.196 ms/op
     p(99.9990) =     14.696 ms/op
     p(99.9999) =     14.746 ms/op
    p(100.0000) =     14.746 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:09
# Fork: 1 of 1
# Warmup Iteration   1: 3.935 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 2.540 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.531 ±(99.9%) 0.006 ms/op
Iteration   1: 2.487 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.857 ms/op
                 getUser·p0.50:   2.494 ms/op
                 getUser·p0.90:   3.035 ms/op
                 getUser·p0.95:   3.150 ms/op
                 getUser·p0.99:   3.682 ms/op
                 getUser·p0.999:  8.500 ms/op
                 getUser·p0.9999: 13.599 ms/op
                 getUser·p1.00:   14.483 ms/op

Iteration   2: 2.515 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.828 ms/op
                 getUser·p0.50:   2.515 ms/op
                 getUser·p0.90:   3.076 ms/op
                 getUser·p0.95:   3.224 ms/op
                 getUser·p0.99:   3.998 ms/op
                 getUser·p0.999:  10.351 ms/op
                 getUser·p0.9999: 13.552 ms/op
                 getUser·p1.00:   14.172 ms/op

Iteration   3: 2.524 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.787 ms/op
                 getUser·p0.50:   2.531 ms/op
                 getUser·p0.90:   3.080 ms/op
                 getUser·p0.95:   3.244 ms/op
                 getUser·p0.99:   4.211 ms/op
                 getUser·p0.999:  8.410 ms/op
                 getUser·p0.9999: 11.179 ms/op
                 getUser·p1.00:   11.354 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 382324
  mean =      2.509 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 78 
    [ 1.250,  2.500) = 189702 
    [ 2.500,  3.750) = 187252 
    [ 3.750,  5.000) = 4116 
    [ 5.000,  6.250) = 758 
    [ 6.250,  7.500) = 33 
    [ 7.500,  8.750) = 14 
    [ 8.750, 10.000) = 46 
    [10.000, 11.250) = 84 
    [11.250, 12.500) = 126 
    [12.500, 13.750) = 99 
    [13.750, 15.000) = 16 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.787 ms/op
     p(50.0000) =      2.515 ms/op
     p(90.0000) =      3.064 ms/op
     p(95.0000) =      3.203 ms/op
     p(99.0000) =      3.965 ms/op
     p(99.9000) =      8.416 ms/op
     p(99.9900) =     13.284 ms/op
     p(99.9990) =     14.243 ms/op
     p(99.9999) =     14.483 ms/op
    p(100.0000) =     14.483 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:04
# Fork: 1 of 1
# Warmup Iteration   1: 4.715 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 3.115 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.039 ±(99.9%) 0.009 ms/op
Iteration   1: 3.028 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.845 ms/op
                 listUser·p0.50:   2.966 ms/op
                 listUser·p0.90:   3.920 ms/op
                 listUser·p0.95:   4.415 ms/op
                 listUser·p0.99:   5.644 ms/op
                 listUser·p0.999:  8.494 ms/op
                 listUser·p0.9999: 11.050 ms/op
                 listUser·p1.00:   11.813 ms/op

Iteration   2: 3.026 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.914 ms/op
                 listUser·p0.50:   2.966 ms/op
                 listUser·p0.90:   3.916 ms/op
                 listUser·p0.95:   4.399 ms/op
                 listUser·p0.99:   5.661 ms/op
                 listUser·p0.999:  9.858 ms/op
                 listUser·p0.9999: 13.484 ms/op
                 listUser·p1.00:   13.730 ms/op

Iteration   3: 3.048 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.853 ms/op
                 listUser·p0.50:   2.978 ms/op
                 listUser·p0.90:   3.957 ms/op
                 listUser·p0.95:   4.448 ms/op
                 listUser·p0.99:   5.652 ms/op
                 listUser·p0.999:  9.570 ms/op
                 listUser·p0.9999: 10.765 ms/op
                 listUser·p1.00:   11.600 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 316129
  mean =      3.034 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 159 
    [ 1.250,  2.500) = 87706 
    [ 2.500,  3.750) = 186563 
    [ 3.750,  5.000) = 34318 
    [ 5.000,  6.250) = 5925 
    [ 6.250,  7.500) = 790 
    [ 7.500,  8.750) = 231 
    [ 8.750, 10.000) = 237 
    [10.000, 11.250) = 127 
    [11.250, 12.500) = 39 
    [12.500, 13.750) = 34 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.845 ms/op
     p(50.0000) =      2.970 ms/op
     p(90.0000) =      3.928 ms/op
     p(95.0000) =      4.424 ms/op
     p(99.0000) =      5.652 ms/op
     p(99.9000) =      9.388 ms/op
     p(99.9900) =     12.714 ms/op
     p(99.9990) =     13.632 ms/op
     p(99.9999) =     13.730 ms/op
    p(100.0000) =     13.730 ms/op


# Run complete. Total time: 00:12:58

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.826 ± 2.781  ops/ms
ClientPb.existUser                       thrpt       3  13.132 ± 1.387  ops/ms
ClientPb.getUser                         thrpt       3  12.874 ± 0.667  ops/ms
ClientPb.listUser                        thrpt       3  10.576 ± 0.840  ops/ms
ClientPb.createUser                       avgt       3   2.532 ± 0.192   ms/op
ClientPb.existUser                        avgt       3   2.419 ± 0.209   ms/op
ClientPb.getUser                          avgt       3   2.455 ± 0.396   ms/op
ClientPb.listUser                         avgt       3   3.019 ± 0.539   ms/op
ClientPb.createUser                     sample  386616   2.480 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.876           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.523           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.023           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.146           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.756           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.739           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.156           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.254           ms/op
ClientPb.existUser                      sample  392911   2.440 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.880           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.490           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.974           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.084           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.580           ms/op
ClientPb.existUser:existUser·p0.999     sample           8.847           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.196           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.746           ms/op
ClientPb.getUser                        sample  382324   2.509 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.787           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.515           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.064           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.203           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.965           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.416           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.284           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.483           ms/op
ClientPb.listUser                       sample  316129   3.034 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.845           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.970           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.928           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.424           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.652           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.388           ms/op
ClientPb.listUser:listUser·p0.9999      sample          12.714           ms/op
ClientPb.listUser:listUser·p1.00        sample          13.730           ms/op
