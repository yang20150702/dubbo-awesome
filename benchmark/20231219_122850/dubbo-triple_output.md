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
# Warmup Iteration   1: 4.418 ops/ms
# Warmup Iteration   2: 11.993 ops/ms
# Warmup Iteration   3: 12.463 ops/ms
Iteration   1: 12.717 ops/ms
Iteration   2: 12.728 ops/ms
Iteration   3: 12.670 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.705 ±(99.9%) 0.565 ops/ms [Average]
  (min, avg, max) = (12.670, 12.705, 12.728), stdev = 0.031
  CI (99.9%): [12.140, 13.270] (assumes normal distribution)


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
# Warmup Iteration   1: 8.462 ops/ms
# Warmup Iteration   2: 13.037 ops/ms
# Warmup Iteration   3: 13.077 ops/ms
Iteration   1: 13.214 ops/ms
Iteration   2: 13.236 ops/ms
Iteration   3: 13.250 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.233 ±(99.9%) 0.332 ops/ms [Average]
  (min, avg, max) = (13.214, 13.233, 13.250), stdev = 0.018
  CI (99.9%): [12.901, 13.565] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 7.741 ops/ms
# Warmup Iteration   2: 12.528 ops/ms
# Warmup Iteration   3: 13.066 ops/ms
Iteration   1: 13.158 ops/ms
Iteration   2: 13.135 ops/ms
Iteration   3: 13.019 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  13.104 ±(99.9%) 1.356 ops/ms [Average]
  (min, avg, max) = (13.019, 13.104, 13.158), stdev = 0.074
  CI (99.9%): [11.748, 14.461] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:45
# Fork: 1 of 1
# Warmup Iteration   1: 6.785 ops/ms
# Warmup Iteration   2: 10.752 ops/ms
# Warmup Iteration   3: 10.807 ops/ms
Iteration   1: 10.880 ops/ms
Iteration   2: 10.756 ops/ms
Iteration   3: 10.878 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.838 ±(99.9%) 1.298 ops/ms [Average]
  (min, avg, max) = (10.756, 10.838, 10.880), stdev = 0.071
  CI (99.9%): [9.540, 12.136] (assumes normal distribution)


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
# Warmup Iteration   1: 3.950 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 2.569 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.506 ±(99.9%) 0.003 ms/op
Iteration   1: 2.531 ±(99.9%) 0.004 ms/op
Iteration   2: 2.477 ±(99.9%) 0.003 ms/op
Iteration   3: 2.511 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.506 ±(99.9%) 0.497 ms/op [Average]
  (min, avg, max) = (2.477, 2.506, 2.531), stdev = 0.027
  CI (99.9%): [2.009, 3.003] (assumes normal distribution)


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
# Warmup Iteration   1: 3.536 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.421 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.421 ±(99.9%) 0.004 ms/op
Iteration   1: 2.425 ±(99.9%) 0.003 ms/op
Iteration   2: 2.397 ±(99.9%) 0.003 ms/op
Iteration   3: 2.430 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.418 ±(99.9%) 0.324 ms/op [Average]
  (min, avg, max) = (2.397, 2.418, 2.430), stdev = 0.018
  CI (99.9%): [2.094, 2.741] (assumes normal distribution)


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
# Warmup Iteration   1: 4.049 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.564 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.488 ±(99.9%) 0.004 ms/op
Iteration   1: 2.456 ±(99.9%) 0.004 ms/op
Iteration   2: 2.457 ±(99.9%) 0.003 ms/op
Iteration   3: 2.471 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.461 ±(99.9%) 0.156 ms/op [Average]
  (min, avg, max) = (2.456, 2.461, 2.471), stdev = 0.009
  CI (99.9%): [2.305, 2.617] (assumes normal distribution)


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
# Warmup Iteration   1: 4.571 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 2.981 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.960 ±(99.9%) 0.006 ms/op
Iteration   1: 2.950 ±(99.9%) 0.006 ms/op
Iteration   2: 2.961 ±(99.9%) 0.006 ms/op
Iteration   3: 2.940 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.950 ±(99.9%) 0.186 ms/op [Average]
  (min, avg, max) = (2.940, 2.950, 2.961), stdev = 0.010
  CI (99.9%): [2.764, 3.137] (assumes normal distribution)


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
# Warmup Iteration   1: 3.947 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 2.594 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.493 ±(99.9%) 0.005 ms/op
Iteration   1: 2.477 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.953 ms/op
                 createUser·p0.50:   2.593 ms/op
                 createUser·p0.90:   2.994 ms/op
                 createUser·p0.95:   3.088 ms/op
                 createUser·p0.99:   3.492 ms/op
                 createUser·p0.999:  7.006 ms/op
                 createUser·p0.9999: 14.762 ms/op
                 createUser·p1.00:   15.401 ms/op

Iteration   2: 2.490 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.980 ms/op
                 createUser·p0.50:   2.580 ms/op
                 createUser·p0.90:   3.011 ms/op
                 createUser·p0.95:   3.121 ms/op
                 createUser·p0.99:   3.703 ms/op
                 createUser·p0.999:  7.994 ms/op
                 createUser·p0.9999: 11.878 ms/op
                 createUser·p1.00:   12.648 ms/op

Iteration   3: 2.489 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.020 ms/op
                 createUser·p0.50:   2.560 ms/op
                 createUser·p0.90:   3.023 ms/op
                 createUser·p0.95:   3.133 ms/op
                 createUser·p0.99:   3.674 ms/op
                 createUser·p0.999:  8.954 ms/op
                 createUser·p0.9999: 10.646 ms/op
                 createUser·p1.00:   11.272 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 385870
  mean =      2.485 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 40 
    [ 1.250,  2.500) = 186661 
    [ 2.500,  3.750) = 196136 
    [ 3.750,  5.000) = 2354 
    [ 5.000,  6.250) = 206 
    [ 6.250,  7.500) = 67 
    [ 7.500,  8.750) = 11 
    [ 8.750, 10.000) = 121 
    [10.000, 11.250) = 102 
    [11.250, 12.500) = 83 
    [12.500, 13.750) = 63 
    [13.750, 15.000) = 23 
    [15.000, 16.250) = 3 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.953 ms/op
     p(50.0000) =      2.576 ms/op
     p(90.0000) =      3.011 ms/op
     p(95.0000) =      3.113 ms/op
     p(99.0000) =      3.629 ms/op
     p(99.9000) =      8.946 ms/op
     p(99.9900) =     13.189 ms/op
     p(99.9990) =     14.984 ms/op
     p(99.9999) =     15.401 ms/op
    p(100.0000) =     15.401 ms/op


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
# Warmup Iteration   1: 3.690 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 2.440 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.440 ±(99.9%) 0.005 ms/op
Iteration   1: 2.454 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.674 ms/op
                 existUser·p0.50:   2.519 ms/op
                 existUser·p0.90:   2.978 ms/op
                 existUser·p0.95:   3.092 ms/op
                 existUser·p0.99:   3.572 ms/op
                 existUser·p0.999:  6.968 ms/op
                 existUser·p0.9999: 13.860 ms/op
                 existUser·p1.00:   14.975 ms/op

Iteration   2: 2.428 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.993 ms/op
                 existUser·p0.50:   2.507 ms/op
                 existUser·p0.90:   2.945 ms/op
                 existUser·p0.95:   3.047 ms/op
                 existUser·p0.99:   3.535 ms/op
                 existUser·p0.999:  7.410 ms/op
                 existUser·p0.9999: 13.924 ms/op
                 existUser·p1.00:   15.106 ms/op

Iteration   3: 2.417 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.923 ms/op
                 existUser·p0.50:   2.429 ms/op
                 existUser·p0.90:   2.949 ms/op
                 existUser·p0.95:   3.072 ms/op
                 existUser·p0.99:   3.629 ms/op
                 existUser·p0.999:  7.975 ms/op
                 existUser·p0.9999: 12.534 ms/op
                 existUser·p1.00:   13.222 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 394183
  mean =      2.433 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 82 
    [ 1.250,  2.500) = 199241 
    [ 2.500,  3.750) = 191898 
    [ 3.750,  5.000) = 2256 
    [ 5.000,  6.250) = 236 
    [ 6.250,  7.500) = 51 
    [ 7.500,  8.750) = 35 
    [ 8.750, 10.000) = 93 
    [10.000, 11.250) = 79 
    [11.250, 12.500) = 63 
    [12.500, 13.750) = 106 
    [13.750, 15.000) = 41 
    [15.000, 16.250) = 2 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.674 ms/op
     p(50.0000) =      2.478 ms/op
     p(90.0000) =      2.957 ms/op
     p(95.0000) =      3.072 ms/op
     p(99.0000) =      3.580 ms/op
     p(99.9000) =      7.954 ms/op
     p(99.9900) =     13.788 ms/op
     p(99.9990) =     14.759 ms/op
     p(99.9999) =     15.106 ms/op
    p(100.0000) =     15.106 ms/op


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
# Warmup Iteration   1: 3.855 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 2.560 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.477 ±(99.9%) 0.005 ms/op
Iteration   1: 2.489 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.402 ms/op
                 getUser·p0.50:   2.503 ms/op
                 getUser·p0.90:   3.043 ms/op
                 getUser·p0.95:   3.191 ms/op
                 getUser·p0.99:   3.842 ms/op
                 getUser·p0.999:  10.132 ms/op
                 getUser·p0.9999: 14.158 ms/op
                 getUser·p1.00:   14.664 ms/op

Iteration   2: 2.505 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.945 ms/op
                 getUser·p0.50:   2.523 ms/op
                 getUser·p0.90:   3.043 ms/op
                 getUser·p0.95:   3.183 ms/op
                 getUser·p0.99:   4.399 ms/op
                 getUser·p0.999:  10.093 ms/op
                 getUser·p0.9999: 12.947 ms/op
                 getUser·p1.00:   13.500 ms/op

Iteration   3: 2.486 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.915 ms/op
                 getUser·p0.50:   2.503 ms/op
                 getUser·p0.90:   3.035 ms/op
                 getUser·p0.95:   3.158 ms/op
                 getUser·p0.99:   3.686 ms/op
                 getUser·p0.999:  7.436 ms/op
                 getUser·p0.9999: 11.567 ms/op
                 getUser·p1.00:   12.337 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 384699
  mean =      2.493 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 96 
    [ 1.250,  2.500) = 191586 
    [ 2.500,  3.750) = 188165 
    [ 3.750,  5.000) = 3984 
    [ 5.000,  6.250) = 468 
    [ 6.250,  7.500) = 15 
    [ 7.500,  8.750) = 2 
    [ 8.750, 10.000) = 27 
    [10.000, 11.250) = 123 
    [11.250, 12.500) = 142 
    [12.500, 13.750) = 69 
    [13.750, 15.000) = 22 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.402 ms/op
     p(50.0000) =      2.507 ms/op
     p(90.0000) =      3.039 ms/op
     p(95.0000) =      3.174 ms/op
     p(99.0000) =      3.908 ms/op
     p(99.9000) =      8.480 ms/op
     p(99.9900) =     13.435 ms/op
     p(99.9990) =     14.396 ms/op
     p(99.9999) =     14.664 ms/op
    p(100.0000) =     14.664 ms/op


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
# Warmup Iteration   1: 4.866 ±(99.9%) 0.055 ms/op
# Warmup Iteration   2: 3.059 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.041 ±(99.9%) 0.008 ms/op
Iteration   1: 3.024 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.948 ms/op
                 listUser·p0.50:   2.966 ms/op
                 listUser·p0.90:   3.887 ms/op
                 listUser·p0.95:   4.399 ms/op
                 listUser·p0.99:   5.683 ms/op
                 listUser·p0.999:  9.060 ms/op
                 listUser·p0.9999: 11.272 ms/op
                 listUser·p1.00:   12.681 ms/op

Iteration   2: 3.014 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   0.998 ms/op
                 listUser·p0.50:   2.949 ms/op
                 listUser·p0.90:   3.899 ms/op
                 listUser·p0.95:   4.391 ms/op
                 listUser·p0.99:   5.587 ms/op
                 listUser·p0.999:  11.298 ms/op
                 listUser·p0.9999: 14.729 ms/op
                 listUser·p1.00:   15.614 ms/op

Iteration   3: 2.979 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.942 ms/op
                 listUser·p0.50:   2.925 ms/op
                 listUser·p0.90:   3.822 ms/op
                 listUser·p0.95:   4.334 ms/op
                 listUser·p0.99:   5.536 ms/op
                 listUser·p0.999:  9.350 ms/op
                 listUser·p0.9999: 12.337 ms/op
                 listUser·p1.00:   12.911 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 319095
  mean =      3.006 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 144 
    [ 1.250,  2.500) = 94502 
    [ 2.500,  3.750) = 186201 
    [ 3.750,  5.000) = 31028 
    [ 5.000,  6.250) = 5756 
    [ 6.250,  7.500) = 755 
    [ 7.500,  8.750) = 185 
    [ 8.750, 10.000) = 203 
    [10.000, 11.250) = 173 
    [11.250, 12.500) = 67 
    [12.500, 13.750) = 41 
    [13.750, 15.000) = 34 
    [15.000, 16.250) = 6 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.942 ms/op
     p(50.0000) =      2.945 ms/op
     p(90.0000) =      3.871 ms/op
     p(95.0000) =      4.375 ms/op
     p(99.0000) =      5.595 ms/op
     p(99.9000) =     10.011 ms/op
     p(99.9900) =     13.877 ms/op
     p(99.9990) =     15.198 ms/op
     p(99.9999) =     15.614 ms/op
    p(100.0000) =     15.614 ms/op


# Run complete. Total time: 00:12:58

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.705 ± 0.565  ops/ms
ClientPb.existUser                       thrpt       3  13.233 ± 0.332  ops/ms
ClientPb.getUser                         thrpt       3  13.104 ± 1.356  ops/ms
ClientPb.listUser                        thrpt       3  10.838 ± 1.298  ops/ms
ClientPb.createUser                       avgt       3   2.506 ± 0.497   ms/op
ClientPb.existUser                        avgt       3   2.418 ± 0.324   ms/op
ClientPb.getUser                          avgt       3   2.461 ± 0.156   ms/op
ClientPb.listUser                         avgt       3   2.950 ± 0.186   ms/op
ClientPb.createUser                     sample  385870   2.485 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.953           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.576           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.011           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.113           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.629           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.946           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.189           ms/op
ClientPb.createUser:createUser·p1.00    sample          15.401           ms/op
ClientPb.existUser                      sample  394183   2.433 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.674           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.478           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.957           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.072           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.580           ms/op
ClientPb.existUser:existUser·p0.999     sample           7.954           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.788           ms/op
ClientPb.existUser:existUser·p1.00      sample          15.106           ms/op
ClientPb.getUser                        sample  384699   2.493 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.402           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.507           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.039           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.174           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.908           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.480           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.435           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.664           ms/op
ClientPb.listUser                       sample  319095   3.006 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.942           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.945           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.871           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.375           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.595           ms/op
ClientPb.listUser:listUser·p0.999       sample          10.011           ms/op
ClientPb.listUser:listUser·p0.9999      sample          13.877           ms/op
ClientPb.listUser:listUser·p1.00        sample          15.614           ms/op
