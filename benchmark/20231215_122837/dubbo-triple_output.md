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
# Warmup Iteration   1: 5.270 ops/ms
# Warmup Iteration   2: 12.008 ops/ms
# Warmup Iteration   3: 12.356 ops/ms
Iteration   1: 12.494 ops/ms
Iteration   2: 12.578 ops/ms
Iteration   3: 12.719 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.597 ±(99.9%) 2.073 ops/ms [Average]
  (min, avg, max) = (12.494, 12.597, 12.719), stdev = 0.114
  CI (99.9%): [10.524, 14.670] (assumes normal distribution)


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
# Warmup Iteration   1: 7.682 ops/ms
# Warmup Iteration   2: 13.111 ops/ms
# Warmup Iteration   3: 13.016 ops/ms
Iteration   1: 12.907 ops/ms
Iteration   2: 12.976 ops/ms
Iteration   3: 13.019 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.967 ±(99.9%) 1.029 ops/ms [Average]
  (min, avg, max) = (12.907, 12.967, 13.019), stdev = 0.056
  CI (99.9%): [11.938, 13.996] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:47
# Fork: 1 of 1
# Warmup Iteration   1: 7.374 ops/ms
# Warmup Iteration   2: 12.366 ops/ms
# Warmup Iteration   3: 12.694 ops/ms
Iteration   1: 12.724 ops/ms
Iteration   2: 12.786 ops/ms
Iteration   3: 12.918 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.809 ±(99.9%) 1.809 ops/ms [Average]
  (min, avg, max) = (12.724, 12.809, 12.918), stdev = 0.099
  CI (99.9%): [11.000, 14.618] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:42
# Fork: 1 of 1
# Warmup Iteration   1: 6.583 ops/ms
# Warmup Iteration   2: 10.447 ops/ms
# Warmup Iteration   3: 10.611 ops/ms
Iteration   1: 10.671 ops/ms
Iteration   2: 10.583 ops/ms
Iteration   3: 10.571 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.608 ±(99.9%) 0.997 ops/ms [Average]
  (min, avg, max) = (10.571, 10.608, 10.671), stdev = 0.055
  CI (99.9%): [9.611, 11.606] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:37
# Fork: 1 of 1
# Warmup Iteration   1: 3.903 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 2.636 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.538 ±(99.9%) 0.004 ms/op
Iteration   1: 2.520 ±(99.9%) 0.004 ms/op
Iteration   2: 2.538 ±(99.9%) 0.004 ms/op
Iteration   3: 2.549 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.536 ±(99.9%) 0.263 ms/op [Average]
  (min, avg, max) = (2.520, 2.536, 2.549), stdev = 0.014
  CI (99.9%): [2.273, 2.799] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:32
# Fork: 1 of 1
# Warmup Iteration   1: 3.902 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.505 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.481 ±(99.9%) 0.004 ms/op
Iteration   1: 2.482 ±(99.9%) 0.003 ms/op
Iteration   2: 2.489 ±(99.9%) 0.004 ms/op
Iteration   3: 2.469 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.480 ±(99.9%) 0.183 ms/op [Average]
  (min, avg, max) = (2.469, 2.480, 2.489), stdev = 0.010
  CI (99.9%): [2.297, 2.662] (assumes normal distribution)


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
# Warmup Iteration   1: 3.884 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.562 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.513 ±(99.9%) 0.003 ms/op
Iteration   1: 2.501 ±(99.9%) 0.004 ms/op
Iteration   2: 2.497 ±(99.9%) 0.004 ms/op
Iteration   3: 2.489 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.496 ±(99.9%) 0.107 ms/op [Average]
  (min, avg, max) = (2.489, 2.496, 2.501), stdev = 0.006
  CI (99.9%): [2.389, 2.602] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:24
# Fork: 1 of 1
# Warmup Iteration   1: 4.597 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.047 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.017 ±(99.9%) 0.005 ms/op
Iteration   1: 3.042 ±(99.9%) 0.005 ms/op
Iteration   2: 3.037 ±(99.9%) 0.005 ms/op
Iteration   3: 3.062 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.047 ±(99.9%) 0.247 ms/op [Average]
  (min, avg, max) = (3.037, 3.047, 3.062), stdev = 0.014
  CI (99.9%): [2.800, 3.294] (assumes normal distribution)


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
# Warmup Iteration   1: 4.538 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 2.756 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.624 ±(99.9%) 0.006 ms/op
Iteration   1: 2.586 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.904 ms/op
                 createUser·p0.50:   2.683 ms/op
                 createUser·p0.90:   3.125 ms/op
                 createUser·p0.95:   3.224 ms/op
                 createUser·p0.99:   3.719 ms/op
                 createUser·p0.999:  11.917 ms/op
                 createUser·p0.9999: 14.664 ms/op
                 createUser·p1.00:   15.450 ms/op

Iteration   2: 2.585 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.842 ms/op
                 createUser·p0.50:   2.642 ms/op
                 createUser·p0.90:   3.142 ms/op
                 createUser·p0.95:   3.248 ms/op
                 createUser·p0.99:   3.682 ms/op
                 createUser·p0.999:  9.890 ms/op
                 createUser·p0.9999: 13.488 ms/op
                 createUser·p1.00:   14.516 ms/op

Iteration   3: 2.616 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   1.013 ms/op
                 createUser·p0.50:   2.695 ms/op
                 createUser·p0.90:   3.170 ms/op
                 createUser·p0.95:   3.297 ms/op
                 createUser·p0.99:   4.104 ms/op
                 createUser·p0.999:  9.317 ms/op
                 createUser·p0.9999: 11.660 ms/op
                 createUser·p1.00:   15.286 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 369476
  mean =      2.596 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 24 
    [ 1.250,  2.500) = 175483 
    [ 2.500,  3.750) = 189803 
    [ 3.750,  5.000) = 3105 
    [ 5.000,  6.250) = 577 
    [ 6.250,  7.500) = 45 
    [ 7.500,  8.750) = 15 
    [ 8.750, 10.000) = 87 
    [10.000, 11.250) = 130 
    [11.250, 12.500) = 64 
    [12.500, 13.750) = 98 
    [13.750, 15.000) = 35 
    [15.000, 16.250) = 10 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.842 ms/op
     p(50.0000) =      2.671 ms/op
     p(90.0000) =      3.146 ms/op
     p(95.0000) =      3.256 ms/op
     p(99.0000) =      3.827 ms/op
     p(99.9000) =      9.830 ms/op
     p(99.9900) =     14.386 ms/op
     p(99.9990) =     15.373 ms/op
     p(99.9999) =     15.450 ms/op
    p(100.0000) =     15.450 ms/op


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
# Warmup Iteration   1: 3.797 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 2.498 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.492 ±(99.9%) 0.005 ms/op
Iteration   1: 2.462 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.006 ms/op
                 existUser·p0.50:   2.515 ms/op
                 existUser·p0.90:   2.998 ms/op
                 existUser·p0.95:   3.097 ms/op
                 existUser·p0.99:   3.523 ms/op
                 existUser·p0.999:  7.543 ms/op
                 existUser·p0.9999: 13.812 ms/op
                 existUser·p1.00:   15.335 ms/op

Iteration   2: 2.477 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.919 ms/op
                 existUser·p0.50:   2.490 ms/op
                 existUser·p0.90:   3.031 ms/op
                 existUser·p0.95:   3.166 ms/op
                 existUser·p0.99:   3.850 ms/op
                 existUser·p0.999:  6.827 ms/op
                 existUser·p0.9999: 12.882 ms/op
                 existUser·p1.00:   14.451 ms/op

Iteration   3: 2.480 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.896 ms/op
                 existUser·p0.50:   2.540 ms/op
                 existUser·p0.90:   3.019 ms/op
                 existUser·p0.95:   3.125 ms/op
                 existUser·p0.99:   3.641 ms/op
                 existUser·p0.999:  8.474 ms/op
                 existUser·p0.9999: 11.788 ms/op
                 existUser·p1.00:   13.369 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 387791
  mean =      2.473 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 41 
    [ 1.250,  2.500) = 193040 
    [ 2.500,  3.750) = 191296 
    [ 3.750,  5.000) = 2445 
    [ 5.000,  6.250) = 523 
    [ 6.250,  7.500) = 53 
    [ 7.500,  8.750) = 28 
    [ 8.750, 10.000) = 89 
    [10.000, 11.250) = 59 
    [11.250, 12.500) = 141 
    [12.500, 13.750) = 61 
    [13.750, 15.000) = 14 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.896 ms/op
     p(50.0000) =      2.511 ms/op
     p(90.0000) =      3.015 ms/op
     p(95.0000) =      3.129 ms/op
     p(99.0000) =      3.674 ms/op
     p(99.9000) =      7.817 ms/op
     p(99.9900) =     13.036 ms/op
     p(99.9990) =     14.332 ms/op
     p(99.9999) =     15.335 ms/op
    p(100.0000) =     15.335 ms/op


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
# Warmup Iteration   1: 3.860 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 2.561 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.537 ±(99.9%) 0.006 ms/op
Iteration   1: 2.515 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.911 ms/op
                 getUser·p0.50:   2.515 ms/op
                 getUser·p0.90:   3.060 ms/op
                 getUser·p0.95:   3.195 ms/op
                 getUser·p0.99:   3.818 ms/op
                 getUser·p0.999:  11.223 ms/op
                 getUser·p0.9999: 14.226 ms/op
                 getUser·p1.00:   15.024 ms/op

Iteration   2: 2.520 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.962 ms/op
                 getUser·p0.50:   2.523 ms/op
                 getUser·p0.90:   3.072 ms/op
                 getUser·p0.95:   3.203 ms/op
                 getUser·p0.99:   4.026 ms/op
                 getUser·p0.999:  8.672 ms/op
                 getUser·p0.9999: 13.550 ms/op
                 getUser·p1.00:   14.156 ms/op

Iteration   3: 2.506 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.994 ms/op
                 getUser·p0.50:   2.544 ms/op
                 getUser·p0.90:   3.043 ms/op
                 getUser·p0.95:   3.150 ms/op
                 getUser·p0.99:   3.654 ms/op
                 getUser·p0.999:  8.694 ms/op
                 getUser·p0.9999: 12.144 ms/op
                 getUser·p1.00:   12.403 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 381618
  mean =      2.514 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 63 
    [ 1.250,  2.500) = 189028 
    [ 2.500,  3.750) = 188304 
    [ 3.750,  5.000) = 3421 
    [ 5.000,  6.250) = 393 
    [ 6.250,  7.500) = 25 
    [ 7.500,  8.750) = 8 
    [ 8.750, 10.000) = 70 
    [10.000, 11.250) = 45 
    [11.250, 12.500) = 117 
    [12.500, 13.750) = 108 
    [13.750, 15.000) = 35 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.911 ms/op
     p(50.0000) =      2.523 ms/op
     p(90.0000) =      3.060 ms/op
     p(95.0000) =      3.183 ms/op
     p(99.0000) =      3.817 ms/op
     p(99.9000) =      8.680 ms/op
     p(99.9900) =     13.730 ms/op
     p(99.9990) =     14.582 ms/op
     p(99.9999) =     15.024 ms/op
    p(100.0000) =     15.024 ms/op


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
# Warmup Iteration   1: 4.802 ±(99.9%) 0.054 ms/op
# Warmup Iteration   2: 3.086 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.026 ±(99.9%) 0.009 ms/op
Iteration   1: 3.033 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.974 ms/op
                 listUser·p0.50:   2.966 ms/op
                 listUser·p0.90:   3.916 ms/op
                 listUser·p0.95:   4.432 ms/op
                 listUser·p0.99:   5.890 ms/op
                 listUser·p0.999:  9.159 ms/op
                 listUser·p0.9999: 10.534 ms/op
                 listUser·p1.00:   11.125 ms/op

Iteration   2: 3.007 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.817 ms/op
                 listUser·p0.50:   2.949 ms/op
                 listUser·p0.90:   3.863 ms/op
                 listUser·p0.95:   4.342 ms/op
                 listUser·p0.99:   5.415 ms/op
                 listUser·p0.999:  9.923 ms/op
                 listUser·p0.9999: 12.077 ms/op
                 listUser·p1.00:   13.222 ms/op

Iteration   3: 3.011 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.766 ms/op
                 listUser·p0.50:   2.953 ms/op
                 listUser·p0.90:   3.891 ms/op
                 listUser·p0.95:   4.366 ms/op
                 listUser·p0.99:   5.439 ms/op
                 listUser·p0.999:  8.681 ms/op
                 listUser·p0.9999: 11.803 ms/op
                 listUser·p1.00:   12.468 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 317903
  mean =      3.017 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 116 
    [ 1.250,  2.500) = 89516 
    [ 2.500,  3.750) = 189213 
    [ 3.750,  5.000) = 32036 
    [ 5.000,  6.250) = 5574 
    [ 6.250,  7.500) = 691 
    [ 7.500,  8.750) = 358 
    [ 8.750, 10.000) = 214 
    [10.000, 11.250) = 118 
    [11.250, 12.500) = 60 
    [12.500, 13.750) = 7 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.766 ms/op
     p(50.0000) =      2.953 ms/op
     p(90.0000) =      3.891 ms/op
     p(95.0000) =      4.375 ms/op
     p(99.0000) =      5.554 ms/op
     p(99.9000) =      9.046 ms/op
     p(99.9900) =     11.846 ms/op
     p(99.9990) =     12.798 ms/op
     p(99.9999) =     13.222 ms/op
    p(100.0000) =     13.222 ms/op


# Run complete. Total time: 00:12:58

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.597 ± 2.073  ops/ms
ClientPb.existUser                       thrpt       3  12.967 ± 1.029  ops/ms
ClientPb.getUser                         thrpt       3  12.809 ± 1.809  ops/ms
ClientPb.listUser                        thrpt       3  10.608 ± 0.997  ops/ms
ClientPb.createUser                       avgt       3   2.536 ± 0.263   ms/op
ClientPb.existUser                        avgt       3   2.480 ± 0.183   ms/op
ClientPb.getUser                          avgt       3   2.496 ± 0.107   ms/op
ClientPb.listUser                         avgt       3   3.047 ± 0.247   ms/op
ClientPb.createUser                     sample  369476   2.596 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.842           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.671           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.146           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.256           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.827           ms/op
ClientPb.createUser:createUser·p0.999   sample           9.830           ms/op
ClientPb.createUser:createUser·p0.9999  sample          14.386           ms/op
ClientPb.createUser:createUser·p1.00    sample          15.450           ms/op
ClientPb.existUser                      sample  387791   2.473 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.896           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.511           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.015           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.129           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.674           ms/op
ClientPb.existUser:existUser·p0.999     sample           7.817           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.036           ms/op
ClientPb.existUser:existUser·p1.00      sample          15.335           ms/op
ClientPb.getUser                        sample  381618   2.514 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.911           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.523           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.060           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.183           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.817           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.680           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.730           ms/op
ClientPb.getUser:getUser·p1.00          sample          15.024           ms/op
ClientPb.listUser                       sample  317903   3.017 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.766           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.953           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.891           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.375           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.554           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.046           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.846           ms/op
ClientPb.listUser:listUser·p1.00        sample          13.222           ms/op
