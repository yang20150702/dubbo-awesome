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
# Warmup Iteration   1: 4.929 ops/ms
# Warmup Iteration   2: 12.007 ops/ms
# Warmup Iteration   3: 12.438 ops/ms
Iteration   1: 12.661 ops/ms
Iteration   2: 12.595 ops/ms
Iteration   3: 12.747 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.667 ±(99.9%) 1.391 ops/ms [Average]
  (min, avg, max) = (12.595, 12.667, 12.747), stdev = 0.076
  CI (99.9%): [11.276, 14.058] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:51
# Fork: 1 of 1
# Warmup Iteration   1: 8.014 ops/ms
# Warmup Iteration   2: 13.157 ops/ms
# Warmup Iteration   3: 13.398 ops/ms
Iteration   1: 13.225 ops/ms
Iteration   2: 13.156 ops/ms
Iteration   3: 13.234 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.205 ±(99.9%) 0.780 ops/ms [Average]
  (min, avg, max) = (13.156, 13.205, 13.234), stdev = 0.043
  CI (99.9%): [12.425, 13.985] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 7.688 ops/ms
# Warmup Iteration   2: 12.664 ops/ms
# Warmup Iteration   3: 12.807 ops/ms
Iteration   1: 12.931 ops/ms
Iteration   2: 12.764 ops/ms
Iteration   3: 12.819 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.838 ±(99.9%) 1.560 ops/ms [Average]
  (min, avg, max) = (12.764, 12.838, 12.931), stdev = 0.086
  CI (99.9%): [11.278, 14.398] (assumes normal distribution)


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
# Warmup Iteration   1: 6.616 ops/ms
# Warmup Iteration   2: 10.628 ops/ms
# Warmup Iteration   3: 10.683 ops/ms
Iteration   1: 10.715 ops/ms
Iteration   2: 10.800 ops/ms
Iteration   3: 10.748 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.754 ±(99.9%) 0.780 ops/ms [Average]
  (min, avg, max) = (10.715, 10.754, 10.800), stdev = 0.043
  CI (99.9%): [9.975, 11.534] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:39
# Fork: 1 of 1
# Warmup Iteration   1: 3.966 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 2.566 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.511 ±(99.9%) 0.004 ms/op
Iteration   1: 2.541 ±(99.9%) 0.005 ms/op
Iteration   2: 2.520 ±(99.9%) 0.004 ms/op
Iteration   3: 2.547 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.536 ±(99.9%) 0.259 ms/op [Average]
  (min, avg, max) = (2.520, 2.536, 2.547), stdev = 0.014
  CI (99.9%): [2.277, 2.796] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:34
# Fork: 1 of 1
# Warmup Iteration   1: 3.464 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.461 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.448 ±(99.9%) 0.004 ms/op
Iteration   1: 2.435 ±(99.9%) 0.004 ms/op
Iteration   2: 2.438 ±(99.9%) 0.003 ms/op
Iteration   3: 2.445 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.439 ±(99.9%) 0.097 ms/op [Average]
  (min, avg, max) = (2.435, 2.439, 2.445), stdev = 0.005
  CI (99.9%): [2.343, 2.536] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:29
# Fork: 1 of 1
# Warmup Iteration   1: 3.941 ±(99.9%) 0.008 ms/op
# Warmup Iteration   2: 2.526 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.487 ±(99.9%) 0.004 ms/op
Iteration   1: 2.477 ±(99.9%) 0.004 ms/op
Iteration   2: 2.463 ±(99.9%) 0.004 ms/op
Iteration   3: 2.450 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.464 ±(99.9%) 0.246 ms/op [Average]
  (min, avg, max) = (2.450, 2.464, 2.477), stdev = 0.013
  CI (99.9%): [2.217, 2.710] (assumes normal distribution)


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
# Warmup Iteration   1: 4.387 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.011 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.963 ±(99.9%) 0.004 ms/op
Iteration   1: 2.952 ±(99.9%) 0.004 ms/op
Iteration   2: 2.937 ±(99.9%) 0.005 ms/op
Iteration   3: 2.936 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.941 ±(99.9%) 0.159 ms/op [Average]
  (min, avg, max) = (2.936, 2.941, 2.952), stdev = 0.009
  CI (99.9%): [2.782, 3.101] (assumes normal distribution)


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
# Warmup Iteration   1: 4.105 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 2.618 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.480 ±(99.9%) 0.005 ms/op
Iteration   1: 2.492 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.945 ms/op
                 createUser·p0.50:   2.585 ms/op
                 createUser·p0.90:   3.019 ms/op
                 createUser·p0.95:   3.129 ms/op
                 createUser·p0.99:   3.752 ms/op
                 createUser·p0.999:  9.844 ms/op
                 createUser·p0.9999: 13.156 ms/op
                 createUser·p1.00:   14.041 ms/op

Iteration   2: 2.475 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.880 ms/op
                 createUser·p0.50:   2.552 ms/op
                 createUser·p0.90:   2.994 ms/op
                 createUser·p0.95:   3.097 ms/op
                 createUser·p0.99:   3.638 ms/op
                 createUser·p0.999:  6.685 ms/op
                 createUser·p0.9999: 12.308 ms/op
                 createUser·p1.00:   12.763 ms/op

Iteration   3: 2.474 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.081 ms/op
                 createUser·p0.50:   2.540 ms/op
                 createUser·p0.90:   3.011 ms/op
                 createUser·p0.95:   3.129 ms/op
                 createUser·p0.99:   3.752 ms/op
                 createUser·p0.999:  8.072 ms/op
                 createUser·p0.9999: 10.669 ms/op
                 createUser·p1.00:   10.846 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 386647
  mean =      2.480 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 37 
    [ 1.250,  2.500) = 188576 
    [ 2.500,  3.750) = 194380 
    [ 3.750,  5.000) = 2975 
    [ 5.000,  6.250) = 264 
    [ 6.250,  7.500) = 24 
    [ 7.500,  8.750) = 38 
    [ 8.750, 10.000) = 64 
    [10.000, 11.250) = 78 
    [11.250, 12.500) = 168 
    [12.500, 13.750) = 40 
    [13.750, 15.000) = 3 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.880 ms/op
     p(50.0000) =      2.556 ms/op
     p(90.0000) =      3.006 ms/op
     p(95.0000) =      3.117 ms/op
     p(99.0000) =      3.719 ms/op
     p(99.9000) =      7.904 ms/op
     p(99.9900) =     12.730 ms/op
     p(99.9990) =     13.648 ms/op
     p(99.9999) =     14.041 ms/op
    p(100.0000) =     14.041 ms/op


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
# Warmup Iteration   1: 3.596 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 2.460 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.441 ±(99.9%) 0.005 ms/op
Iteration   1: 2.433 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.954 ms/op
                 existUser·p0.50:   2.499 ms/op
                 existUser·p0.90:   2.949 ms/op
                 existUser·p0.95:   3.035 ms/op
                 existUser·p0.99:   3.318 ms/op
                 existUser·p0.999:  5.770 ms/op
                 existUser·p0.9999: 13.713 ms/op
                 existUser·p1.00:   13.877 ms/op

Iteration   2: 2.455 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.954 ms/op
                 existUser·p0.50:   2.564 ms/op
                 existUser·p0.90:   2.978 ms/op
                 existUser·p0.95:   3.064 ms/op
                 existUser·p0.99:   3.396 ms/op
                 existUser·p0.999:  7.082 ms/op
                 existUser·p0.9999: 12.107 ms/op
                 existUser·p1.00:   12.878 ms/op

Iteration   3: 2.439 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.825 ms/op
                 existUser·p0.50:   2.462 ms/op
                 existUser·p0.90:   2.974 ms/op
                 existUser·p0.95:   3.076 ms/op
                 existUser·p0.99:   3.633 ms/op
                 existUser·p0.999:  5.603 ms/op
                 existUser·p0.9999: 11.692 ms/op
                 existUser·p1.00:   12.747 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 392599
  mean =      2.442 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 48 
    [ 1.250,  2.500) = 196197 
    [ 2.500,  3.750) = 193903 
    [ 3.750,  5.000) = 1809 
    [ 5.000,  6.250) = 278 
    [ 6.250,  7.500) = 11 
    [ 7.500,  8.750) = 22 
    [ 8.750, 10.000) = 68 
    [10.000, 11.250) = 82 
    [11.250, 12.500) = 95 
    [12.500, 13.750) = 77 
    [13.750, 15.000) = 9 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.825 ms/op
     p(50.0000) =      2.503 ms/op
     p(90.0000) =      2.966 ms/op
     p(95.0000) =      3.060 ms/op
     p(99.0000) =      3.441 ms/op
     p(99.9000) =      5.836 ms/op
     p(99.9900) =     12.911 ms/op
     p(99.9990) =     13.828 ms/op
     p(99.9999) =     13.877 ms/op
    p(100.0000) =     13.877 ms/op


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
# Warmup Iteration   1: 4.028 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 2.557 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.478 ±(99.9%) 0.005 ms/op
Iteration   1: 2.493 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.959 ms/op
                 getUser·p0.50:   2.499 ms/op
                 getUser·p0.90:   3.052 ms/op
                 getUser·p0.95:   3.178 ms/op
                 getUser·p0.99:   3.731 ms/op
                 getUser·p0.999:  10.435 ms/op
                 getUser·p0.9999: 14.112 ms/op
                 getUser·p1.00:   14.746 ms/op

Iteration   2: 2.513 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.931 ms/op
                 getUser·p0.50:   2.531 ms/op
                 getUser·p0.90:   3.064 ms/op
                 getUser·p0.95:   3.244 ms/op
                 getUser·p0.99:   4.563 ms/op
                 getUser·p0.999:  6.196 ms/op
                 getUser·p0.9999: 12.019 ms/op
                 getUser·p1.00:   12.829 ms/op

Iteration   3: 2.449 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.010 ms/op
                 getUser·p0.50:   2.462 ms/op
                 getUser·p0.90:   2.982 ms/op
                 getUser·p0.95:   3.092 ms/op
                 getUser·p0.99:   3.662 ms/op
                 getUser·p0.999:  6.774 ms/op
                 getUser·p0.9999: 12.435 ms/op
                 getUser·p1.00:   13.468 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 386019
  mean =      2.485 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 85 
    [ 1.250,  2.500) = 192937 
    [ 2.500,  3.750) = 187966 
    [ 3.750,  5.000) = 4038 
    [ 5.000,  6.250) = 605 
    [ 6.250,  7.500) = 36 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 38 
    [10.000, 11.250) = 119 
    [11.250, 12.500) = 97 
    [12.500, 13.750) = 83 
    [13.750, 15.000) = 15 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.931 ms/op
     p(50.0000) =      2.499 ms/op
     p(90.0000) =      3.031 ms/op
     p(95.0000) =      3.166 ms/op
     p(99.0000) =      3.932 ms/op
     p(99.9000) =      6.291 ms/op
     p(99.9900) =     13.130 ms/op
     p(99.9990) =     14.420 ms/op
     p(99.9999) =     14.746 ms/op
    p(100.0000) =     14.746 ms/op


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
# Warmup Iteration   1: 4.749 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 3.093 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.019 ±(99.9%) 0.008 ms/op
Iteration   1: 2.995 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.834 ms/op
                 listUser·p0.50:   2.949 ms/op
                 listUser·p0.90:   3.850 ms/op
                 listUser·p0.95:   4.342 ms/op
                 listUser·p0.99:   5.431 ms/op
                 listUser·p0.999:  8.966 ms/op
                 listUser·p0.9999: 11.370 ms/op
                 listUser·p1.00:   11.928 ms/op

Iteration   2: 2.974 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.995 ms/op
                 listUser·p0.50:   2.925 ms/op
                 listUser·p0.90:   3.805 ms/op
                 listUser·p0.95:   4.276 ms/op
                 listUser·p0.99:   5.415 ms/op
                 listUser·p0.999:  9.044 ms/op
                 listUser·p0.9999: 10.842 ms/op
                 listUser·p1.00:   11.436 ms/op

Iteration   3: 2.996 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.778 ms/op
                 listUser·p0.50:   2.933 ms/op
                 listUser·p0.90:   3.874 ms/op
                 listUser·p0.95:   4.358 ms/op
                 listUser·p0.99:   5.538 ms/op
                 listUser·p0.999:  9.442 ms/op
                 listUser·p0.9999: 13.538 ms/op
                 listUser·p1.00:   14.385 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 320965
  mean =      2.988 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 169 
    [ 1.250,  2.500) = 97138 
    [ 2.500,  3.750) = 186530 
    [ 3.750,  5.000) = 30721 
    [ 5.000,  6.250) = 5291 
    [ 6.250,  7.500) = 497 
    [ 7.500,  8.750) = 228 
    [ 8.750, 10.000) = 216 
    [10.000, 11.250) = 117 
    [11.250, 12.500) = 32 
    [12.500, 13.750) = 20 
    [13.750, 15.000) = 6 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.778 ms/op
     p(50.0000) =      2.937 ms/op
     p(90.0000) =      3.842 ms/op
     p(95.0000) =      4.325 ms/op
     p(99.0000) =      5.464 ms/op
     p(99.9000) =      9.224 ms/op
     p(99.9900) =     11.972 ms/op
     p(99.9990) =     13.874 ms/op
     p(99.9999) =     14.385 ms/op
    p(100.0000) =     14.385 ms/op


# Run complete. Total time: 00:12:58

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.667 ± 1.391  ops/ms
ClientPb.existUser                       thrpt       3  13.205 ± 0.780  ops/ms
ClientPb.getUser                         thrpt       3  12.838 ± 1.560  ops/ms
ClientPb.listUser                        thrpt       3  10.754 ± 0.780  ops/ms
ClientPb.createUser                       avgt       3   2.536 ± 0.259   ms/op
ClientPb.existUser                        avgt       3   2.439 ± 0.097   ms/op
ClientPb.getUser                          avgt       3   2.464 ± 0.246   ms/op
ClientPb.listUser                         avgt       3   2.941 ± 0.159   ms/op
ClientPb.createUser                     sample  386647   2.480 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.880           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.556           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.006           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.117           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.719           ms/op
ClientPb.createUser:createUser·p0.999   sample           7.904           ms/op
ClientPb.createUser:createUser·p0.9999  sample          12.730           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.041           ms/op
ClientPb.existUser                      sample  392599   2.442 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.825           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.503           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.966           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.060           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.441           ms/op
ClientPb.existUser:existUser·p0.999     sample           5.836           ms/op
ClientPb.existUser:existUser·p0.9999    sample          12.911           ms/op
ClientPb.existUser:existUser·p1.00      sample          13.877           ms/op
ClientPb.getUser                        sample  386019   2.485 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.931           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.499           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.031           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.166           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.932           ms/op
ClientPb.getUser:getUser·p0.999         sample           6.291           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.130           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.746           ms/op
ClientPb.listUser                       sample  320965   2.988 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.778           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.937           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.842           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.325           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.464           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.224           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.972           ms/op
ClientPb.listUser:listUser·p1.00        sample          14.385           ms/op
