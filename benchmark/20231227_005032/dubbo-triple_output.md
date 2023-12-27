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
# Warmup Iteration   1: 4.532 ops/ms
# Warmup Iteration   2: 12.077 ops/ms
# Warmup Iteration   3: 12.257 ops/ms
Iteration   1: 12.554 ops/ms
Iteration   2: 12.273 ops/ms
Iteration   3: 12.532 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.453 ±(99.9%) 2.854 ops/ms [Average]
  (min, avg, max) = (12.273, 12.453, 12.554), stdev = 0.156
  CI (99.9%): [9.599, 15.307] (assumes normal distribution)


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
# Warmup Iteration   1: 8.091 ops/ms
# Warmup Iteration   2: 12.879 ops/ms
# Warmup Iteration   3: 12.991 ops/ms
Iteration   1: 12.940 ops/ms
Iteration   2: 12.970 ops/ms
Iteration   3: 12.860 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.924 ±(99.9%) 1.032 ops/ms [Average]
  (min, avg, max) = (12.860, 12.924, 12.970), stdev = 0.057
  CI (99.9%): [11.891, 13.956] (assumes normal distribution)


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
# Warmup Iteration   1: 8.076 ops/ms
# Warmup Iteration   2: 12.653 ops/ms
# Warmup Iteration   3: 12.873 ops/ms
Iteration   1: 12.942 ops/ms
Iteration   2: 12.864 ops/ms
Iteration   3: 13.023 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.943 ±(99.9%) 1.452 ops/ms [Average]
  (min, avg, max) = (12.864, 12.943, 13.023), stdev = 0.080
  CI (99.9%): [11.491, 14.395] (assumes normal distribution)


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
# Warmup Iteration   1: 6.631 ops/ms
# Warmup Iteration   2: 10.546 ops/ms
# Warmup Iteration   3: 10.574 ops/ms
Iteration   1: 10.558 ops/ms
Iteration   2: 10.657 ops/ms
Iteration   3: 10.658 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.624 ±(99.9%) 1.049 ops/ms [Average]
  (min, avg, max) = (10.558, 10.624, 10.658), stdev = 0.058
  CI (99.9%): [9.575, 11.673] (assumes normal distribution)


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
# Warmup Iteration   1: 4.138 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 2.567 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.502 ±(99.9%) 0.005 ms/op
Iteration   1: 2.580 ±(99.9%) 0.005 ms/op
Iteration   2: 2.519 ±(99.9%) 0.004 ms/op
Iteration   3: 2.495 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.531 ±(99.9%) 0.799 ms/op [Average]
  (min, avg, max) = (2.495, 2.531, 2.580), stdev = 0.044
  CI (99.9%): [1.732, 3.331] (assumes normal distribution)


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
# Warmup Iteration   1: 3.753 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.460 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.490 ±(99.9%) 0.004 ms/op
Iteration   1: 2.435 ±(99.9%) 0.004 ms/op
Iteration   2: 2.463 ±(99.9%) 0.004 ms/op
Iteration   3: 2.455 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.451 ±(99.9%) 0.262 ms/op [Average]
  (min, avg, max) = (2.435, 2.451, 2.463), stdev = 0.014
  CI (99.9%): [2.189, 2.714] (assumes normal distribution)


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
# Warmup Iteration   1: 4.029 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.603 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.514 ±(99.9%) 0.004 ms/op
Iteration   1: 2.488 ±(99.9%) 0.003 ms/op
Iteration   2: 2.461 ±(99.9%) 0.004 ms/op
Iteration   3: 2.498 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.482 ±(99.9%) 0.351 ms/op [Average]
  (min, avg, max) = (2.461, 2.482, 2.498), stdev = 0.019
  CI (99.9%): [2.131, 2.833] (assumes normal distribution)


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
# Warmup Iteration   1: 4.832 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.099 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.042 ±(99.9%) 0.005 ms/op
Iteration   1: 3.024 ±(99.9%) 0.006 ms/op
Iteration   2: 3.029 ±(99.9%) 0.006 ms/op
Iteration   3: 3.043 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.032 ±(99.9%) 0.182 ms/op [Average]
  (min, avg, max) = (3.024, 3.032, 3.043), stdev = 0.010
  CI (99.9%): [2.850, 3.214] (assumes normal distribution)


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
# Warmup Iteration   1: 4.115 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 2.625 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.504 ±(99.9%) 0.006 ms/op
Iteration   1: 2.526 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.879 ms/op
                 createUser·p0.50:   2.576 ms/op
                 createUser·p0.90:   3.064 ms/op
                 createUser·p0.95:   3.187 ms/op
                 createUser·p0.99:   3.842 ms/op
                 createUser·p0.999:  11.649 ms/op
                 createUser·p0.9999: 13.342 ms/op
                 createUser·p1.00:   13.615 ms/op

Iteration   2: 2.518 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.053 ms/op
                 createUser·p0.50:   2.613 ms/op
                 createUser·p0.90:   3.052 ms/op
                 createUser·p0.95:   3.146 ms/op
                 createUser·p0.99:   3.518 ms/op
                 createUser·p0.999:  9.390 ms/op
                 createUser·p0.9999: 12.403 ms/op
                 createUser·p1.00:   13.550 ms/op

Iteration   3: 2.568 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.027 ms/op
                 createUser·p0.50:   2.605 ms/op
                 createUser·p0.90:   3.121 ms/op
                 createUser·p0.95:   3.269 ms/op
                 createUser·p0.99:   4.183 ms/op
                 createUser·p0.999:  8.626 ms/op
                 createUser·p0.9999: 10.187 ms/op
                 createUser·p1.00:   11.207 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 377934
  mean =      2.537 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 33 
    [ 1.250,  2.500) = 181646 
    [ 2.500,  3.750) = 191812 
    [ 3.750,  5.000) = 3440 
    [ 5.000,  6.250) = 509 
    [ 6.250,  7.500) = 89 
    [ 7.500,  8.750) = 35 
    [ 8.750, 10.000) = 111 
    [10.000, 11.250) = 89 
    [11.250, 12.500) = 77 
    [12.500, 13.750) = 93 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.879 ms/op
     p(50.0000) =      2.597 ms/op
     p(90.0000) =      3.076 ms/op
     p(95.0000) =      3.199 ms/op
     p(99.0000) =      3.842 ms/op
     p(99.9000) =      8.668 ms/op
     p(99.9900) =     13.176 ms/op
     p(99.9990) =     13.537 ms/op
     p(99.9999) =     13.615 ms/op
    p(100.0000) =     13.615 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 3.908 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 2.501 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.462 ±(99.9%) 0.005 ms/op
Iteration   1: 2.471 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.057 ms/op
                 existUser·p0.50:   2.548 ms/op
                 existUser·p0.90:   3.002 ms/op
                 existUser·p0.95:   3.117 ms/op
                 existUser·p0.99:   3.609 ms/op
                 existUser·p0.999:  6.741 ms/op
                 existUser·p0.9999: 14.336 ms/op
                 existUser·p1.00:   14.631 ms/op

Iteration   2: 2.451 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.006 ms/op
                 existUser·p0.50:   2.515 ms/op
                 existUser·p0.90:   2.970 ms/op
                 existUser·p0.95:   3.064 ms/op
                 existUser·p0.99:   3.449 ms/op
                 existUser·p0.999:  8.285 ms/op
                 existUser·p0.9999: 12.942 ms/op
                 existUser·p1.00:   13.599 ms/op

Iteration   3: 2.455 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.876 ms/op
                 existUser·p0.50:   2.462 ms/op
                 existUser·p0.90:   2.994 ms/op
                 existUser·p0.95:   3.113 ms/op
                 existUser·p0.99:   3.637 ms/op
                 existUser·p0.999:  6.421 ms/op
                 existUser·p0.9999: 12.075 ms/op
                 existUser·p1.00:   12.337 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 390047
  mean =      2.459 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 47 
    [ 1.250,  2.500) = 194516 
    [ 2.500,  3.750) = 192572 
    [ 3.750,  5.000) = 2180 
    [ 5.000,  6.250) = 281 
    [ 6.250,  7.500) = 76 
    [ 7.500,  8.750) = 20 
    [ 8.750, 10.000) = 74 
    [10.000, 11.250) = 92 
    [11.250, 12.500) = 85 
    [12.500, 13.750) = 86 
    [13.750, 15.000) = 18 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.876 ms/op
     p(50.0000) =      2.507 ms/op
     p(90.0000) =      2.990 ms/op
     p(95.0000) =      3.097 ms/op
     p(99.0000) =      3.576 ms/op
     p(99.9000) =      6.578 ms/op
     p(99.9900) =     13.435 ms/op
     p(99.9990) =     14.457 ms/op
     p(99.9999) =     14.631 ms/op
    p(100.0000) =     14.631 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 4.031 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 2.588 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.499 ±(99.9%) 0.005 ms/op
Iteration   1: 2.506 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.989 ms/op
                 getUser·p0.50:   2.527 ms/op
                 getUser·p0.90:   3.047 ms/op
                 getUser·p0.95:   3.183 ms/op
                 getUser·p0.99:   4.125 ms/op
                 getUser·p0.999:  11.473 ms/op
                 getUser·p0.9999: 13.865 ms/op
                 getUser·p1.00:   14.549 ms/op

Iteration   2: 2.520 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.808 ms/op
                 getUser·p0.50:   2.560 ms/op
                 getUser·p0.90:   3.060 ms/op
                 getUser·p0.95:   3.187 ms/op
                 getUser·p0.99:   4.116 ms/op
                 getUser·p0.999:  9.115 ms/op
                 getUser·p0.9999: 13.970 ms/op
                 getUser·p1.00:   15.483 ms/op

Iteration   3: 2.512 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.822 ms/op
                 getUser·p0.50:   2.548 ms/op
                 getUser·p0.90:   3.064 ms/op
                 getUser·p0.95:   3.199 ms/op
                 getUser·p0.99:   3.785 ms/op
                 getUser·p0.999:  8.262 ms/op
                 getUser·p0.9999: 11.679 ms/op
                 getUser·p1.00:   12.173 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 381680
  mean =      2.513 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 74 
    [ 1.250,  2.500) = 187350 
    [ 2.500,  3.750) = 189010 
    [ 3.750,  5.000) = 3916 
    [ 5.000,  6.250) = 772 
    [ 6.250,  7.500) = 123 
    [ 7.500,  8.750) = 51 
    [ 8.750, 10.000) = 70 
    [10.000, 11.250) = 109 
    [11.250, 12.500) = 78 
    [12.500, 13.750) = 89 
    [13.750, 15.000) = 36 
    [15.000, 16.250) = 2 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.808 ms/op
     p(50.0000) =      2.544 ms/op
     p(90.0000) =      3.056 ms/op
     p(95.0000) =      3.191 ms/op
     p(99.0000) =      3.977 ms/op
     p(99.9000) =      8.869 ms/op
     p(99.9900) =     13.760 ms/op
     p(99.9990) =     14.549 ms/op
     p(99.9999) =     15.483 ms/op
    p(100.0000) =     15.483 ms/op


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
# Warmup Iteration   1: 4.883 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 3.065 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.028 ±(99.9%) 0.009 ms/op
Iteration   1: 3.028 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.961 ms/op
                 listUser·p0.50:   2.953 ms/op
                 listUser·p0.90:   3.899 ms/op
                 listUser·p0.95:   4.432 ms/op
                 listUser·p0.99:   5.685 ms/op
                 listUser·p0.999:  9.912 ms/op
                 listUser·p0.9999: 15.237 ms/op
                 listUser·p1.00:   17.170 ms/op

Iteration   2: 3.015 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.898 ms/op
                 listUser·p0.50:   2.961 ms/op
                 listUser·p0.90:   3.895 ms/op
                 listUser·p0.95:   4.399 ms/op
                 listUser·p0.99:   5.513 ms/op
                 listUser·p0.999:  9.207 ms/op
                 listUser·p0.9999: 10.764 ms/op
                 listUser·p1.00:   11.649 ms/op

Iteration   3: 3.020 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.883 ms/op
                 listUser·p0.50:   2.961 ms/op
                 listUser·p0.90:   3.899 ms/op
                 listUser·p0.95:   4.407 ms/op
                 listUser·p0.99:   5.726 ms/op
                 listUser·p0.999:  9.224 ms/op
                 listUser·p0.9999: 12.301 ms/op
                 listUser·p1.00:   13.238 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 317484
  mean =      3.021 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 122 
    [ 1.250,  2.500) = 90670 
    [ 2.500,  3.750) = 187043 
    [ 3.750,  5.000) = 32071 
    [ 5.000,  6.250) = 6068 
    [ 6.250,  7.500) = 777 
    [ 7.500,  8.750) = 254 
    [ 8.750, 10.000) = 274 
    [10.000, 11.250) = 159 
    [11.250, 12.500) = 22 
    [12.500, 13.750) = 9 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 13 
    [16.250, 17.500) = 2 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.883 ms/op
     p(50.0000) =      2.957 ms/op
     p(90.0000) =      3.899 ms/op
     p(95.0000) =      4.415 ms/op
     p(99.0000) =      5.636 ms/op
     p(99.9000) =      9.535 ms/op
     p(99.9900) =     12.321 ms/op
     p(99.9990) =     16.068 ms/op
     p(99.9999) =     17.170 ms/op
    p(100.0000) =     17.170 ms/op


# Run complete. Total time: 00:13:00

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.453 ± 2.854  ops/ms
ClientPb.existUser                       thrpt       3  12.924 ± 1.032  ops/ms
ClientPb.getUser                         thrpt       3  12.943 ± 1.452  ops/ms
ClientPb.listUser                        thrpt       3  10.624 ± 1.049  ops/ms
ClientPb.createUser                       avgt       3   2.531 ± 0.799   ms/op
ClientPb.existUser                        avgt       3   2.451 ± 0.262   ms/op
ClientPb.getUser                          avgt       3   2.482 ± 0.351   ms/op
ClientPb.listUser                         avgt       3   3.032 ± 0.182   ms/op
ClientPb.createUser                     sample  377934   2.537 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.879           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.597           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.076           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.199           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.842           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.668           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.176           ms/op
ClientPb.createUser:createUser·p1.00    sample          13.615           ms/op
ClientPb.existUser                      sample  390047   2.459 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.876           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.507           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.990           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.097           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.576           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.578           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.435           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.631           ms/op
ClientPb.getUser                        sample  381680   2.513 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.808           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.544           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.056           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.191           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.977           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.869           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.760           ms/op
ClientPb.getUser:getUser·p1.00          sample          15.483           ms/op
ClientPb.listUser                       sample  317484   3.021 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.883           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.957           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.899           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.415           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.636           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.535           ms/op
ClientPb.listUser:listUser·p0.9999      sample          12.321           ms/op
ClientPb.listUser:listUser·p1.00        sample          17.170           ms/op
