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
# Warmup Iteration   1: 5.380 ops/ms
# Warmup Iteration   2: 12.354 ops/ms
# Warmup Iteration   3: 12.387 ops/ms
Iteration   1: 12.608 ops/ms
Iteration   2: 12.695 ops/ms
Iteration   3: 12.694 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.665 ±(99.9%) 0.910 ops/ms [Average]
  (min, avg, max) = (12.608, 12.665, 12.695), stdev = 0.050
  CI (99.9%): [11.755, 13.576] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:53
# Fork: 1 of 1
# Warmup Iteration   1: 8.411 ops/ms
# Warmup Iteration   2: 12.858 ops/ms
# Warmup Iteration   3: 12.959 ops/ms
Iteration   1: 13.004 ops/ms
Iteration   2: 13.012 ops/ms
Iteration   3: 12.916 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.977 ±(99.9%) 0.976 ops/ms [Average]
  (min, avg, max) = (12.916, 12.977, 13.012), stdev = 0.053
  CI (99.9%): [12.002, 13.953] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:48
# Fork: 1 of 1
# Warmup Iteration   1: 7.453 ops/ms
# Warmup Iteration   2: 12.642 ops/ms
# Warmup Iteration   3: 13.057 ops/ms
Iteration   1: 13.070 ops/ms
Iteration   2: 13.083 ops/ms
Iteration   3: 12.933 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  13.028 ±(99.9%) 1.517 ops/ms [Average]
  (min, avg, max) = (12.933, 13.028, 13.083), stdev = 0.083
  CI (99.9%): [11.511, 14.545] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:43
# Fork: 1 of 1
# Warmup Iteration   1: 6.906 ops/ms
# Warmup Iteration   2: 10.444 ops/ms
# Warmup Iteration   3: 10.727 ops/ms
Iteration   1: 10.764 ops/ms
Iteration   2: 10.707 ops/ms
Iteration   3: 10.705 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.725 ±(99.9%) 0.612 ops/ms [Average]
  (min, avg, max) = (10.705, 10.725, 10.764), stdev = 0.034
  CI (99.9%): [10.113, 11.337] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:38
# Fork: 1 of 1
# Warmup Iteration   1: 3.706 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 2.550 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.466 ±(99.9%) 0.004 ms/op
Iteration   1: 2.467 ±(99.9%) 0.005 ms/op
Iteration   2: 2.521 ±(99.9%) 0.004 ms/op
Iteration   3: 2.470 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.486 ±(99.9%) 0.554 ms/op [Average]
  (min, avg, max) = (2.467, 2.486, 2.521), stdev = 0.030
  CI (99.9%): [1.932, 3.040] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:34
# Fork: 1 of 1
# Warmup Iteration   1: 3.712 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.415 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.451 ±(99.9%) 0.003 ms/op
Iteration   1: 2.449 ±(99.9%) 0.003 ms/op
Iteration   2: 2.431 ±(99.9%) 0.003 ms/op
Iteration   3: 2.492 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.457 ±(99.9%) 0.567 ms/op [Average]
  (min, avg, max) = (2.431, 2.457, 2.492), stdev = 0.031
  CI (99.9%): [1.890, 3.025] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:29
# Fork: 1 of 1
# Warmup Iteration   1: 4.013 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.541 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.515 ±(99.9%) 0.003 ms/op
Iteration   1: 2.497 ±(99.9%) 0.004 ms/op
Iteration   2: 2.495 ±(99.9%) 0.004 ms/op
Iteration   3: 2.507 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.500 ±(99.9%) 0.120 ms/op [Average]
  (min, avg, max) = (2.495, 2.500, 2.507), stdev = 0.007
  CI (99.9%): [2.380, 2.620] (assumes normal distribution)


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
# Warmup Iteration   1: 4.907 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.063 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.037 ±(99.9%) 0.005 ms/op
Iteration   1: 2.990 ±(99.9%) 0.004 ms/op
Iteration   2: 3.015 ±(99.9%) 0.005 ms/op
Iteration   3: 3.027 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.011 ±(99.9%) 0.352 ms/op [Average]
  (min, avg, max) = (2.990, 3.011, 3.027), stdev = 0.019
  CI (99.9%): [2.659, 3.362] (assumes normal distribution)


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
# Warmup Iteration   1: 4.089 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 2.698 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.541 ±(99.9%) 0.006 ms/op
Iteration   1: 2.515 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.657 ms/op
                 createUser·p0.50:   2.576 ms/op
                 createUser·p0.90:   3.060 ms/op
                 createUser·p0.95:   3.195 ms/op
                 createUser·p0.99:   3.801 ms/op
                 createUser·p0.999:  11.975 ms/op
                 createUser·p0.9999: 13.648 ms/op
                 createUser·p1.00:   14.598 ms/op

Iteration   2: 2.559 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.880 ms/op
                 createUser·p0.50:   2.634 ms/op
                 createUser·p0.90:   3.092 ms/op
                 createUser·p0.95:   3.219 ms/op
                 createUser·p0.99:   4.088 ms/op
                 createUser·p0.999:  9.193 ms/op
                 createUser·p0.9999: 13.099 ms/op
                 createUser·p1.00:   13.828 ms/op

Iteration   3: 2.539 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.975 ms/op
                 createUser·p0.50:   2.556 ms/op
                 createUser·p0.90:   3.092 ms/op
                 createUser·p0.95:   3.228 ms/op
                 createUser·p0.99:   4.014 ms/op
                 createUser·p0.999:  7.922 ms/op
                 createUser·p0.9999: 10.558 ms/op
                 createUser·p1.00:   10.781 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 377974
  mean =      2.538 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 59 
    [ 1.250,  2.500) = 181380 
    [ 2.500,  3.750) = 191399 
    [ 3.750,  5.000) = 4126 
    [ 5.000,  6.250) = 570 
    [ 6.250,  7.500) = 53 
    [ 7.500,  8.750) = 29 
    [ 8.750, 10.000) = 108 
    [10.000, 11.250) = 58 
    [11.250, 12.500) = 72 
    [12.500, 13.750) = 111 
    [13.750, 15.000) = 9 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.657 ms/op
     p(50.0000) =      2.585 ms/op
     p(90.0000) =      3.084 ms/op
     p(95.0000) =      3.215 ms/op
     p(99.0000) =      3.961 ms/op
     p(99.9000) =      8.037 ms/op
     p(99.9900) =     13.304 ms/op
     p(99.9990) =     14.181 ms/op
     p(99.9999) =     14.598 ms/op
    p(100.0000) =     14.598 ms/op


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
# Warmup Iteration   1: 3.636 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 2.425 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.442 ±(99.9%) 0.005 ms/op
Iteration   1: 2.433 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.945 ms/op
                 existUser·p0.50:   2.462 ms/op
                 existUser·p0.90:   2.961 ms/op
                 existUser·p0.95:   3.076 ms/op
                 existUser·p0.99:   3.654 ms/op
                 existUser·p0.999:  6.198 ms/op
                 existUser·p0.9999: 13.498 ms/op
                 existUser·p1.00:   13.894 ms/op

Iteration   2: 2.437 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.942 ms/op
                 existUser·p0.50:   2.490 ms/op
                 existUser·p0.90:   2.957 ms/op
                 existUser·p0.95:   3.064 ms/op
                 existUser·p0.99:   3.752 ms/op
                 existUser·p0.999:  7.216 ms/op
                 existUser·p0.9999: 13.185 ms/op
                 existUser·p1.00:   14.336 ms/op

Iteration   3: 2.453 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.953 ms/op
                 existUser·p0.50:   2.515 ms/op
                 existUser·p0.90:   2.990 ms/op
                 existUser·p0.95:   3.105 ms/op
                 existUser·p0.99:   3.719 ms/op
                 existUser·p0.999:  5.792 ms/op
                 existUser·p0.9999: 11.681 ms/op
                 existUser·p1.00:   12.419 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 392932
  mean =      2.441 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 65 
    [ 1.250,  2.500) = 197437 
    [ 2.500,  3.750) = 191746 
    [ 3.750,  5.000) = 2775 
    [ 5.000,  6.250) = 456 
    [ 6.250,  7.500) = 78 
    [ 7.500,  8.750) = 41 
    [ 8.750, 10.000) = 40 
    [10.000, 11.250) = 62 
    [11.250, 12.500) = 113 
    [12.500, 13.750) = 110 
    [13.750, 15.000) = 9 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.942 ms/op
     p(50.0000) =      2.490 ms/op
     p(90.0000) =      2.970 ms/op
     p(95.0000) =      3.080 ms/op
     p(99.0000) =      3.707 ms/op
     p(99.9000) =      7.169 ms/op
     p(99.9900) =     13.184 ms/op
     p(99.9990) =     14.272 ms/op
     p(99.9999) =     14.336 ms/op
    p(100.0000) =     14.336 ms/op


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
# Warmup Iteration   1: 3.750 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 2.567 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.533 ±(99.9%) 0.005 ms/op
Iteration   1: 2.543 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.906 ms/op
                 getUser·p0.50:   2.552 ms/op
                 getUser·p0.90:   3.097 ms/op
                 getUser·p0.95:   3.248 ms/op
                 getUser·p0.99:   4.100 ms/op
                 getUser·p0.999:  12.609 ms/op
                 getUser·p0.9999: 20.977 ms/op
                 getUser·p1.00:   21.529 ms/op

Iteration   2: 2.578 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   1.021 ms/op
                 getUser·p0.50:   2.597 ms/op
                 getUser·p0.90:   3.113 ms/op
                 getUser·p0.95:   3.285 ms/op
                 getUser·p0.99:   5.145 ms/op
                 getUser·p0.999:  12.156 ms/op
                 getUser·p0.9999: 22.571 ms/op
                 getUser·p1.00:   23.233 ms/op

Iteration   3: 2.513 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.833 ms/op
                 getUser·p0.50:   2.556 ms/op
                 getUser·p0.90:   3.064 ms/op
                 getUser·p0.95:   3.195 ms/op
                 getUser·p0.99:   3.858 ms/op
                 getUser·p0.999:  8.745 ms/op
                 getUser·p0.9999: 10.963 ms/op
                 getUser·p1.00:   11.993 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 376926
  mean =      2.545 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 183682 
    [ 2.500,  5.000) = 191110 
    [ 5.000,  7.500) = 1620 
    [ 7.500, 10.000) = 159 
    [10.000, 12.500) = 139 
    [12.500, 15.000) = 152 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 2 
    [20.000, 22.500) = 49 
    [22.500, 25.000) = 13 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.833 ms/op
     p(50.0000) =      2.568 ms/op
     p(90.0000) =      3.088 ms/op
     p(95.0000) =      3.240 ms/op
     p(99.0000) =      4.317 ms/op
     p(99.9000) =      9.701 ms/op
     p(99.9900) =     21.145 ms/op
     p(99.9990) =     23.149 ms/op
     p(99.9999) =     23.233 ms/op
    p(100.0000) =     23.233 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 4.984 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 3.120 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.065 ±(99.9%) 0.009 ms/op
Iteration   1: 3.057 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.721 ms/op
                 listUser·p0.50:   3.002 ms/op
                 listUser·p0.90:   3.953 ms/op
                 listUser·p0.95:   4.456 ms/op
                 listUser·p0.99:   5.726 ms/op
                 listUser·p0.999:  9.142 ms/op
                 listUser·p0.9999: 10.652 ms/op
                 listUser·p1.00:   11.469 ms/op

Iteration   2: 3.067 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.059 ms/op
                 listUser·p0.50:   2.994 ms/op
                 listUser·p0.90:   4.002 ms/op
                 listUser·p0.95:   4.522 ms/op
                 listUser·p0.99:   5.775 ms/op
                 listUser·p0.999:  9.994 ms/op
                 listUser·p0.9999: 11.890 ms/op
                 listUser·p1.00:   12.780 ms/op

Iteration   3: 3.025 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.818 ms/op
                 listUser·p0.50:   2.974 ms/op
                 listUser·p0.90:   3.871 ms/op
                 listUser·p0.95:   4.342 ms/op
                 listUser·p0.99:   5.439 ms/op
                 listUser·p0.999:  8.689 ms/op
                 listUser·p0.9999: 10.139 ms/op
                 listUser·p1.00:   10.699 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 314551
  mean =      3.050 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 119 
    [ 1.250,  2.500) = 86096 
    [ 2.500,  3.750) = 186425 
    [ 3.750,  5.000) = 34195 
    [ 5.000,  6.250) = 6323 
    [ 6.250,  7.500) = 743 
    [ 7.500,  8.750) = 235 
    [ 8.750, 10.000) = 245 
    [10.000, 11.250) = 137 
    [11.250, 12.500) = 27 
    [12.500, 13.750) = 6 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.721 ms/op
     p(50.0000) =      2.990 ms/op
     p(90.0000) =      3.940 ms/op
     p(95.0000) =      4.440 ms/op
     p(99.0000) =      5.644 ms/op
     p(99.9000) =      9.093 ms/op
     p(99.9900) =     11.256 ms/op
     p(99.9990) =     12.632 ms/op
     p(99.9999) =     12.780 ms/op
    p(100.0000) =     12.780 ms/op


# Run complete. Total time: 00:13:01

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.665 ± 0.910  ops/ms
ClientPb.existUser                       thrpt       3  12.977 ± 0.976  ops/ms
ClientPb.getUser                         thrpt       3  13.028 ± 1.517  ops/ms
ClientPb.listUser                        thrpt       3  10.725 ± 0.612  ops/ms
ClientPb.createUser                       avgt       3   2.486 ± 0.554   ms/op
ClientPb.existUser                        avgt       3   2.457 ± 0.567   ms/op
ClientPb.getUser                          avgt       3   2.500 ± 0.120   ms/op
ClientPb.listUser                         avgt       3   3.011 ± 0.352   ms/op
ClientPb.createUser                     sample  377974   2.538 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.657           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.585           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.084           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.215           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.961           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.037           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.304           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.598           ms/op
ClientPb.existUser                      sample  392932   2.441 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.942           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.490           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.970           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.080           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.707           ms/op
ClientPb.existUser:existUser·p0.999     sample           7.169           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.184           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.336           ms/op
ClientPb.getUser                        sample  376926   2.545 ± 0.004   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.833           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.568           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.088           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.240           ms/op
ClientPb.getUser:getUser·p0.99          sample           4.317           ms/op
ClientPb.getUser:getUser·p0.999         sample           9.701           ms/op
ClientPb.getUser:getUser·p0.9999        sample          21.145           ms/op
ClientPb.getUser:getUser·p1.00          sample          23.233           ms/op
ClientPb.listUser                       sample  314551   3.050 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.721           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.990           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.940           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.440           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.644           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.093           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.256           ms/op
ClientPb.listUser:listUser·p1.00        sample          12.780           ms/op
