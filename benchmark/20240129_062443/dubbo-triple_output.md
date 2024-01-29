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
# Warmup Iteration   1: 4.910 ops/ms
# Warmup Iteration   2: 11.896 ops/ms
# Warmup Iteration   3: 12.440 ops/ms
Iteration   1: 12.473 ops/ms
Iteration   2: 12.586 ops/ms
Iteration   3: 12.719 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.593 ±(99.9%) 2.247 ops/ms [Average]
  (min, avg, max) = (12.473, 12.593, 12.719), stdev = 0.123
  CI (99.9%): [10.345, 14.840] (assumes normal distribution)


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
# Warmup Iteration   1: 8.171 ops/ms
# Warmup Iteration   2: 12.903 ops/ms
# Warmup Iteration   3: 13.210 ops/ms
Iteration   1: 13.290 ops/ms
Iteration   2: 13.243 ops/ms
Iteration   3: 13.224 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.252 ±(99.9%) 0.621 ops/ms [Average]
  (min, avg, max) = (13.224, 13.252, 13.290), stdev = 0.034
  CI (99.9%): [12.631, 13.874] (assumes normal distribution)


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
# Warmup Iteration   1: 7.815 ops/ms
# Warmup Iteration   2: 12.609 ops/ms
# Warmup Iteration   3: 12.762 ops/ms
Iteration   1: 12.860 ops/ms
Iteration   2: 13.020 ops/ms
Iteration   3: 12.824 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.901 ±(99.9%) 1.896 ops/ms [Average]
  (min, avg, max) = (12.824, 12.901, 13.020), stdev = 0.104
  CI (99.9%): [11.005, 14.798] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:42
# Fork: 1 of 1
# Warmup Iteration   1: 6.649 ops/ms
# Warmup Iteration   2: 10.601 ops/ms
# Warmup Iteration   3: 10.764 ops/ms
Iteration   1: 10.683 ops/ms
Iteration   2: 10.582 ops/ms
Iteration   3: 10.553 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.606 ±(99.9%) 1.240 ops/ms [Average]
  (min, avg, max) = (10.553, 10.606, 10.683), stdev = 0.068
  CI (99.9%): [9.366, 11.846] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:37
# Fork: 1 of 1
# Warmup Iteration   1: 4.057 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.548 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.513 ±(99.9%) 0.004 ms/op
Iteration   1: 2.546 ±(99.9%) 0.004 ms/op
Iteration   2: 2.504 ±(99.9%) 0.004 ms/op
Iteration   3: 2.525 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.525 ±(99.9%) 0.382 ms/op [Average]
  (min, avg, max) = (2.504, 2.525, 2.546), stdev = 0.021
  CI (99.9%): [2.142, 2.907] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:32
# Fork: 1 of 1
# Warmup Iteration   1: 3.801 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.512 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.472 ±(99.9%) 0.004 ms/op
Iteration   1: 2.487 ±(99.9%) 0.004 ms/op
Iteration   2: 2.488 ±(99.9%) 0.005 ms/op
Iteration   3: 2.485 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.487 ±(99.9%) 0.033 ms/op [Average]
  (min, avg, max) = (2.485, 2.487, 2.488), stdev = 0.002
  CI (99.9%): [2.454, 2.519] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:28
# Fork: 1 of 1
# Warmup Iteration   1: 3.758 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.573 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.486 ±(99.9%) 0.005 ms/op
Iteration   1: 2.462 ±(99.9%) 0.004 ms/op
Iteration   2: 2.479 ±(99.9%) 0.005 ms/op
Iteration   3: 2.463 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.468 ±(99.9%) 0.174 ms/op [Average]
  (min, avg, max) = (2.462, 2.468, 2.479), stdev = 0.010
  CI (99.9%): [2.293, 2.642] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:23
# Fork: 1 of 1
# Warmup Iteration   1: 4.621 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.014 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.003 ±(99.9%) 0.004 ms/op
Iteration   1: 2.965 ±(99.9%) 0.004 ms/op
Iteration   2: 2.997 ±(99.9%) 0.005 ms/op
Iteration   3: 2.957 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.973 ±(99.9%) 0.387 ms/op [Average]
  (min, avg, max) = (2.957, 2.973, 2.997), stdev = 0.021
  CI (99.9%): [2.586, 3.360] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:18
# Fork: 1 of 1
# Warmup Iteration   1: 4.184 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 2.680 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.561 ±(99.9%) 0.006 ms/op
Iteration   1: 2.530 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.065 ms/op
                 createUser·p0.50:   2.593 ms/op
                 createUser·p0.90:   3.064 ms/op
                 createUser·p0.95:   3.170 ms/op
                 createUser·p0.99:   3.699 ms/op
                 createUser·p0.999:  11.251 ms/op
                 createUser·p0.9999: 14.026 ms/op
                 createUser·p1.00:   15.188 ms/op

Iteration   2: 2.543 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.977 ms/op
                 createUser·p0.50:   2.630 ms/op
                 createUser·p0.90:   3.088 ms/op
                 createUser·p0.95:   3.191 ms/op
                 createUser·p0.99:   3.670 ms/op
                 createUser·p0.999:  9.463 ms/op
                 createUser·p0.9999: 12.091 ms/op
                 createUser·p1.00:   12.550 ms/op

Iteration   3: 2.540 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.051 ms/op
                 createUser·p0.50:   2.601 ms/op
                 createUser·p0.90:   3.076 ms/op
                 createUser·p0.95:   3.191 ms/op
                 createUser·p0.99:   3.842 ms/op
                 createUser·p0.999:  8.929 ms/op
                 createUser·p0.9999: 11.502 ms/op
                 createUser·p1.00:   13.631 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 377945
  mean =      2.538 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 26 
    [ 1.250,  2.500) = 181786 
    [ 2.500,  3.750) = 192423 
    [ 3.750,  5.000) = 2822 
    [ 5.000,  6.250) = 311 
    [ 6.250,  7.500) = 100 
    [ 7.500,  8.750) = 76 
    [ 8.750, 10.000) = 122 
    [10.000, 11.250) = 87 
    [11.250, 12.500) = 129 
    [12.500, 13.750) = 47 
    [13.750, 15.000) = 15 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.977 ms/op
     p(50.0000) =      2.609 ms/op
     p(90.0000) =      3.076 ms/op
     p(95.0000) =      3.183 ms/op
     p(99.0000) =      3.738 ms/op
     p(99.9000) =      8.929 ms/op
     p(99.9900) =     13.157 ms/op
     p(99.9990) =     14.241 ms/op
     p(99.9999) =     15.188 ms/op
    p(100.0000) =     15.188 ms/op


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
# Warmup Iteration   1: 3.794 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 2.430 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.412 ±(99.9%) 0.005 ms/op
Iteration   1: 2.433 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.861 ms/op
                 existUser·p0.50:   2.494 ms/op
                 existUser·p0.90:   2.957 ms/op
                 existUser·p0.95:   3.060 ms/op
                 existUser·p0.99:   3.483 ms/op
                 existUser·p0.999:  5.922 ms/op
                 existUser·p0.9999: 13.812 ms/op
                 existUser·p1.00:   14.189 ms/op

Iteration   2: 2.431 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.981 ms/op
                 existUser·p0.50:   2.527 ms/op
                 existUser·p0.90:   2.949 ms/op
                 existUser·p0.95:   3.043 ms/op
                 existUser·p0.99:   3.474 ms/op
                 existUser·p0.999:  9.004 ms/op
                 existUser·p0.9999: 13.351 ms/op
                 existUser·p1.00:   13.844 ms/op

Iteration   3: 2.465 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.945 ms/op
                 existUser·p0.50:   2.519 ms/op
                 existUser·p0.90:   3.006 ms/op
                 existUser·p0.95:   3.121 ms/op
                 existUser·p0.99:   3.686 ms/op
                 existUser·p0.999:  6.930 ms/op
                 existUser·p0.9999: 11.796 ms/op
                 existUser·p1.00:   12.485 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 392512
  mean =      2.443 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 45 
    [ 1.250,  2.500) = 194991 
    [ 2.500,  3.750) = 194644 
    [ 3.750,  5.000) = 2149 
    [ 5.000,  6.250) = 257 
    [ 6.250,  7.500) = 56 
    [ 7.500,  8.750) = 22 
    [ 8.750, 10.000) = 68 
    [10.000, 11.250) = 95 
    [11.250, 12.500) = 56 
    [12.500, 13.750) = 112 
    [13.750, 15.000) = 17 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.861 ms/op
     p(50.0000) =      2.515 ms/op
     p(90.0000) =      2.970 ms/op
     p(95.0000) =      3.076 ms/op
     p(99.0000) =      3.551 ms/op
     p(99.9000) =      6.963 ms/op
     p(99.9900) =     13.406 ms/op
     p(99.9990) =     14.075 ms/op
     p(99.9999) =     14.189 ms/op
    p(100.0000) =     14.189 ms/op


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
# Warmup Iteration   1: 3.954 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 2.615 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.528 ±(99.9%) 0.006 ms/op
Iteration   1: 2.508 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.822 ms/op
                 getUser·p0.50:   2.519 ms/op
                 getUser·p0.90:   3.043 ms/op
                 getUser·p0.95:   3.183 ms/op
                 getUser·p0.99:   4.121 ms/op
                 getUser·p0.999:  11.797 ms/op
                 getUser·p0.9999: 14.225 ms/op
                 getUser·p1.00:   14.582 ms/op

Iteration   2: 2.542 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.957 ms/op
                 getUser·p0.50:   2.564 ms/op
                 getUser·p0.90:   3.092 ms/op
                 getUser·p0.95:   3.232 ms/op
                 getUser·p0.99:   4.150 ms/op
                 getUser·p0.999:  10.096 ms/op
                 getUser·p0.9999: 13.691 ms/op
                 getUser·p1.00:   14.402 ms/op

Iteration   3: 2.495 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.642 ms/op
                 getUser·p0.50:   2.507 ms/op
                 getUser·p0.90:   3.043 ms/op
                 getUser·p0.95:   3.150 ms/op
                 getUser·p0.99:   3.658 ms/op
                 getUser·p0.999:  8.492 ms/op
                 getUser·p0.9999: 11.849 ms/op
                 getUser·p1.00:   12.468 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 381410
  mean =      2.515 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 44 
    [ 1.250,  2.500) = 188487 
    [ 2.500,  3.750) = 187702 
    [ 3.750,  5.000) = 3587 
    [ 5.000,  6.250) = 1053 
    [ 6.250,  7.500) = 150 
    [ 7.500,  8.750) = 10 
    [ 8.750, 10.000) = 48 
    [10.000, 11.250) = 92 
    [11.250, 12.500) = 97 
    [12.500, 13.750) = 110 
    [13.750, 15.000) = 30 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.642 ms/op
     p(50.0000) =      2.531 ms/op
     p(90.0000) =      3.060 ms/op
     p(95.0000) =      3.187 ms/op
     p(99.0000) =      3.957 ms/op
     p(99.9000) =      8.693 ms/op
     p(99.9900) =     13.582 ms/op
     p(99.9990) =     14.421 ms/op
     p(99.9999) =     14.582 ms/op
    p(100.0000) =     14.582 ms/op


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
# Warmup Iteration   1: 4.694 ±(99.9%) 0.061 ms/op
# Warmup Iteration   2: 3.047 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.020 ±(99.9%) 0.009 ms/op
Iteration   1: 2.990 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.938 ms/op
                 listUser·p0.50:   2.941 ms/op
                 listUser·p0.90:   3.834 ms/op
                 listUser·p0.95:   4.301 ms/op
                 listUser·p0.99:   5.439 ms/op
                 listUser·p0.999:  9.407 ms/op
                 listUser·p0.9999: 13.603 ms/op
                 listUser·p1.00:   14.189 ms/op

Iteration   2: 2.992 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.703 ms/op
                 listUser·p0.50:   2.937 ms/op
                 listUser·p0.90:   3.822 ms/op
                 listUser·p0.95:   4.276 ms/op
                 listUser·p0.99:   5.382 ms/op
                 listUser·p0.999:  9.683 ms/op
                 listUser·p0.9999: 11.053 ms/op
                 listUser·p1.00:   12.059 ms/op

Iteration   3: 2.988 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.793 ms/op
                 listUser·p0.50:   2.933 ms/op
                 listUser·p0.90:   3.830 ms/op
                 listUser·p0.95:   4.325 ms/op
                 listUser·p0.99:   5.431 ms/op
                 listUser·p0.999:  9.879 ms/op
                 listUser·p0.9999: 12.350 ms/op
                 listUser·p1.00:   13.533 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 320808
  mean =      2.990 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 114 
    [ 1.250,  2.500) = 94618 
    [ 2.500,  3.750) = 189800 
    [ 3.750,  5.000) = 30222 
    [ 5.000,  6.250) = 4933 
    [ 6.250,  7.500) = 447 
    [ 7.500,  8.750) = 141 
    [ 8.750, 10.000) = 271 
    [10.000, 11.250) = 181 
    [11.250, 12.500) = 46 
    [12.500, 13.750) = 31 
    [13.750, 15.000) = 4 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.703 ms/op
     p(50.0000) =      2.937 ms/op
     p(90.0000) =      3.826 ms/op
     p(95.0000) =      4.301 ms/op
     p(99.0000) =      5.415 ms/op
     p(99.9000) =      9.699 ms/op
     p(99.9900) =     12.926 ms/op
     p(99.9990) =     14.051 ms/op
     p(99.9999) =     14.189 ms/op
    p(100.0000) =     14.189 ms/op


# Run complete. Total time: 00:12:58

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.593 ± 2.247  ops/ms
ClientPb.existUser                       thrpt       3  13.252 ± 0.621  ops/ms
ClientPb.getUser                         thrpt       3  12.901 ± 1.896  ops/ms
ClientPb.listUser                        thrpt       3  10.606 ± 1.240  ops/ms
ClientPb.createUser                       avgt       3   2.525 ± 0.382   ms/op
ClientPb.existUser                        avgt       3   2.487 ± 0.033   ms/op
ClientPb.getUser                          avgt       3   2.468 ± 0.174   ms/op
ClientPb.listUser                         avgt       3   2.973 ± 0.387   ms/op
ClientPb.createUser                     sample  377945   2.538 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.977           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.609           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.076           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.183           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.738           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.929           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.157           ms/op
ClientPb.createUser:createUser·p1.00    sample          15.188           ms/op
ClientPb.existUser                      sample  392512   2.443 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.861           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.515           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.970           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.076           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.551           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.963           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.406           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.189           ms/op
ClientPb.getUser                        sample  381410   2.515 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.642           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.531           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.060           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.187           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.957           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.693           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.582           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.582           ms/op
ClientPb.listUser                       sample  320808   2.990 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.703           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.937           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.826           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.301           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.415           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.699           ms/op
ClientPb.listUser:listUser·p0.9999      sample          12.926           ms/op
ClientPb.listUser:listUser·p1.00        sample          14.189           ms/op
