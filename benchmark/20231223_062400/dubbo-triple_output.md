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
# Warmup Iteration   1: 4.649 ops/ms
# Warmup Iteration   2: 11.659 ops/ms
# Warmup Iteration   3: 12.036 ops/ms
Iteration   1: 12.177 ops/ms
Iteration   2: 12.220 ops/ms
Iteration   3: 12.294 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.230 ±(99.9%) 1.074 ops/ms [Average]
  (min, avg, max) = (12.177, 12.230, 12.294), stdev = 0.059
  CI (99.9%): [11.157, 13.304] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:51
# Fork: 1 of 1
# Warmup Iteration   1: 8.101 ops/ms
# Warmup Iteration   2: 12.702 ops/ms
# Warmup Iteration   3: 12.886 ops/ms
Iteration   1: 12.896 ops/ms
Iteration   2: 12.938 ops/ms
Iteration   3: 12.876 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.903 ±(99.9%) 0.584 ops/ms [Average]
  (min, avg, max) = (12.876, 12.903, 12.938), stdev = 0.032
  CI (99.9%): [12.319, 13.488] (assumes normal distribution)


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
# Warmup Iteration   1: 7.845 ops/ms
# Warmup Iteration   2: 12.731 ops/ms
# Warmup Iteration   3: 12.651 ops/ms
Iteration   1: 12.775 ops/ms
Iteration   2: 12.942 ops/ms
Iteration   3: 12.788 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.835 ±(99.9%) 1.695 ops/ms [Average]
  (min, avg, max) = (12.775, 12.835, 12.942), stdev = 0.093
  CI (99.9%): [11.140, 14.530] (assumes normal distribution)


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
# Warmup Iteration   1: 6.664 ops/ms
# Warmup Iteration   2: 10.486 ops/ms
# Warmup Iteration   3: 10.510 ops/ms
Iteration   1: 10.517 ops/ms
Iteration   2: 10.620 ops/ms
Iteration   3: 10.640 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.592 ±(99.9%) 1.207 ops/ms [Average]
  (min, avg, max) = (10.517, 10.592, 10.640), stdev = 0.066
  CI (99.9%): [9.385, 11.799] (assumes normal distribution)


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
# Warmup Iteration   1: 3.974 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.658 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.562 ±(99.9%) 0.004 ms/op
Iteration   1: 2.575 ±(99.9%) 0.003 ms/op
Iteration   2: 2.575 ±(99.9%) 0.004 ms/op
Iteration   3: 2.607 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.586 ±(99.9%) 0.329 ms/op [Average]
  (min, avg, max) = (2.575, 2.586, 2.607), stdev = 0.018
  CI (99.9%): [2.257, 2.914] (assumes normal distribution)


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
# Warmup Iteration   1: 3.746 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.504 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.466 ±(99.9%) 0.004 ms/op
Iteration   1: 2.492 ±(99.9%) 0.004 ms/op
Iteration   2: 2.478 ±(99.9%) 0.004 ms/op
Iteration   3: 2.494 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.488 ±(99.9%) 0.162 ms/op [Average]
  (min, avg, max) = (2.478, 2.488, 2.494), stdev = 0.009
  CI (99.9%): [2.326, 2.650] (assumes normal distribution)


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
# Warmup Iteration   1: 3.927 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.586 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.524 ±(99.9%) 0.003 ms/op
Iteration   1: 2.528 ±(99.9%) 0.004 ms/op
Iteration   2: 2.513 ±(99.9%) 0.004 ms/op
Iteration   3: 2.567 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.536 ±(99.9%) 0.518 ms/op [Average]
  (min, avg, max) = (2.513, 2.536, 2.567), stdev = 0.028
  CI (99.9%): [2.018, 3.053] (assumes normal distribution)


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
# Warmup Iteration   1: 4.709 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.059 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.997 ±(99.9%) 0.007 ms/op
Iteration   1: 2.988 ±(99.9%) 0.005 ms/op
Iteration   2: 2.972 ±(99.9%) 0.005 ms/op
Iteration   3: 2.980 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.980 ±(99.9%) 0.147 ms/op [Average]
  (min, avg, max) = (2.972, 2.980, 2.988), stdev = 0.008
  CI (99.9%): [2.833, 3.127] (assumes normal distribution)


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
# Warmup Iteration   1: 4.118 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 2.706 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.568 ±(99.9%) 0.006 ms/op
Iteration   1: 2.543 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.031 ms/op
                 createUser·p0.50:   2.634 ms/op
                 createUser·p0.90:   3.084 ms/op
                 createUser·p0.95:   3.187 ms/op
                 createUser·p0.99:   3.625 ms/op
                 createUser·p0.999:  11.633 ms/op
                 createUser·p0.9999: 13.828 ms/op
                 createUser·p1.00:   14.221 ms/op

Iteration   2: 2.588 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.044 ms/op
                 createUser·p0.50:   2.658 ms/op
                 createUser·p0.90:   3.138 ms/op
                 createUser·p0.95:   3.252 ms/op
                 createUser·p0.99:   3.797 ms/op
                 createUser·p0.999:  9.297 ms/op
                 createUser·p0.9999: 12.391 ms/op
                 createUser·p1.00:   12.960 ms/op

Iteration   3: 2.577 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.920 ms/op
                 createUser·p0.50:   2.675 ms/op
                 createUser·p0.90:   3.121 ms/op
                 createUser·p0.95:   3.219 ms/op
                 createUser·p0.99:   3.723 ms/op
                 createUser·p0.999:  8.929 ms/op
                 createUser·p0.9999: 11.413 ms/op
                 createUser·p1.00:   15.991 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 373388
  mean =      2.569 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 33 
    [ 1.250,  2.500) = 176846 
    [ 2.500,  3.750) = 193054 
    [ 3.750,  5.000) = 2712 
    [ 5.000,  6.250) = 290 
    [ 6.250,  7.500) = 25 
    [ 7.500,  8.750) = 21 
    [ 8.750, 10.000) = 130 
    [10.000, 11.250) = 96 
    [11.250, 12.500) = 80 
    [12.500, 13.750) = 85 
    [13.750, 15.000) = 15 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.920 ms/op
     p(50.0000) =      2.654 ms/op
     p(90.0000) =      3.117 ms/op
     p(95.0000) =      3.219 ms/op
     p(99.0000) =      3.711 ms/op
     p(99.9000) =      8.939 ms/op
     p(99.9900) =     13.200 ms/op
     p(99.9990) =     14.193 ms/op
     p(99.9999) =     15.991 ms/op
    p(100.0000) =     15.991 ms/op


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
# Warmup Iteration   1: 3.597 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 2.475 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.457 ±(99.9%) 0.005 ms/op
Iteration   1: 2.421 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.933 ms/op
                 existUser·p0.50:   2.531 ms/op
                 existUser·p0.90:   2.929 ms/op
                 existUser·p0.95:   3.023 ms/op
                 existUser·p0.99:   3.432 ms/op
                 existUser·p0.999:  5.503 ms/op
                 existUser·p0.9999: 13.468 ms/op
                 existUser·p1.00:   14.221 ms/op

Iteration   2: 2.455 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.909 ms/op
                 existUser·p0.50:   2.531 ms/op
                 existUser·p0.90:   2.982 ms/op
                 existUser·p0.95:   3.088 ms/op
                 existUser·p0.99:   3.592 ms/op
                 existUser·p0.999:  6.403 ms/op
                 existUser·p0.9999: 13.173 ms/op
                 existUser·p1.00:   14.025 ms/op

Iteration   3: 2.462 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.907 ms/op
                 existUser·p0.50:   2.499 ms/op
                 existUser·p0.90:   3.006 ms/op
                 existUser·p0.95:   3.121 ms/op
                 existUser·p0.99:   3.707 ms/op
                 existUser·p0.999:  6.949 ms/op
                 existUser·p0.9999: 11.902 ms/op
                 existUser·p1.00:   12.796 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 392080
  mean =      2.446 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 38 
    [ 1.250,  2.500) = 193989 
    [ 2.500,  3.750) = 195145 
    [ 3.750,  5.000) = 2275 
    [ 5.000,  6.250) = 230 
    [ 6.250,  7.500) = 20 
    [ 7.500,  8.750) = 15 
    [ 8.750, 10.000) = 113 
    [10.000, 11.250) = 73 
    [11.250, 12.500) = 115 
    [12.500, 13.750) = 55 
    [13.750, 15.000) = 12 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.907 ms/op
     p(50.0000) =      2.519 ms/op
     p(90.0000) =      2.974 ms/op
     p(95.0000) =      3.080 ms/op
     p(99.0000) =      3.588 ms/op
     p(99.9000) =      6.365 ms/op
     p(99.9900) =     13.091 ms/op
     p(99.9990) =     14.111 ms/op
     p(99.9999) =     14.221 ms/op
    p(100.0000) =     14.221 ms/op


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
# Warmup Iteration   1: 3.903 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 2.609 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.530 ±(99.9%) 0.006 ms/op
Iteration   1: 2.523 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.047 ms/op
                 getUser·p0.50:   2.544 ms/op
                 getUser·p0.90:   3.076 ms/op
                 getUser·p0.95:   3.199 ms/op
                 getUser·p0.99:   3.682 ms/op
                 getUser·p0.999:  7.105 ms/op
                 getUser·p0.9999: 13.691 ms/op
                 getUser·p1.00:   14.451 ms/op

Iteration   2: 2.511 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.829 ms/op
                 getUser·p0.50:   2.552 ms/op
                 getUser·p0.90:   3.035 ms/op
                 getUser·p0.95:   3.158 ms/op
                 getUser·p0.99:   3.924 ms/op
                 getUser·p0.999:  10.151 ms/op
                 getUser·p0.9999: 14.005 ms/op
                 getUser·p1.00:   14.565 ms/op

Iteration   3: 2.536 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.029 ms/op
                 getUser·p0.50:   2.568 ms/op
                 getUser·p0.90:   3.088 ms/op
                 getUser·p0.95:   3.244 ms/op
                 getUser·p0.99:   4.130 ms/op
                 getUser·p0.999:  7.757 ms/op
                 getUser·p0.9999: 11.711 ms/op
                 getUser·p1.00:   12.141 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 380137
  mean =      2.523 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 64 
    [ 1.250,  2.500) = 186063 
    [ 2.500,  3.750) = 189091 
    [ 3.750,  5.000) = 3754 
    [ 5.000,  6.250) = 678 
    [ 6.250,  7.500) = 89 
    [ 7.500,  8.750) = 73 
    [ 8.750, 10.000) = 36 
    [10.000, 11.250) = 98 
    [11.250, 12.500) = 104 
    [12.500, 13.750) = 64 
    [13.750, 15.000) = 23 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.829 ms/op
     p(50.0000) =      2.556 ms/op
     p(90.0000) =      3.068 ms/op
     p(95.0000) =      3.199 ms/op
     p(99.0000) =      3.916 ms/op
     p(99.9000) =      7.715 ms/op
     p(99.9900) =     13.467 ms/op
     p(99.9990) =     14.533 ms/op
     p(99.9999) =     14.565 ms/op
    p(100.0000) =     14.565 ms/op


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
# Warmup Iteration   1: 4.807 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 3.108 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.097 ±(99.9%) 0.009 ms/op
Iteration   1: 3.034 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.893 ms/op
                 listUser·p0.50:   2.966 ms/op
                 listUser·p0.90:   3.932 ms/op
                 listUser·p0.95:   4.456 ms/op
                 listUser·p0.99:   5.644 ms/op
                 listUser·p0.999:  9.847 ms/op
                 listUser·p0.9999: 11.835 ms/op
                 listUser·p1.00:   12.747 ms/op

Iteration   2: 3.027 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.944 ms/op
                 listUser·p0.50:   2.974 ms/op
                 listUser·p0.90:   3.879 ms/op
                 listUser·p0.95:   4.375 ms/op
                 listUser·p0.99:   5.530 ms/op
                 listUser·p0.999:  9.902 ms/op
                 listUser·p0.9999: 11.968 ms/op
                 listUser·p1.00:   12.632 ms/op

Iteration   3: 3.045 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.766 ms/op
                 listUser·p0.50:   2.974 ms/op
                 listUser·p0.90:   3.932 ms/op
                 listUser·p0.95:   4.465 ms/op
                 listUser·p0.99:   5.562 ms/op
                 listUser·p0.999:  8.978 ms/op
                 listUser·p0.9999: 13.427 ms/op
                 listUser·p1.00:   14.221 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 316032
  mean =      3.035 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 109 
    [ 1.250,  2.500) = 87602 
    [ 2.500,  3.750) = 187696 
    [ 3.750,  5.000) = 33197 
    [ 5.000,  6.250) = 6207 
    [ 6.250,  7.500) = 558 
    [ 7.500,  8.750) = 186 
    [ 8.750, 10.000) = 228 
    [10.000, 11.250) = 163 
    [11.250, 12.500) = 68 
    [12.500, 13.750) = 16 
    [13.750, 15.000) = 2 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.766 ms/op
     p(50.0000) =      2.970 ms/op
     p(90.0000) =      3.916 ms/op
     p(95.0000) =      4.432 ms/op
     p(99.0000) =      5.579 ms/op
     p(99.9000) =      9.716 ms/op
     p(99.9900) =     12.278 ms/op
     p(99.9990) =     13.624 ms/op
     p(99.9999) =     14.221 ms/op
    p(100.0000) =     14.221 ms/op


# Run complete. Total time: 00:12:59

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.230 ± 1.074  ops/ms
ClientPb.existUser                       thrpt       3  12.903 ± 0.584  ops/ms
ClientPb.getUser                         thrpt       3  12.835 ± 1.695  ops/ms
ClientPb.listUser                        thrpt       3  10.592 ± 1.207  ops/ms
ClientPb.createUser                       avgt       3   2.586 ± 0.329   ms/op
ClientPb.existUser                        avgt       3   2.488 ± 0.162   ms/op
ClientPb.getUser                          avgt       3   2.536 ± 0.518   ms/op
ClientPb.listUser                         avgt       3   2.980 ± 0.147   ms/op
ClientPb.createUser                     sample  373388   2.569 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.920           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.654           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.117           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.219           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.711           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.939           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.200           ms/op
ClientPb.createUser:createUser·p1.00    sample          15.991           ms/op
ClientPb.existUser                      sample  392080   2.446 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.907           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.519           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.974           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.080           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.588           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.365           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.091           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.221           ms/op
ClientPb.getUser                        sample  380137   2.523 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.829           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.556           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.068           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.199           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.916           ms/op
ClientPb.getUser:getUser·p0.999         sample           7.715           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.467           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.565           ms/op
ClientPb.listUser                       sample  316032   3.035 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.766           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.970           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.916           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.432           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.579           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.716           ms/op
ClientPb.listUser:listUser·p0.9999      sample          12.278           ms/op
ClientPb.listUser:listUser·p1.00        sample          14.221           ms/op
