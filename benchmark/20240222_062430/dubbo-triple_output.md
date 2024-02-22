# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 4.777 ops/ms
# Warmup Iteration   2: 12.181 ops/ms
# Warmup Iteration   3: 12.234 ops/ms
Iteration   1: 12.564 ops/ms
Iteration   2: 12.455 ops/ms
Iteration   3: 12.515 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.511 ±(99.9%) 1.000 ops/ms [Average]
  (min, avg, max) = (12.455, 12.511, 12.564), stdev = 0.055
  CI (99.9%): [11.511, 13.511] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:11:52
# Fork: 1 of 1
# Warmup Iteration   1: 7.707 ops/ms
# Warmup Iteration   2: 12.982 ops/ms
# Warmup Iteration   3: 12.856 ops/ms
Iteration   1: 12.889 ops/ms
Iteration   2: 12.973 ops/ms
Iteration   3: 12.843 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.902 ±(99.9%) 1.202 ops/ms [Average]
  (min, avg, max) = (12.843, 12.902, 12.973), stdev = 0.066
  CI (99.9%): [11.699, 14.104] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:47
# Fork: 1 of 1
# Warmup Iteration   1: 7.497 ops/ms
# Warmup Iteration   2: 12.548 ops/ms
# Warmup Iteration   3: 12.701 ops/ms
Iteration   1: 12.954 ops/ms
Iteration   2: 12.782 ops/ms
Iteration   3: 12.765 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.834 ±(99.9%) 1.911 ops/ms [Average]
  (min, avg, max) = (12.765, 12.834, 12.954), stdev = 0.105
  CI (99.9%): [10.922, 14.745] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:45
# Fork: 1 of 1
# Warmup Iteration   1: 6.778 ops/ms
# Warmup Iteration   2: 10.411 ops/ms
# Warmup Iteration   3: 10.537 ops/ms
Iteration   1: 10.658 ops/ms
Iteration   2: 10.698 ops/ms
Iteration   3: 10.465 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.607 ±(99.9%) 2.277 ops/ms [Average]
  (min, avg, max) = (10.465, 10.607, 10.698), stdev = 0.125
  CI (99.9%): [8.330, 12.884] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 3.961 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.560 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.505 ±(99.9%) 0.004 ms/op
Iteration   1: 2.524 ±(99.9%) 0.004 ms/op
Iteration   2: 2.494 ±(99.9%) 0.003 ms/op
Iteration   3: 2.477 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.499 ±(99.9%) 0.430 ms/op [Average]
  (min, avg, max) = (2.477, 2.499, 2.524), stdev = 0.024
  CI (99.9%): [2.069, 2.928] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:35
# Fork: 1 of 1
# Warmup Iteration   1: 3.732 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.476 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.478 ±(99.9%) 0.003 ms/op
Iteration   1: 2.445 ±(99.9%) 0.004 ms/op
Iteration   2: 2.539 ±(99.9%) 0.004 ms/op
Iteration   3: 2.481 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.488 ±(99.9%) 0.866 ms/op [Average]
  (min, avg, max) = (2.445, 2.488, 2.539), stdev = 0.047
  CI (99.9%): [1.622, 3.354] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:30
# Fork: 1 of 1
# Warmup Iteration   1: 4.042 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 2.487 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.485 ±(99.9%) 0.005 ms/op
Iteration   1: 2.473 ±(99.9%) 0.004 ms/op
Iteration   2: 2.472 ±(99.9%) 0.005 ms/op
Iteration   3: 2.487 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.477 ±(99.9%) 0.151 ms/op [Average]
  (min, avg, max) = (2.472, 2.477, 2.487), stdev = 0.008
  CI (99.9%): [2.327, 2.628] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:24
# Fork: 1 of 1
# Warmup Iteration   1: 4.570 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.058 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.015 ±(99.9%) 0.005 ms/op
Iteration   1: 3.018 ±(99.9%) 0.005 ms/op
Iteration   2: 3.002 ±(99.9%) 0.004 ms/op
Iteration   3: 2.996 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.005 ±(99.9%) 0.209 ms/op [Average]
  (min, avg, max) = (2.996, 3.005, 3.018), stdev = 0.011
  CI (99.9%): [2.797, 3.214] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:19
# Fork: 1 of 1
# Warmup Iteration   1: 4.016 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 2.685 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.529 ±(99.9%) 0.006 ms/op
Iteration   1: 2.521 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.858 ms/op
                 createUser·p0.50:   2.564 ms/op
                 createUser·p0.90:   3.060 ms/op
                 createUser·p0.95:   3.178 ms/op
                 createUser·p0.99:   3.838 ms/op
                 createUser·p0.999:  11.505 ms/op
                 createUser·p0.9999: 13.069 ms/op
                 createUser·p1.00:   14.008 ms/op

Iteration   2: 2.539 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.761 ms/op
                 createUser·p0.50:   2.589 ms/op
                 createUser·p0.90:   3.084 ms/op
                 createUser·p0.95:   3.232 ms/op
                 createUser·p0.99:   4.010 ms/op
                 createUser·p0.999:  9.768 ms/op
                 createUser·p0.9999: 12.245 ms/op
                 createUser·p1.00:   12.501 ms/op

Iteration   3: 2.513 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.947 ms/op
                 createUser·p0.50:   2.589 ms/op
                 createUser·p0.90:   3.052 ms/op
                 createUser·p0.95:   3.162 ms/op
                 createUser·p0.99:   3.633 ms/op
                 createUser·p0.999:  8.796 ms/op
                 createUser·p0.9999: 10.746 ms/op
                 createUser·p1.00:   17.924 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 379821
  mean =      2.524 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 59 
    [ 1.250,  2.500) = 182764 
    [ 2.500,  3.750) = 192678 
    [ 3.750,  5.000) = 3302 
    [ 5.000,  6.250) = 556 
    [ 6.250,  7.500) = 75 
    [ 7.500,  8.750) = 2 
    [ 8.750, 10.000) = 105 
    [10.000, 11.250) = 116 
    [11.250, 12.500) = 105 
    [12.500, 13.750) = 51 
    [13.750, 15.000) = 7 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.761 ms/op
     p(50.0000) =      2.580 ms/op
     p(90.0000) =      3.064 ms/op
     p(95.0000) =      3.187 ms/op
     p(99.0000) =      3.822 ms/op
     p(99.9000) =      8.864 ms/op
     p(99.9900) =     12.829 ms/op
     p(99.9990) =     13.858 ms/op
     p(99.9999) =     17.924 ms/op
    p(100.0000) =     17.924 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.652 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 2.484 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.427 ±(99.9%) 0.005 ms/op
Iteration   1: 2.438 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.951 ms/op
                 existUser·p0.50:   2.503 ms/op
                 existUser·p0.90:   2.966 ms/op
                 existUser·p0.95:   3.064 ms/op
                 existUser·p0.99:   3.473 ms/op
                 existUser·p0.999:  6.636 ms/op
                 existUser·p0.9999: 14.152 ms/op
                 existUser·p1.00:   14.778 ms/op

Iteration   2: 2.447 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.239 ms/op
                 existUser·p0.50:   2.605 ms/op
                 existUser·p0.90:   2.953 ms/op
                 existUser·p0.95:   3.043 ms/op
                 existUser·p0.99:   3.465 ms/op
                 existUser·p0.999:  6.305 ms/op
                 existUser·p0.9999: 12.960 ms/op
                 existUser·p1.00:   13.976 ms/op

Iteration   3: 2.421 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.866 ms/op
                 existUser·p0.50:   2.478 ms/op
                 existUser·p0.90:   2.945 ms/op
                 existUser·p0.95:   3.052 ms/op
                 existUser·p0.99:   3.592 ms/op
                 existUser·p0.999:  8.389 ms/op
                 existUser·p0.9999: 11.911 ms/op
                 existUser·p1.00:   12.452 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 393792
  mean =      2.436 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 35 
    [ 1.250,  2.500) = 194823 
    [ 2.500,  3.750) = 196103 
    [ 3.750,  5.000) = 1955 
    [ 5.000,  6.250) = 445 
    [ 6.250,  7.500) = 32 
    [ 7.500,  8.750) = 31 
    [ 8.750, 10.000) = 78 
    [10.000, 11.250) = 79 
    [11.250, 12.500) = 106 
    [12.500, 13.750) = 85 
    [13.750, 15.000) = 20 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.866 ms/op
     p(50.0000) =      2.527 ms/op
     p(90.0000) =      2.953 ms/op
     p(95.0000) =      3.052 ms/op
     p(99.0000) =      3.523 ms/op
     p(99.9000) =      7.891 ms/op
     p(99.9900) =     13.468 ms/op
     p(99.9990) =     14.402 ms/op
     p(99.9999) =     14.778 ms/op
    p(100.0000) =     14.778 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:09
# Fork: 1 of 1
# Warmup Iteration   1: 3.944 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 2.571 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.509 ±(99.9%) 0.006 ms/op
Iteration   1: 2.507 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.926 ms/op
                 getUser·p0.50:   2.503 ms/op
                 getUser·p0.90:   3.068 ms/op
                 getUser·p0.95:   3.187 ms/op
                 getUser·p0.99:   3.682 ms/op
                 getUser·p0.999:  10.308 ms/op
                 getUser·p0.9999: 13.550 ms/op
                 getUser·p1.00:   14.467 ms/op

Iteration   2: 2.552 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   1.073 ms/op
                 getUser·p0.50:   2.556 ms/op
                 getUser·p0.90:   3.101 ms/op
                 getUser·p0.95:   3.240 ms/op
                 getUser·p0.99:   4.588 ms/op
                 getUser·p0.999:  10.157 ms/op
                 getUser·p0.9999: 12.911 ms/op
                 getUser·p1.00:   13.255 ms/op

Iteration   3: 2.514 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.871 ms/op
                 getUser·p0.50:   2.544 ms/op
                 getUser·p0.90:   3.060 ms/op
                 getUser·p0.95:   3.166 ms/op
                 getUser·p0.99:   3.654 ms/op
                 getUser·p0.999:  7.451 ms/op
                 getUser·p0.9999: 10.635 ms/op
                 getUser·p1.00:   11.108 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 379969
  mean =      2.524 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 69 
    [ 1.250,  2.500) = 187509 
    [ 2.500,  3.750) = 187732 
    [ 3.750,  5.000) = 3408 
    [ 5.000,  6.250) = 774 
    [ 6.250,  7.500) = 61 
    [ 7.500,  8.750) = 25 
    [ 8.750, 10.000) = 88 
    [10.000, 11.250) = 142 
    [11.250, 12.500) = 85 
    [12.500, 13.750) = 68 
    [13.750, 15.000) = 8 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.871 ms/op
     p(50.0000) =      2.535 ms/op
     p(90.0000) =      3.076 ms/op
     p(95.0000) =      3.195 ms/op
     p(99.0000) =      3.891 ms/op
     p(99.9000) =      9.110 ms/op
     p(99.9900) =     13.173 ms/op
     p(99.9990) =     14.090 ms/op
     p(99.9999) =     14.467 ms/op
    p(100.0000) =     14.467 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:04
# Fork: 1 of 1
# Warmup Iteration   1: 4.802 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 3.096 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.041 ±(99.9%) 0.009 ms/op
Iteration   1: 3.016 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.952 ms/op
                 listUser·p0.50:   2.961 ms/op
                 listUser·p0.90:   3.879 ms/op
                 listUser·p0.95:   4.358 ms/op
                 listUser·p0.99:   5.603 ms/op
                 listUser·p0.999:  9.535 ms/op
                 listUser·p0.9999: 10.922 ms/op
                 listUser·p1.00:   11.600 ms/op

Iteration   2: 3.002 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.914 ms/op
                 listUser·p0.50:   2.953 ms/op
                 listUser·p0.90:   3.838 ms/op
                 listUser·p0.95:   4.317 ms/op
                 listUser·p0.99:   5.513 ms/op
                 listUser·p0.999:  8.847 ms/op
                 listUser·p0.9999: 10.475 ms/op
                 listUser·p1.00:   11.092 ms/op

Iteration   3: 2.998 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.057 ms/op
                 listUser·p0.50:   2.941 ms/op
                 listUser·p0.90:   3.817 ms/op
                 listUser·p0.95:   4.284 ms/op
                 listUser·p0.99:   5.439 ms/op
                 listUser·p0.999:  9.105 ms/op
                 listUser·p0.9999: 10.655 ms/op
                 listUser·p1.00:   11.764 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 319056
  mean =      3.005 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 80 
    [ 1.250,  2.500) = 88997 
    [ 2.500,  3.750) = 192698 
    [ 3.750,  5.000) = 30842 
    [ 5.000,  6.250) = 5228 
    [ 6.250,  7.500) = 593 
    [ 7.500,  8.750) = 219 
    [ 8.750, 10.000) = 267 
    [10.000, 11.250) = 121 
    [11.250, 12.500) = 11 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.914 ms/op
     p(50.0000) =      2.953 ms/op
     p(90.0000) =      3.842 ms/op
     p(95.0000) =      4.317 ms/op
     p(99.0000) =      5.513 ms/op
     p(99.9000) =      9.159 ms/op
     p(99.9900) =     10.781 ms/op
     p(99.9990) =     11.613 ms/op
     p(99.9999) =     11.764 ms/op
    p(100.0000) =     11.764 ms/op


# Run complete. Total time: 00:12:59

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.511 ± 1.000  ops/ms
ClientPb.existUser                       thrpt       3  12.902 ± 1.202  ops/ms
ClientPb.getUser                         thrpt       3  12.834 ± 1.911  ops/ms
ClientPb.listUser                        thrpt       3  10.607 ± 2.277  ops/ms
ClientPb.createUser                       avgt       3   2.499 ± 0.430   ms/op
ClientPb.existUser                        avgt       3   2.488 ± 0.866   ms/op
ClientPb.getUser                          avgt       3   2.477 ± 0.151   ms/op
ClientPb.listUser                         avgt       3   3.005 ± 0.209   ms/op
ClientPb.createUser                     sample  379821   2.524 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.761           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.580           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.064           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.187           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.822           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.864           ms/op
ClientPb.createUser:createUser·p0.9999  sample          12.829           ms/op
ClientPb.createUser:createUser·p1.00    sample          17.924           ms/op
ClientPb.existUser                      sample  393792   2.436 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.866           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.527           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.953           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.052           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.523           ms/op
ClientPb.existUser:existUser·p0.999     sample           7.891           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.468           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.778           ms/op
ClientPb.getUser                        sample  379969   2.524 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.871           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.535           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.076           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.195           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.891           ms/op
ClientPb.getUser:getUser·p0.999         sample           9.110           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.173           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.467           ms/op
ClientPb.listUser                       sample  319056   3.005 ± 0.004   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.914           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.953           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.842           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.317           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.513           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.159           ms/op
ClientPb.listUser:listUser·p0.9999      sample          10.781           ms/op
ClientPb.listUser:listUser·p1.00        sample          11.764           ms/op
