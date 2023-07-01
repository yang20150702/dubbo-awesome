# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.504 ops/ms
# Warmup Iteration   2: 5.870 ops/ms
# Warmup Iteration   3: 9.317 ops/ms
Iteration   1: 9.601 ops/ms
Iteration   2: 9.739 ops/ms
Iteration   3: 10.163 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.834 ±(99.9%) 5.339 ops/ms [Average]
  (min, avg, max) = (9.601, 9.834, 10.163), stdev = 0.293
  CI (99.9%): [4.495, 15.173] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:11:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.443 ops/ms
# Warmup Iteration   2: 9.280 ops/ms
# Warmup Iteration   3: 10.255 ops/ms
Iteration   1: 10.473 ops/ms
Iteration   2: 10.373 ops/ms
Iteration   3: 10.359 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.402 ±(99.9%) 1.135 ops/ms [Average]
  (min, avg, max) = (10.359, 10.402, 10.473), stdev = 0.062
  CI (99.9%): [9.266, 11.537] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:55
# Fork: 1 of 1
# Warmup Iteration   1: 3.334 ops/ms
# Warmup Iteration   2: 9.004 ops/ms
# Warmup Iteration   3: 9.508 ops/ms
Iteration   1: 9.931 ops/ms
Iteration   2: 10.040 ops/ms
Iteration   3: 10.284 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  10.085 ±(99.9%) 3.298 ops/ms [Average]
  (min, avg, max) = (9.931, 10.085, 10.284), stdev = 0.181
  CI (99.9%): [6.787, 13.383] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 3.559 ops/ms
# Warmup Iteration   2: 7.960 ops/ms
# Warmup Iteration   3: 8.340 ops/ms
Iteration   1: 8.391 ops/ms
Iteration   2: 8.533 ops/ms
Iteration   3: 8.781 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.568 ±(99.9%) 3.592 ops/ms [Average]
  (min, avg, max) = (8.391, 8.568, 8.781), stdev = 0.197
  CI (99.9%): [4.976, 12.161] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 8.016 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.516 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.371 ±(99.9%) 0.005 ms/op
Iteration   1: 3.258 ±(99.9%) 0.005 ms/op
Iteration   2: 3.144 ±(99.9%) 0.003 ms/op
Iteration   3: 3.215 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.206 ±(99.9%) 1.052 ms/op [Average]
  (min, avg, max) = (3.144, 3.206, 3.258), stdev = 0.058
  CI (99.9%): [2.154, 4.258] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:38
# Fork: 1 of 1
# Warmup Iteration   1: 7.455 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 3.358 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.224 ±(99.9%) 0.004 ms/op
Iteration   1: 3.156 ±(99.9%) 0.005 ms/op
Iteration   2: 3.096 ±(99.9%) 0.007 ms/op
Iteration   3: 3.083 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.112 ±(99.9%) 0.706 ms/op [Average]
  (min, avg, max) = (3.083, 3.112, 3.156), stdev = 0.039
  CI (99.9%): [2.406, 3.818] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 8.549 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 3.565 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.412 ±(99.9%) 0.003 ms/op
Iteration   1: 3.248 ±(99.9%) 0.005 ms/op
Iteration   2: 3.110 ±(99.9%) 0.007 ms/op
Iteration   3: 3.130 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.163 ±(99.9%) 1.361 ms/op [Average]
  (min, avg, max) = (3.110, 3.163, 3.248), stdev = 0.075
  CI (99.9%): [1.802, 4.524] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 8.592 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 4.136 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.920 ±(99.9%) 0.005 ms/op
Iteration   1: 3.820 ±(99.9%) 0.006 ms/op
Iteration   2: 3.676 ±(99.9%) 0.006 ms/op
Iteration   3: 3.903 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.800 ±(99.9%) 2.096 ms/op [Average]
  (min, avg, max) = (3.676, 3.800, 3.903), stdev = 0.115
  CI (99.9%): [1.704, 5.896] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 6.984 ±(99.9%) 0.084 ms/op
# Warmup Iteration   2: 3.773 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.429 ±(99.9%) 0.010 ms/op
Iteration   1: 3.214 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.009 ms/op
                 createUser·p0.50:   3.133 ms/op
                 createUser·p0.90:   3.535 ms/op
                 createUser·p0.95:   4.067 ms/op
                 createUser·p0.99:   5.860 ms/op
                 createUser·p0.999:  18.757 ms/op
                 createUser·p0.9999: 25.757 ms/op
                 createUser·p1.00:   26.083 ms/op

Iteration   2: 3.235 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.040 ms/op
                 createUser·p0.50:   3.154 ms/op
                 createUser·p0.90:   3.604 ms/op
                 createUser·p0.95:   3.969 ms/op
                 createUser·p0.99:   5.784 ms/op
                 createUser·p0.999:  17.145 ms/op
                 createUser·p0.9999: 32.215 ms/op
                 createUser·p1.00:   32.866 ms/op

Iteration   3: 3.217 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.124 ms/op
                 createUser·p0.50:   3.195 ms/op
                 createUser·p0.90:   3.461 ms/op
                 createUser·p0.95:   3.781 ms/op
                 createUser·p0.99:   5.915 ms/op
                 createUser·p0.999:  14.661 ms/op
                 createUser·p0.9999: 37.622 ms/op
                 createUser·p1.00:   38.076 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 297839
  mean =      3.222 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 20120 
    [ 2.500,  5.000) = 271338 
    [ 5.000,  7.500) = 5307 
    [ 7.500, 10.000) = 454 
    [10.000, 12.500) = 150 
    [12.500, 15.000) = 143 
    [15.000, 17.500) = 72 
    [17.500, 20.000) = 85 
    [20.000, 22.500) = 82 
    [22.500, 25.000) = 4 
    [25.000, 27.500) = 20 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 32 
    [32.500, 35.000) = 9 
    [35.000, 37.500) = 11 

  Percentiles, ms/op:
      p(0.0000) =      1.009 ms/op
     p(50.0000) =      3.162 ms/op
     p(90.0000) =      3.539 ms/op
     p(95.0000) =      3.916 ms/op
     p(99.0000) =      5.862 ms/op
     p(99.9000) =     15.254 ms/op
     p(99.9900) =     32.710 ms/op
     p(99.9990) =     37.883 ms/op
     p(99.9999) =     38.076 ms/op
    p(100.0000) =     38.076 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 7.602 ±(99.9%) 0.090 ms/op
# Warmup Iteration   2: 3.392 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.150 ±(99.9%) 0.008 ms/op
Iteration   1: 3.045 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.233 ms/op
                 existUser·p0.50:   2.978 ms/op
                 existUser·p0.90:   3.256 ms/op
                 existUser·p0.95:   3.440 ms/op
                 existUser·p0.99:   4.628 ms/op
                 existUser·p0.999:  7.913 ms/op
                 existUser·p0.9999: 27.410 ms/op
                 existUser·p1.00:   29.524 ms/op

Iteration   2: 3.041 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.206 ms/op
                 existUser·p0.50:   2.994 ms/op
                 existUser·p0.90:   3.162 ms/op
                 existUser·p0.95:   3.314 ms/op
                 existUser·p0.99:   4.719 ms/op
                 existUser·p0.999:  13.943 ms/op
                 existUser·p0.9999: 23.918 ms/op
                 existUser·p1.00:   25.657 ms/op

Iteration   3: 3.212 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.548 ms/op
                 existUser·p0.50:   3.162 ms/op
                 existUser·p0.90:   3.498 ms/op
                 existUser·p0.95:   3.936 ms/op
                 existUser·p0.99:   5.947 ms/op
                 existUser·p0.999:  14.041 ms/op
                 existUser·p0.9999: 21.137 ms/op
                 existUser·p1.00:   21.398 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 309791
  mean =      3.098 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 20700 
    [ 2.500,  5.000) = 284660 
    [ 5.000,  7.500) = 3800 
    [ 7.500, 10.000) = 147 
    [10.000, 12.500) = 90 
    [12.500, 15.000) = 101 
    [15.000, 17.500) = 35 
    [17.500, 20.000) = 113 
    [20.000, 22.500) = 83 
    [22.500, 25.000) = 29 
    [25.000, 27.500) = 24 

  Percentiles, ms/op:
      p(0.0000) =      1.206 ms/op
     p(50.0000) =      3.047 ms/op
     p(90.0000) =      3.281 ms/op
     p(95.0000) =      3.555 ms/op
     p(99.0000) =      5.382 ms/op
     p(99.9000) =     13.943 ms/op
     p(99.9900) =     26.608 ms/op
     p(99.9990) =     29.118 ms/op
     p(99.9999) =     29.524 ms/op
    p(100.0000) =     29.524 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 7.673 ±(99.9%) 0.100 ms/op
# Warmup Iteration   2: 3.522 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.241 ±(99.9%) 0.010 ms/op
Iteration   1: 3.164 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.139 ms/op
                 getUser·p0.50:   3.076 ms/op
                 getUser·p0.90:   3.494 ms/op
                 getUser·p0.95:   3.822 ms/op
                 getUser·p0.99:   5.521 ms/op
                 getUser·p0.999:  17.555 ms/op
                 getUser·p0.9999: 20.087 ms/op
                 getUser·p1.00:   20.840 ms/op

Iteration   2: 3.135 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.434 ms/op
                 getUser·p0.50:   3.027 ms/op
                 getUser·p0.90:   3.367 ms/op
                 getUser·p0.95:   3.551 ms/op
                 getUser·p0.99:   5.874 ms/op
                 getUser·p0.999:  12.021 ms/op
                 getUser·p0.9999: 20.604 ms/op
                 getUser·p1.00:   21.266 ms/op

Iteration   3: 3.172 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   1.165 ms/op
                 getUser·p0.50:   3.056 ms/op
                 getUser·p0.90:   3.670 ms/op
                 getUser·p0.95:   3.961 ms/op
                 getUser·p0.99:   5.235 ms/op
                 getUser·p0.999:  8.556 ms/op
                 getUser·p0.9999: 19.956 ms/op
                 getUser·p1.00:   21.234 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 304015
  mean =      3.157 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13270 
    [ 2.500,  5.000) = 285089 
    [ 5.000,  7.500) = 4883 
    [ 7.500, 10.000) = 353 
    [10.000, 12.500) = 98 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 40 
    [17.500, 20.000) = 209 
    [20.000, 22.500) = 41 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.139 ms/op
     p(50.0000) =      3.047 ms/op
     p(90.0000) =      3.490 ms/op
     p(95.0000) =      3.830 ms/op
     p(99.0000) =      5.587 ms/op
     p(99.9000) =     14.753 ms/op
     p(99.9900) =     20.120 ms/op
     p(99.9990) =     21.232 ms/op
     p(99.9999) =     21.266 ms/op
    p(100.0000) =     21.266 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 8.660 ±(99.9%) 0.109 ms/op
# Warmup Iteration   2: 4.150 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.794 ±(99.9%) 0.011 ms/op
Iteration   1: 3.672 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.179 ms/op
                 listUser·p0.50:   3.580 ms/op
                 listUser·p0.90:   3.854 ms/op
                 listUser·p0.95:   4.100 ms/op
                 listUser·p0.99:   6.676 ms/op
                 listUser·p0.999:  13.631 ms/op
                 listUser·p0.9999: 18.893 ms/op
                 listUser·p1.00:   19.792 ms/op

Iteration   2: 3.762 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.552 ms/op
                 listUser·p0.50:   3.609 ms/op
                 listUser·p0.90:   4.059 ms/op
                 listUser·p0.95:   4.293 ms/op
                 listUser·p0.99:   7.422 ms/op
                 listUser·p0.999:  14.452 ms/op
                 listUser·p0.9999: 21.791 ms/op
                 listUser·p1.00:   22.282 ms/op

Iteration   3: 3.680 ±(99.9%) 0.007 ms/op
                 listUser·p0.00:   1.505 ms/op
                 listUser·p0.50:   3.568 ms/op
                 listUser·p0.90:   3.973 ms/op
                 listUser·p0.95:   4.149 ms/op
                 listUser·p0.99:   6.308 ms/op
                 listUser·p0.999:  12.960 ms/op
                 listUser·p0.9999: 15.188 ms/op
                 listUser·p1.00:   15.860 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 259159
  mean =      3.704 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 54 
    [ 2.500,  5.000) = 252267 
    [ 5.000,  7.500) = 5040 
    [ 7.500, 10.000) = 1096 
    [10.000, 12.500) = 228 
    [12.500, 15.000) = 333 
    [15.000, 17.500) = 79 
    [17.500, 20.000) = 41 
    [20.000, 22.500) = 21 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.505 ms/op
     p(50.0000) =      3.584 ms/op
     p(90.0000) =      3.981 ms/op
     p(95.0000) =      4.190 ms/op
     p(99.0000) =      6.906 ms/op
     p(99.9000) =     13.621 ms/op
     p(99.9900) =     19.079 ms/op
     p(99.9990) =     22.047 ms/op
     p(99.9999) =     22.282 ms/op
    p(100.0000) =     22.282 ms/op


# Run complete. Total time: 00:13:08

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.834 ± 5.339  ops/ms
ClientPb.existUser                       thrpt       3  10.402 ± 1.135  ops/ms
ClientPb.getUser                         thrpt       3  10.085 ± 3.298  ops/ms
ClientPb.listUser                        thrpt       3   8.568 ± 3.592  ops/ms
ClientPb.createUser                       avgt       3   3.206 ± 1.052   ms/op
ClientPb.existUser                        avgt       3   3.112 ± 0.706   ms/op
ClientPb.getUser                          avgt       3   3.163 ± 1.361   ms/op
ClientPb.listUser                         avgt       3   3.800 ± 2.096   ms/op
ClientPb.createUser                     sample  297839   3.222 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.009           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.162           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.539           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.916           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.862           ms/op
ClientPb.createUser:createUser·p0.999   sample          15.254           ms/op
ClientPb.createUser:createUser·p0.9999  sample          32.710           ms/op
ClientPb.createUser:createUser·p1.00    sample          38.076           ms/op
ClientPb.existUser                      sample  309791   3.098 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.206           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.047           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.281           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.555           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.382           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.943           ms/op
ClientPb.existUser:existUser·p0.9999    sample          26.608           ms/op
ClientPb.existUser:existUser·p1.00      sample          29.524           ms/op
ClientPb.getUser                        sample  304015   3.157 ± 0.004   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.139           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.047           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.490           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.830           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.587           ms/op
ClientPb.getUser:getUser·p0.999         sample          14.753           ms/op
ClientPb.getUser:getUser·p0.9999        sample          20.120           ms/op
ClientPb.getUser:getUser·p1.00          sample          21.266           ms/op
ClientPb.listUser                       sample  259159   3.704 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.505           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.584           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.981           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.190           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.906           ms/op
ClientPb.listUser:listUser·p0.999       sample          13.621           ms/op
ClientPb.listUser:listUser·p0.9999      sample          19.079           ms/op
ClientPb.listUser:listUser·p1.00        sample          22.282           ms/op
