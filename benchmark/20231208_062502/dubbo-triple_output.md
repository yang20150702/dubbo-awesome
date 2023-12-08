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
# Warmup Iteration   1: 5.278 ops/ms
# Warmup Iteration   2: 12.107 ops/ms
# Warmup Iteration   3: 12.478 ops/ms
Iteration   1: 12.785 ops/ms
Iteration   2: 12.821 ops/ms
Iteration   3: 12.857 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.821 ±(99.9%) 0.657 ops/ms [Average]
  (min, avg, max) = (12.785, 12.821, 12.857), stdev = 0.036
  CI (99.9%): [12.165, 13.478] (assumes normal distribution)


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
# Warmup Iteration   1: 7.949 ops/ms
# Warmup Iteration   2: 12.920 ops/ms
# Warmup Iteration   3: 13.164 ops/ms
Iteration   1: 13.066 ops/ms
Iteration   2: 13.116 ops/ms
Iteration   3: 13.107 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.096 ±(99.9%) 0.492 ops/ms [Average]
  (min, avg, max) = (13.066, 13.096, 13.116), stdev = 0.027
  CI (99.9%): [12.604, 13.589] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:46
# Fork: 1 of 1
# Warmup Iteration   1: 7.966 ops/ms
# Warmup Iteration   2: 12.468 ops/ms
# Warmup Iteration   3: 12.823 ops/ms
Iteration   1: 12.934 ops/ms
Iteration   2: 12.954 ops/ms
Iteration   3: 12.937 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.942 ±(99.9%) 0.193 ops/ms [Average]
  (min, avg, max) = (12.934, 12.942, 12.954), stdev = 0.011
  CI (99.9%): [12.748, 13.135] (assumes normal distribution)


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
# Warmup Iteration   1: 6.963 ops/ms
# Warmup Iteration   2: 10.511 ops/ms
# Warmup Iteration   3: 10.677 ops/ms
Iteration   1: 10.873 ops/ms
Iteration   2: 10.805 ops/ms
Iteration   3: 10.867 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.848 ±(99.9%) 0.687 ops/ms [Average]
  (min, avg, max) = (10.805, 10.848, 10.873), stdev = 0.038
  CI (99.9%): [10.161, 11.535] (assumes normal distribution)


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
# Warmup Iteration   1: 4.055 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 2.563 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.481 ±(99.9%) 0.004 ms/op
Iteration   1: 2.529 ±(99.9%) 0.004 ms/op
Iteration   2: 2.573 ±(99.9%) 0.003 ms/op
Iteration   3: 2.530 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.544 ±(99.9%) 0.454 ms/op [Average]
  (min, avg, max) = (2.529, 2.544, 2.573), stdev = 0.025
  CI (99.9%): [2.090, 2.998] (assumes normal distribution)


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
# Warmup Iteration   1: 3.665 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.428 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.431 ±(99.9%) 0.005 ms/op
Iteration   1: 2.432 ±(99.9%) 0.004 ms/op
Iteration   2: 2.423 ±(99.9%) 0.004 ms/op
Iteration   3: 2.451 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.436 ±(99.9%) 0.253 ms/op [Average]
  (min, avg, max) = (2.423, 2.436, 2.451), stdev = 0.014
  CI (99.9%): [2.182, 2.689] (assumes normal distribution)


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
# Warmup Iteration   1: 3.863 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.543 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.518 ±(99.9%) 0.004 ms/op
Iteration   1: 2.511 ±(99.9%) 0.004 ms/op
Iteration   2: 2.495 ±(99.9%) 0.004 ms/op
Iteration   3: 2.495 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.500 ±(99.9%) 0.167 ms/op [Average]
  (min, avg, max) = (2.495, 2.500, 2.511), stdev = 0.009
  CI (99.9%): [2.333, 2.667] (assumes normal distribution)


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
# Warmup Iteration   1: 4.563 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.007 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.952 ±(99.9%) 0.006 ms/op
Iteration   1: 2.931 ±(99.9%) 0.006 ms/op
Iteration   2: 2.981 ±(99.9%) 0.006 ms/op
Iteration   3: 2.973 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.961 ±(99.9%) 0.488 ms/op [Average]
  (min, avg, max) = (2.931, 2.961, 2.981), stdev = 0.027
  CI (99.9%): [2.473, 3.450] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:18
# Fork: 1 of 1
# Warmup Iteration   1: 4.100 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 2.609 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.535 ±(99.9%) 0.005 ms/op
Iteration   1: 2.522 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.994 ms/op
                 createUser·p0.50:   2.585 ms/op
                 createUser·p0.90:   3.068 ms/op
                 createUser·p0.95:   3.211 ms/op
                 createUser·p0.99:   3.957 ms/op
                 createUser·p0.999:  11.549 ms/op
                 createUser·p0.9999: 14.074 ms/op
                 createUser·p1.00:   14.746 ms/op

Iteration   2: 2.477 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.024 ms/op
                 createUser·p0.50:   2.576 ms/op
                 createUser·p0.90:   3.002 ms/op
                 createUser·p0.95:   3.097 ms/op
                 createUser·p0.99:   3.445 ms/op
                 createUser·p0.999:  10.075 ms/op
                 createUser·p0.9999: 13.976 ms/op
                 createUser·p1.00:   14.320 ms/op

Iteration   3: 2.506 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.007 ms/op
                 createUser·p0.50:   2.572 ms/op
                 createUser·p0.90:   3.043 ms/op
                 createUser·p0.95:   3.174 ms/op
                 createUser·p0.99:   3.842 ms/op
                 createUser·p0.999:  8.715 ms/op
                 createUser·p0.9999: 10.093 ms/op
                 createUser·p1.00:   13.337 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 383394
  mean =      2.501 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 48 
    [ 1.250,  2.500) = 185398 
    [ 2.500,  3.750) = 193973 
    [ 3.750,  5.000) = 3079 
    [ 5.000,  6.250) = 302 
    [ 6.250,  7.500) = 78 
    [ 7.500,  8.750) = 104 
    [ 8.750, 10.000) = 136 
    [10.000, 11.250) = 77 
    [11.250, 12.500) = 44 
    [12.500, 13.750) = 119 
    [13.750, 15.000) = 36 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.994 ms/op
     p(50.0000) =      2.576 ms/op
     p(90.0000) =      3.035 ms/op
     p(95.0000) =      3.158 ms/op
     p(99.0000) =      3.772 ms/op
     p(99.9000) =      9.057 ms/op
     p(99.9900) =     13.713 ms/op
     p(99.9990) =     14.699 ms/op
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
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.607 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 2.441 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.408 ±(99.9%) 0.005 ms/op
Iteration   1: 2.419 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.895 ms/op
                 existUser·p0.50:   2.433 ms/op
                 existUser·p0.90:   2.953 ms/op
                 existUser·p0.95:   3.088 ms/op
                 existUser·p0.99:   3.867 ms/op
                 existUser·p0.999:  6.638 ms/op
                 existUser·p0.9999: 15.426 ms/op
                 existUser·p1.00:   16.482 ms/op

Iteration   2: 2.400 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.796 ms/op
                 existUser·p0.50:   2.478 ms/op
                 existUser·p0.90:   2.912 ms/op
                 existUser·p0.95:   3.027 ms/op
                 existUser·p0.99:   3.682 ms/op
                 existUser·p0.999:  7.572 ms/op
                 existUser·p0.9999: 14.140 ms/op
                 existUser·p1.00:   14.909 ms/op

Iteration   3: 2.423 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.871 ms/op
                 existUser·p0.50:   2.511 ms/op
                 existUser·p0.90:   2.949 ms/op
                 existUser·p0.95:   3.064 ms/op
                 existUser·p0.99:   3.801 ms/op
                 existUser·p0.999:  6.415 ms/op
                 existUser·p0.9999: 11.203 ms/op
                 existUser·p1.00:   12.157 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 397442
  mean =      2.414 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 70 
    [ 1.250,  2.500) = 202561 
    [ 2.500,  3.750) = 190655 
    [ 3.750,  5.000) = 3234 
    [ 5.000,  6.250) = 494 
    [ 6.250,  7.500) = 37 
    [ 7.500,  8.750) = 19 
    [ 8.750, 10.000) = 47 
    [10.000, 11.250) = 91 
    [11.250, 12.500) = 95 
    [12.500, 13.750) = 92 
    [13.750, 15.000) = 26 
    [15.000, 16.250) = 14 
    [16.250, 17.500) = 7 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.796 ms/op
     p(50.0000) =      2.470 ms/op
     p(90.0000) =      2.937 ms/op
     p(95.0000) =      3.060 ms/op
     p(99.0000) =      3.789 ms/op
     p(99.9000) =      7.067 ms/op
     p(99.9900) =     14.107 ms/op
     p(99.9990) =     16.319 ms/op
     p(99.9999) =     16.482 ms/op
    p(100.0000) =     16.482 ms/op


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
# Warmup Iteration   1: 3.794 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 2.535 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.497 ±(99.9%) 0.006 ms/op
Iteration   1: 2.482 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.936 ms/op
                 getUser·p0.50:   2.499 ms/op
                 getUser·p0.90:   3.027 ms/op
                 getUser·p0.95:   3.150 ms/op
                 getUser·p0.99:   3.764 ms/op
                 getUser·p0.999:  8.015 ms/op
                 getUser·p0.9999: 13.668 ms/op
                 getUser·p1.00:   13.828 ms/op

Iteration   2: 2.482 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.014 ms/op
                 getUser·p0.50:   2.507 ms/op
                 getUser·p0.90:   3.011 ms/op
                 getUser·p0.95:   3.133 ms/op
                 getUser·p0.99:   4.022 ms/op
                 getUser·p0.999:  7.849 ms/op
                 getUser·p0.9999: 12.765 ms/op
                 getUser·p1.00:   12.993 ms/op

Iteration   3: 2.500 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.864 ms/op
                 getUser·p0.50:   2.531 ms/op
                 getUser·p0.90:   3.039 ms/op
                 getUser·p0.95:   3.232 ms/op
                 getUser·p0.99:   4.358 ms/op
                 getUser·p0.999:  9.098 ms/op
                 getUser·p0.9999: 14.647 ms/op
                 getUser·p1.00:   15.385 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 385574
  mean =      2.488 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 62 
    [ 1.250,  2.500) = 191762 
    [ 2.500,  3.750) = 187579 
    [ 3.750,  5.000) = 4763 
    [ 5.000,  6.250) = 888 
    [ 6.250,  7.500) = 129 
    [ 7.500,  8.750) = 7 
    [ 8.750, 10.000) = 22 
    [10.000, 11.250) = 100 
    [11.250, 12.500) = 122 
    [12.500, 13.750) = 101 
    [13.750, 15.000) = 29 
    [15.000, 16.250) = 10 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.864 ms/op
     p(50.0000) =      2.511 ms/op
     p(90.0000) =      3.023 ms/op
     p(95.0000) =      3.166 ms/op
     p(99.0000) =      4.133 ms/op
     p(99.9000) =      7.866 ms/op
     p(99.9900) =     13.770 ms/op
     p(99.9990) =     15.207 ms/op
     p(99.9999) =     15.385 ms/op
    p(100.0000) =     15.385 ms/op


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
# Warmup Iteration   1: 4.687 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 3.035 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.962 ±(99.9%) 0.008 ms/op
Iteration   1: 2.961 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.731 ms/op
                 listUser·p0.50:   2.900 ms/op
                 listUser·p0.90:   3.867 ms/op
                 listUser·p0.95:   4.358 ms/op
                 listUser·p0.99:   5.603 ms/op
                 listUser·p0.999:  9.274 ms/op
                 listUser·p0.9999: 10.912 ms/op
                 listUser·p1.00:   11.993 ms/op

Iteration   2: 2.958 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.734 ms/op
                 listUser·p0.50:   2.896 ms/op
                 listUser·p0.90:   3.805 ms/op
                 listUser·p0.95:   4.309 ms/op
                 listUser·p0.99:   5.480 ms/op
                 listUser·p0.999:  9.599 ms/op
                 listUser·p0.9999: 13.995 ms/op
                 listUser·p1.00:   14.221 ms/op

Iteration   3: 2.970 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.818 ms/op
                 listUser·p0.50:   2.892 ms/op
                 listUser·p0.90:   3.871 ms/op
                 listUser·p0.95:   4.399 ms/op
                 listUser·p0.99:   5.562 ms/op
                 listUser·p0.999:  9.683 ms/op
                 listUser·p0.9999: 11.354 ms/op
                 listUser·p1.00:   12.354 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 323730
  mean =      2.963 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 139 
    [ 1.250,  2.500) = 103771 
    [ 2.500,  3.750) = 182427 
    [ 3.750,  5.000) = 30199 
    [ 5.000,  6.250) = 5844 
    [ 6.250,  7.500) = 598 
    [ 7.500,  8.750) = 226 
    [ 8.750, 10.000) = 320 
    [10.000, 11.250) = 151 
    [11.250, 12.500) = 28 
    [12.500, 13.750) = 16 
    [13.750, 15.000) = 11 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.731 ms/op
     p(50.0000) =      2.896 ms/op
     p(90.0000) =      3.846 ms/op
     p(95.0000) =      4.358 ms/op
     p(99.0000) =      5.554 ms/op
     p(99.9000) =      9.552 ms/op
     p(99.9900) =     12.145 ms/op
     p(99.9990) =     14.107 ms/op
     p(99.9999) =     14.221 ms/op
    p(100.0000) =     14.221 ms/op


# Run complete. Total time: 00:12:58

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.821 ± 0.657  ops/ms
ClientPb.existUser                       thrpt       3  13.096 ± 0.492  ops/ms
ClientPb.getUser                         thrpt       3  12.942 ± 0.193  ops/ms
ClientPb.listUser                        thrpt       3  10.848 ± 0.687  ops/ms
ClientPb.createUser                       avgt       3   2.544 ± 0.454   ms/op
ClientPb.existUser                        avgt       3   2.436 ± 0.253   ms/op
ClientPb.getUser                          avgt       3   2.500 ± 0.167   ms/op
ClientPb.listUser                         avgt       3   2.961 ± 0.488   ms/op
ClientPb.createUser                     sample  383394   2.501 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.994           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.576           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.035           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.158           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.772           ms/op
ClientPb.createUser:createUser·p0.999   sample           9.057           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.713           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.746           ms/op
ClientPb.existUser                      sample  397442   2.414 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.796           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.470           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.937           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.060           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.789           ms/op
ClientPb.existUser:existUser·p0.999     sample           7.067           ms/op
ClientPb.existUser:existUser·p0.9999    sample          14.107           ms/op
ClientPb.existUser:existUser·p1.00      sample          16.482           ms/op
ClientPb.getUser                        sample  385574   2.488 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.864           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.511           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.023           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.166           ms/op
ClientPb.getUser:getUser·p0.99          sample           4.133           ms/op
ClientPb.getUser:getUser·p0.999         sample           7.866           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.770           ms/op
ClientPb.getUser:getUser·p1.00          sample          15.385           ms/op
ClientPb.listUser                       sample  323730   2.963 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.731           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.896           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.846           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.358           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.554           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.552           ms/op
ClientPb.listUser:listUser·p0.9999      sample          12.145           ms/op
ClientPb.listUser:listUser·p1.00        sample          14.221           ms/op
