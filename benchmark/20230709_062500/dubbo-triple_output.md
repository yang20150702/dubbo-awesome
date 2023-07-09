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
# Warmup Iteration   1: 1.941 ops/ms
# Warmup Iteration   2: 4.597 ops/ms
# Warmup Iteration   3: 7.836 ops/ms
Iteration   1: 8.687 ops/ms
Iteration   2: 8.937 ops/ms
Iteration   3: 9.035 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  8.887 ±(99.9%) 3.278 ops/ms [Average]
  (min, avg, max) = (8.687, 8.887, 9.035), stdev = 0.180
  CI (99.9%): [5.608, 12.165] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:09
# Fork: 1 of 1
# Warmup Iteration   1: 2.231 ops/ms
# Warmup Iteration   2: 7.527 ops/ms
# Warmup Iteration   3: 8.629 ops/ms
Iteration   1: 8.852 ops/ms
Iteration   2: 9.040 ops/ms
Iteration   3: 9.007 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.966 ±(99.9%) 1.828 ops/ms [Average]
  (min, avg, max) = (8.852, 8.966, 9.040), stdev = 0.100
  CI (99.9%): [7.139, 10.794] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:03
# Fork: 1 of 1
# Warmup Iteration   1: 2.416 ops/ms
# Warmup Iteration   2: 7.788 ops/ms
# Warmup Iteration   3: 8.672 ops/ms
Iteration   1: 8.566 ops/ms
Iteration   2: 8.947 ops/ms
Iteration   3: 9.494 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.002 ±(99.9%) 8.508 ops/ms [Average]
  (min, avg, max) = (8.566, 9.002, 9.494), stdev = 0.466
  CI (99.9%): [0.494, 17.510] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:53
# Fork: 1 of 1
# Warmup Iteration   1: 2.789 ops/ms
# Warmup Iteration   2: 7.324 ops/ms
# Warmup Iteration   3: 7.738 ops/ms
Iteration   1: 7.800 ops/ms
Iteration   2: 7.772 ops/ms
Iteration   3: 7.746 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.772 ±(99.9%) 0.493 ops/ms [Average]
  (min, avg, max) = (7.746, 7.772, 7.800), stdev = 0.027
  CI (99.9%): [7.280, 8.265] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:48
# Fork: 1 of 1
# Warmup Iteration   1: 11.120 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 3.813 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.710 ±(99.9%) 0.003 ms/op
Iteration   1: 3.626 ±(99.9%) 0.004 ms/op
Iteration   2: 3.476 ±(99.9%) 0.006 ms/op
Iteration   3: 3.641 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.581 ±(99.9%) 1.665 ms/op [Average]
  (min, avg, max) = (3.476, 3.581, 3.641), stdev = 0.091
  CI (99.9%): [1.916, 5.247] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:42
# Fork: 1 of 1
# Warmup Iteration   1: 9.969 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 4.217 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.518 ±(99.9%) 0.004 ms/op
Iteration   1: 3.478 ±(99.9%) 0.010 ms/op
Iteration   2: 3.630 ±(99.9%) 0.006 ms/op
Iteration   3: 3.534 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.548 ±(99.9%) 1.407 ms/op [Average]
  (min, avg, max) = (3.478, 3.548, 3.630), stdev = 0.077
  CI (99.9%): [2.141, 4.954] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 9.890 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 4.157 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.853 ±(99.9%) 0.007 ms/op
Iteration   1: 3.581 ±(99.9%) 0.006 ms/op
Iteration   2: 3.781 ±(99.9%) 0.008 ms/op
Iteration   3: 3.516 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.626 ±(99.9%) 2.526 ms/op [Average]
  (min, avg, max) = (3.516, 3.626, 3.781), stdev = 0.138
  CI (99.9%): [1.100, 6.152] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 10.744 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 5.014 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.233 ±(99.9%) 0.009 ms/op
Iteration   1: 4.126 ±(99.9%) 0.009 ms/op
Iteration   2: 4.074 ±(99.9%) 0.010 ms/op
Iteration   3: 4.058 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.086 ±(99.9%) 0.647 ms/op [Average]
  (min, avg, max) = (4.058, 4.086, 4.126), stdev = 0.035
  CI (99.9%): [3.439, 4.733] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 9.839 ±(99.9%) 0.125 ms/op
# Warmup Iteration   2: 4.444 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 3.571 ±(99.9%) 0.011 ms/op
Iteration   1: 3.369 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.241 ms/op
                 createUser·p0.50:   3.314 ms/op
                 createUser·p0.90:   3.523 ms/op
                 createUser·p0.95:   3.899 ms/op
                 createUser·p0.99:   5.980 ms/op
                 createUser·p0.999:  17.203 ms/op
                 createUser·p0.9999: 22.332 ms/op
                 createUser·p1.00:   22.577 ms/op

Iteration   2: 3.433 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.546 ms/op
                 createUser·p0.50:   3.277 ms/op
                 createUser·p0.90:   3.920 ms/op
                 createUser·p0.95:   4.202 ms/op
                 createUser·p0.99:   5.972 ms/op
                 createUser·p0.999:  18.082 ms/op
                 createUser·p0.9999: 23.583 ms/op
                 createUser·p1.00:   24.379 ms/op

Iteration   3: 3.630 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.120 ms/op
                 createUser·p0.50:   3.465 ms/op
                 createUser·p0.90:   4.260 ms/op
                 createUser·p0.95:   4.776 ms/op
                 createUser·p0.99:   6.349 ms/op
                 createUser·p0.999:  16.581 ms/op
                 createUser·p0.9999: 23.790 ms/op
                 createUser·p1.00:   25.166 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 276088
  mean =      3.474 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7265 
    [ 2.500,  5.000) = 261657 
    [ 5.000,  7.500) = 6033 
    [ 7.500, 10.000) = 723 
    [10.000, 12.500) = 71 
    [12.500, 15.000) = 51 
    [15.000, 17.500) = 30 
    [17.500, 20.000) = 132 
    [20.000, 22.500) = 76 
    [22.500, 25.000) = 48 
    [25.000, 27.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      1.120 ms/op
     p(50.0000) =      3.351 ms/op
     p(90.0000) =      3.973 ms/op
     p(95.0000) =      4.325 ms/op
     p(99.0000) =      6.078 ms/op
     p(99.9000) =     16.763 ms/op
     p(99.9900) =     23.462 ms/op
     p(99.9990) =     24.885 ms/op
     p(99.9999) =     25.166 ms/op
    p(100.0000) =     25.166 ms/op


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
# Warmup Iteration   1: 8.992 ±(99.9%) 0.106 ms/op
# Warmup Iteration   2: 3.692 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.426 ±(99.9%) 0.008 ms/op
Iteration   1: 3.442 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.427 ms/op
                 existUser·p0.50:   3.322 ms/op
                 existUser·p0.90:   3.801 ms/op
                 existUser·p0.95:   4.129 ms/op
                 existUser·p0.99:   5.808 ms/op
                 existUser·p0.999:  19.922 ms/op
                 existUser·p0.9999: 24.219 ms/op
                 existUser·p1.00:   24.969 ms/op

Iteration   2: 3.409 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.186 ms/op
                 existUser·p0.50:   3.277 ms/op
                 existUser·p0.90:   3.748 ms/op
                 existUser·p0.95:   4.051 ms/op
                 existUser·p0.99:   6.423 ms/op
                 existUser·p0.999:  22.768 ms/op
                 existUser·p0.9999: 25.698 ms/op
                 existUser·p1.00:   27.066 ms/op

Iteration   3: 3.462 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.772 ms/op
                 existUser·p0.50:   3.318 ms/op
                 existUser·p0.90:   3.920 ms/op
                 existUser·p0.95:   4.399 ms/op
                 existUser·p0.99:   6.545 ms/op
                 existUser·p0.999:  9.988 ms/op
                 existUser·p0.9999: 24.423 ms/op
                 existUser·p1.00:   25.297 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 279128
  mean =      3.437 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4370 
    [ 2.500,  5.000) = 267623 
    [ 5.000,  7.500) = 6161 
    [ 7.500, 10.000) = 566 
    [10.000, 12.500) = 137 
    [12.500, 15.000) = 15 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 7 
    [20.000, 22.500) = 66 
    [22.500, 25.000) = 156 
    [25.000, 27.500) = 27 

  Percentiles, ms/op:
      p(0.0000) =      1.186 ms/op
     p(50.0000) =      3.305 ms/op
     p(90.0000) =      3.822 ms/op
     p(95.0000) =      4.186 ms/op
     p(99.0000) =      6.185 ms/op
     p(99.9000) =     12.292 ms/op
     p(99.9900) =     24.972 ms/op
     p(99.9990) =     25.921 ms/op
     p(99.9999) =     27.066 ms/op
    p(100.0000) =     27.066 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 10.456 ±(99.9%) 0.136 ms/op
# Warmup Iteration   2: 3.955 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.699 ±(99.9%) 0.013 ms/op
Iteration   1: 3.461 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.466 ms/op
                 getUser·p0.50:   3.318 ms/op
                 getUser·p0.90:   3.805 ms/op
                 getUser·p0.95:   4.063 ms/op
                 getUser·p0.99:   6.405 ms/op
                 getUser·p0.999:  18.514 ms/op
                 getUser·p0.9999: 28.401 ms/op
                 getUser·p1.00:   29.524 ms/op

Iteration   2: 3.502 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.333 ms/op
                 getUser·p0.50:   3.371 ms/op
                 getUser·p0.90:   3.908 ms/op
                 getUser·p0.95:   4.219 ms/op
                 getUser·p0.99:   6.218 ms/op
                 getUser·p0.999:  23.953 ms/op
                 getUser·p0.9999: 28.190 ms/op
                 getUser·p1.00:   28.934 ms/op

Iteration   3: 3.454 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.358 ms/op
                 getUser·p0.50:   3.326 ms/op
                 getUser·p0.90:   3.793 ms/op
                 getUser·p0.95:   3.990 ms/op
                 getUser·p0.99:   5.865 ms/op
                 getUser·p0.999:  21.561 ms/op
                 getUser·p0.9999: 24.181 ms/op
                 getUser·p1.00:   25.362 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 276554
  mean =      3.472 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2640 
    [ 2.500,  5.000) = 267585 
    [ 5.000,  7.500) = 5127 
    [ 7.500, 10.000) = 707 
    [10.000, 12.500) = 113 
    [12.500, 15.000) = 38 
    [15.000, 17.500) = 30 
    [17.500, 20.000) = 58 
    [20.000, 22.500) = 38 
    [22.500, 25.000) = 115 
    [25.000, 27.500) = 59 

  Percentiles, ms/op:
      p(0.0000) =      1.333 ms/op
     p(50.0000) =      3.338 ms/op
     p(90.0000) =      3.834 ms/op
     p(95.0000) =      4.096 ms/op
     p(99.0000) =      6.201 ms/op
     p(99.9000) =     18.776 ms/op
     p(99.9900) =     28.082 ms/op
     p(99.9990) =     29.190 ms/op
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
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 12.964 ±(99.9%) 0.194 ms/op
# Warmup Iteration   2: 4.730 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 4.335 ±(99.9%) 0.016 ms/op
Iteration   1: 4.077 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   2.122 ms/op
                 listUser·p0.50:   3.973 ms/op
                 listUser·p0.90:   4.383 ms/op
                 listUser·p0.95:   4.743 ms/op
                 listUser·p0.99:   7.422 ms/op
                 listUser·p0.999:  21.837 ms/op
                 listUser·p0.9999: 23.663 ms/op
                 listUser·p1.00:   24.216 ms/op

Iteration   2: 4.169 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   2.548 ms/op
                 listUser·p0.50:   3.965 ms/op
                 listUser·p0.90:   4.571 ms/op
                 listUser·p0.95:   5.054 ms/op
                 listUser·p0.99:   8.200 ms/op
                 listUser·p0.999:  14.893 ms/op
                 listUser·p0.9999: 17.990 ms/op
                 listUser·p1.00:   18.055 ms/op

Iteration   3: 4.252 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.425 ms/op
                 listUser·p0.50:   4.076 ms/op
                 listUser·p0.90:   4.645 ms/op
                 listUser·p0.95:   5.087 ms/op
                 listUser·p0.99:   8.307 ms/op
                 listUser·p0.999:  16.171 ms/op
                 listUser·p0.9999: 17.496 ms/op
                 listUser·p1.00:   17.727 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 230426
  mean =      4.164 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12 
    [ 2.500,  5.000) = 219285 
    [ 5.000,  7.500) = 8081 
    [ 7.500, 10.000) = 1989 
    [10.000, 12.500) = 412 
    [12.500, 15.000) = 291 
    [15.000, 17.500) = 162 
    [17.500, 20.000) = 57 
    [20.000, 22.500) = 91 
    [22.500, 25.000) = 46 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.122 ms/op
     p(50.0000) =      3.990 ms/op
     p(90.0000) =      4.555 ms/op
     p(95.0000) =      4.973 ms/op
     p(99.0000) =      8.036 ms/op
     p(99.9000) =     17.072 ms/op
     p(99.9900) =     23.101 ms/op
     p(99.9990) =     23.979 ms/op
     p(99.9999) =     24.216 ms/op
    p(100.0000) =     24.216 ms/op


# Run complete. Total time: 00:13:13

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   8.887 ± 3.278  ops/ms
ClientPb.existUser                       thrpt       3   8.966 ± 1.828  ops/ms
ClientPb.getUser                         thrpt       3   9.002 ± 8.508  ops/ms
ClientPb.listUser                        thrpt       3   7.772 ± 0.493  ops/ms
ClientPb.createUser                       avgt       3   3.581 ± 1.665   ms/op
ClientPb.existUser                        avgt       3   3.548 ± 1.407   ms/op
ClientPb.getUser                          avgt       3   3.626 ± 2.526   ms/op
ClientPb.listUser                         avgt       3   4.086 ± 0.647   ms/op
ClientPb.createUser                     sample  276088   3.474 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.120           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.351           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.973           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.325           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.078           ms/op
ClientPb.createUser:createUser·p0.999   sample          16.763           ms/op
ClientPb.createUser:createUser·p0.9999  sample          23.462           ms/op
ClientPb.createUser:createUser·p1.00    sample          25.166           ms/op
ClientPb.existUser                      sample  279128   3.437 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.186           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.305           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.822           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.186           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.185           ms/op
ClientPb.existUser:existUser·p0.999     sample          12.292           ms/op
ClientPb.existUser:existUser·p0.9999    sample          24.972           ms/op
ClientPb.existUser:existUser·p1.00      sample          27.066           ms/op
ClientPb.getUser                        sample  276554   3.472 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.333           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.338           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.834           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.096           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.201           ms/op
ClientPb.getUser:getUser·p0.999         sample          18.776           ms/op
ClientPb.getUser:getUser·p0.9999        sample          28.082           ms/op
ClientPb.getUser:getUser·p1.00          sample          29.524           ms/op
ClientPb.listUser                       sample  230426   4.164 ± 0.007   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.122           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.990           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.555           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.973           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.036           ms/op
ClientPb.listUser:listUser·p0.999       sample          17.072           ms/op
ClientPb.listUser:listUser·p0.9999      sample          23.101           ms/op
ClientPb.listUser:listUser·p1.00        sample          24.216           ms/op
