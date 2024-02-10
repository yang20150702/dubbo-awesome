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
# Warmup Iteration   1: 4.946 ops/ms
# Warmup Iteration   2: 12.457 ops/ms
# Warmup Iteration   3: 12.529 ops/ms
Iteration   1: 12.822 ops/ms
Iteration   2: 12.785 ops/ms
Iteration   3: 12.872 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.826 ±(99.9%) 0.793 ops/ms [Average]
  (min, avg, max) = (12.785, 12.826, 12.872), stdev = 0.043
  CI (99.9%): [12.033, 13.619] (assumes normal distribution)


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
# Warmup Iteration   1: 8.351 ops/ms
# Warmup Iteration   2: 13.057 ops/ms
# Warmup Iteration   3: 13.154 ops/ms
Iteration   1: 13.104 ops/ms
Iteration   2: 13.213 ops/ms
Iteration   3: 13.172 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.163 ±(99.9%) 1.009 ops/ms [Average]
  (min, avg, max) = (13.104, 13.163, 13.213), stdev = 0.055
  CI (99.9%): [12.154, 14.172] (assumes normal distribution)


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
# Warmup Iteration   1: 8.258 ops/ms
# Warmup Iteration   2: 12.563 ops/ms
# Warmup Iteration   3: 12.837 ops/ms
Iteration   1: 12.944 ops/ms
Iteration   2: 13.046 ops/ms
Iteration   3: 12.928 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.973 ±(99.9%) 1.165 ops/ms [Average]
  (min, avg, max) = (12.928, 12.973, 13.046), stdev = 0.064
  CI (99.9%): [11.808, 14.138] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:44
# Fork: 1 of 1
# Warmup Iteration   1: 6.736 ops/ms
# Warmup Iteration   2: 10.512 ops/ms
# Warmup Iteration   3: 10.755 ops/ms
Iteration   1: 10.699 ops/ms
Iteration   2: 10.846 ops/ms
Iteration   3: 10.880 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.808 ±(99.9%) 1.754 ops/ms [Average]
  (min, avg, max) = (10.699, 10.808, 10.880), stdev = 0.096
  CI (99.9%): [9.055, 12.562] (assumes normal distribution)


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
# Warmup Iteration   1: 3.757 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.541 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.483 ±(99.9%) 0.004 ms/op
Iteration   1: 2.482 ±(99.9%) 0.004 ms/op
Iteration   2: 2.475 ±(99.9%) 0.004 ms/op
Iteration   3: 2.485 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.481 ±(99.9%) 0.099 ms/op [Average]
  (min, avg, max) = (2.475, 2.481, 2.485), stdev = 0.005
  CI (99.9%): [2.382, 2.580] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:33
# Fork: 1 of 1
# Warmup Iteration   1: 3.552 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.374 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.360 ±(99.9%) 0.005 ms/op
Iteration   1: 2.421 ±(99.9%) 0.004 ms/op
Iteration   2: 2.424 ±(99.9%) 0.003 ms/op
Iteration   3: 2.407 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.417 ±(99.9%) 0.168 ms/op [Average]
  (min, avg, max) = (2.407, 2.417, 2.424), stdev = 0.009
  CI (99.9%): [2.249, 2.585] (assumes normal distribution)


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
# Warmup Iteration   1: 3.659 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.519 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.461 ±(99.9%) 0.004 ms/op
Iteration   1: 2.462 ±(99.9%) 0.003 ms/op
Iteration   2: 2.448 ±(99.9%) 0.003 ms/op
Iteration   3: 2.496 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.469 ±(99.9%) 0.454 ms/op [Average]
  (min, avg, max) = (2.448, 2.469, 2.496), stdev = 0.025
  CI (99.9%): [2.015, 2.923] (assumes normal distribution)


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
# Warmup Iteration   1: 4.540 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 2.959 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.907 ±(99.9%) 0.006 ms/op
Iteration   1: 2.940 ±(99.9%) 0.006 ms/op
Iteration   2: 2.907 ±(99.9%) 0.005 ms/op
Iteration   3: 2.920 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.922 ±(99.9%) 0.300 ms/op [Average]
  (min, avg, max) = (2.907, 2.922, 2.940), stdev = 0.016
  CI (99.9%): [2.623, 3.222] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 3.980 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 2.645 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.489 ±(99.9%) 0.006 ms/op
Iteration   1: 2.466 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.714 ms/op
                 createUser·p0.50:   2.478 ms/op
                 createUser·p0.90:   2.994 ms/op
                 createUser·p0.95:   3.113 ms/op
                 createUser·p0.99:   3.748 ms/op
                 createUser·p0.999:  8.197 ms/op
                 createUser·p0.9999: 14.108 ms/op
                 createUser·p1.00:   15.565 ms/op

Iteration   2: 2.493 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.025 ms/op
                 createUser·p0.50:   2.515 ms/op
                 createUser·p0.90:   3.039 ms/op
                 createUser·p0.95:   3.174 ms/op
                 createUser·p0.99:   3.830 ms/op
                 createUser·p0.999:  9.233 ms/op
                 createUser·p0.9999: 12.337 ms/op
                 createUser·p1.00:   12.534 ms/op

Iteration   3: 2.471 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.904 ms/op
                 createUser·p0.50:   2.535 ms/op
                 createUser·p0.90:   3.002 ms/op
                 createUser·p0.95:   3.113 ms/op
                 createUser·p0.99:   3.737 ms/op
                 createUser·p0.999:  8.596 ms/op
                 createUser·p0.9999: 10.734 ms/op
                 createUser·p1.00:   10.945 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 387399
  mean =      2.477 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 58 
    [ 1.250,  2.500) = 193178 
    [ 2.500,  3.750) = 190123 
    [ 3.750,  5.000) = 3203 
    [ 5.000,  6.250) = 387 
    [ 6.250,  7.500) = 59 
    [ 7.500,  8.750) = 21 
    [ 8.750, 10.000) = 75 
    [10.000, 11.250) = 95 
    [11.250, 12.500) = 127 
    [12.500, 13.750) = 53 
    [13.750, 15.000) = 15 
    [15.000, 16.250) = 5 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.714 ms/op
     p(50.0000) =      2.507 ms/op
     p(90.0000) =      3.011 ms/op
     p(95.0000) =      3.133 ms/op
     p(99.0000) =      3.777 ms/op
     p(99.9000) =      8.207 ms/op
     p(99.9900) =     13.030 ms/op
     p(99.9990) =     15.364 ms/op
     p(99.9999) =     15.565 ms/op
    p(100.0000) =     15.565 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 3.680 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 2.492 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.462 ±(99.9%) 0.005 ms/op
Iteration   1: 2.472 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.842 ms/op
                 existUser·p0.50:   2.593 ms/op
                 existUser·p0.90:   2.990 ms/op
                 existUser·p0.95:   3.076 ms/op
                 existUser·p0.99:   3.383 ms/op
                 existUser·p0.999:  5.093 ms/op
                 existUser·p0.9999: 14.075 ms/op
                 existUser·p1.00:   14.270 ms/op

Iteration   2: 2.458 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.936 ms/op
                 existUser·p0.50:   2.572 ms/op
                 existUser·p0.90:   2.966 ms/op
                 existUser·p0.95:   3.060 ms/op
                 existUser·p0.99:   3.572 ms/op
                 existUser·p0.999:  7.479 ms/op
                 existUser·p0.9999: 13.074 ms/op
                 existUser·p1.00:   13.550 ms/op

Iteration   3: 2.493 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.975 ms/op
                 existUser·p0.50:   2.548 ms/op
                 existUser·p0.90:   3.043 ms/op
                 existUser·p0.95:   3.174 ms/op
                 existUser·p0.99:   3.895 ms/op
                 existUser·p0.999:  7.928 ms/op
                 existUser·p0.9999: 11.930 ms/op
                 existUser·p1.00:   12.157 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 387607
  mean =      2.474 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 48 
    [ 1.250,  2.500) = 188585 
    [ 2.500,  3.750) = 195739 
    [ 3.750,  5.000) = 2587 
    [ 5.000,  6.250) = 272 
    [ 6.250,  7.500) = 19 
    [ 7.500,  8.750) = 36 
    [ 8.750, 10.000) = 79 
    [10.000, 11.250) = 60 
    [11.250, 12.500) = 86 
    [12.500, 13.750) = 76 
    [13.750, 15.000) = 20 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.842 ms/op
     p(50.0000) =      2.568 ms/op
     p(90.0000) =      2.998 ms/op
     p(95.0000) =      3.105 ms/op
     p(99.0000) =      3.650 ms/op
     p(99.9000) =      5.918 ms/op
     p(99.9900) =     13.156 ms/op
     p(99.9990) =     14.195 ms/op
     p(99.9999) =     14.270 ms/op
    p(100.0000) =     14.270 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 4.048 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 2.597 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.528 ±(99.9%) 0.006 ms/op
Iteration   1: 2.494 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.744 ms/op
                 getUser·p0.50:   2.511 ms/op
                 getUser·p0.90:   3.039 ms/op
                 getUser·p0.95:   3.146 ms/op
                 getUser·p0.99:   3.609 ms/op
                 getUser·p0.999:  10.456 ms/op
                 getUser·p0.9999: 13.926 ms/op
                 getUser·p1.00:   14.156 ms/op

Iteration   2: 2.557 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.868 ms/op
                 getUser·p0.50:   2.597 ms/op
                 getUser·p0.90:   3.101 ms/op
                 getUser·p0.95:   3.285 ms/op
                 getUser·p0.99:   4.858 ms/op
                 getUser·p0.999:  7.184 ms/op
                 getUser·p0.9999: 12.673 ms/op
                 getUser·p1.00:   12.894 ms/op

Iteration   3: 2.502 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.862 ms/op
                 getUser·p0.50:   2.535 ms/op
                 getUser·p0.90:   3.052 ms/op
                 getUser·p0.95:   3.178 ms/op
                 getUser·p0.99:   3.805 ms/op
                 getUser·p0.999:  5.726 ms/op
                 getUser·p0.9999: 11.485 ms/op
                 getUser·p1.00:   12.141 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 380986
  mean =      2.517 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 79 
    [ 1.250,  2.500) = 186757 
    [ 2.500,  3.750) = 188492 
    [ 3.750,  5.000) = 4296 
    [ 5.000,  6.250) = 880 
    [ 6.250,  7.500) = 146 
    [ 7.500,  8.750) = 13 
    [ 8.750, 10.000) = 71 
    [10.000, 11.250) = 68 
    [11.250, 12.500) = 73 
    [12.500, 13.750) = 89 
    [13.750, 15.000) = 22 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.744 ms/op
     p(50.0000) =      2.548 ms/op
     p(90.0000) =      3.060 ms/op
     p(95.0000) =      3.195 ms/op
     p(99.0000) =      4.092 ms/op
     p(99.9000) =      6.750 ms/op
     p(99.9900) =     13.281 ms/op
     p(99.9990) =     14.110 ms/op
     p(99.9999) =     14.156 ms/op
    p(100.0000) =     14.156 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 4.830 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 3.059 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.011 ±(99.9%) 0.009 ms/op
Iteration   1: 2.985 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   0.787 ms/op
                 listUser·p0.50:   2.900 ms/op
                 listUser·p0.90:   3.940 ms/op
                 listUser·p0.95:   4.440 ms/op
                 listUser·p0.99:   5.693 ms/op
                 listUser·p0.999:  9.532 ms/op
                 listUser·p0.9999: 12.118 ms/op
                 listUser·p1.00:   18.416 ms/op

Iteration   2: 2.955 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   0.916 ms/op
                 listUser·p0.50:   2.859 ms/op
                 listUser·p0.90:   3.895 ms/op
                 listUser·p0.95:   4.448 ms/op
                 listUser·p0.99:   5.734 ms/op
                 listUser·p0.999:  9.650 ms/op
                 listUser·p0.9999: 13.094 ms/op
                 listUser·p1.00:   18.448 ms/op

Iteration   3: 2.979 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.970 ms/op
                 listUser·p0.50:   2.896 ms/op
                 listUser·p0.90:   3.912 ms/op
                 listUser·p0.95:   4.432 ms/op
                 listUser·p0.99:   5.595 ms/op
                 listUser·p0.999:  9.847 ms/op
                 listUser·p0.9999: 11.609 ms/op
                 listUser·p1.00:   11.878 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 322672
  mean =      2.973 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 308 
    [ 1.250,  2.500) = 106681 
    [ 2.500,  3.750) = 174393 
    [ 3.750,  5.000) = 33338 
    [ 5.000,  6.250) = 6262 
    [ 6.250,  7.500) = 879 
    [ 7.500,  8.750) = 306 
    [ 8.750, 10.000) = 254 
    [10.000, 11.250) = 156 
    [11.250, 12.500) = 61 
    [12.500, 13.750) = 24 
    [13.750, 15.000) = 8 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.787 ms/op
     p(50.0000) =      2.888 ms/op
     p(90.0000) =      3.916 ms/op
     p(95.0000) =      4.440 ms/op
     p(99.0000) =      5.685 ms/op
     p(99.9000) =      9.699 ms/op
     p(99.9900) =     12.726 ms/op
     p(99.9990) =     14.239 ms/op
     p(99.9999) =     18.448 ms/op
    p(100.0000) =     18.448 ms/op


# Run complete. Total time: 00:13:01

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.826 ± 0.793  ops/ms
ClientPb.existUser                       thrpt       3  13.163 ± 1.009  ops/ms
ClientPb.getUser                         thrpt       3  12.973 ± 1.165  ops/ms
ClientPb.listUser                        thrpt       3  10.808 ± 1.754  ops/ms
ClientPb.createUser                       avgt       3   2.481 ± 0.099   ms/op
ClientPb.existUser                        avgt       3   2.417 ± 0.168   ms/op
ClientPb.getUser                          avgt       3   2.469 ± 0.454   ms/op
ClientPb.listUser                         avgt       3   2.922 ± 0.300   ms/op
ClientPb.createUser                     sample  387399   2.477 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.714           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.507           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.011           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.133           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.777           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.207           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.030           ms/op
ClientPb.createUser:createUser·p1.00    sample          15.565           ms/op
ClientPb.existUser                      sample  387607   2.474 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.842           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.568           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.998           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.105           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.650           ms/op
ClientPb.existUser:existUser·p0.999     sample           5.918           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.156           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.270           ms/op
ClientPb.getUser                        sample  380986   2.517 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.744           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.548           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.060           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.195           ms/op
ClientPb.getUser:getUser·p0.99          sample           4.092           ms/op
ClientPb.getUser:getUser·p0.999         sample           6.750           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.281           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.156           ms/op
ClientPb.listUser                       sample  322672   2.973 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.787           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.888           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.916           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.440           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.685           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.699           ms/op
ClientPb.listUser:listUser·p0.9999      sample          12.726           ms/op
ClientPb.listUser:listUser·p1.00        sample          18.448           ms/op
