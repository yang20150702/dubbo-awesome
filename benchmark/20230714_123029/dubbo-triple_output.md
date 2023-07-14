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
# Warmup Iteration   1: 2.226 ops/ms
# Warmup Iteration   2: 5.684 ops/ms
# Warmup Iteration   3: 8.747 ops/ms
Iteration   1: 9.331 ops/ms
Iteration   2: 9.260 ops/ms
Iteration   3: 9.117 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.236 ±(99.9%) 1.987 ops/ms [Average]
  (min, avg, max) = (9.117, 9.236, 9.331), stdev = 0.109
  CI (99.9%): [7.249, 11.224] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 3.370 ops/ms
# Warmup Iteration   2: 8.947 ops/ms
# Warmup Iteration   3: 9.593 ops/ms
Iteration   1: 9.733 ops/ms
Iteration   2: 9.485 ops/ms
Iteration   3: 9.825 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.681 ±(99.9%) 3.211 ops/ms [Average]
  (min, avg, max) = (9.485, 9.681, 9.825), stdev = 0.176
  CI (99.9%): [6.471, 12.892] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 2.927 ops/ms
# Warmup Iteration   2: 8.177 ops/ms
# Warmup Iteration   3: 9.292 ops/ms
Iteration   1: 9.311 ops/ms
Iteration   2: 9.299 ops/ms
Iteration   3: 9.418 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.342 ±(99.9%) 1.191 ops/ms [Average]
  (min, avg, max) = (9.299, 9.342, 9.418), stdev = 0.065
  CI (99.9%): [8.151, 10.534] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:48
# Fork: 1 of 1
# Warmup Iteration   1: 2.491 ops/ms
# Warmup Iteration   2: 7.037 ops/ms
# Warmup Iteration   3: 8.001 ops/ms
Iteration   1: 7.794 ops/ms
Iteration   2: 8.037 ops/ms
Iteration   3: 7.977 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.936 ±(99.9%) 2.306 ops/ms [Average]
  (min, avg, max) = (7.794, 7.936, 8.037), stdev = 0.126
  CI (99.9%): [5.630, 10.242] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:43
# Fork: 1 of 1
# Warmup Iteration   1: 10.561 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 3.947 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.564 ±(99.9%) 0.007 ms/op
Iteration   1: 3.488 ±(99.9%) 0.005 ms/op
Iteration   2: 3.317 ±(99.9%) 0.010 ms/op
Iteration   3: 3.513 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.439 ±(99.9%) 1.948 ms/op [Average]
  (min, avg, max) = (3.317, 3.439, 3.513), stdev = 0.107
  CI (99.9%): [1.491, 5.388] (assumes normal distribution)


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
# Warmup Iteration   1: 9.164 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.670 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.463 ±(99.9%) 0.007 ms/op
Iteration   1: 3.311 ±(99.9%) 0.005 ms/op
Iteration   2: 3.230 ±(99.9%) 0.010 ms/op
Iteration   3: 3.282 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.274 ±(99.9%) 0.753 ms/op [Average]
  (min, avg, max) = (3.230, 3.274, 3.311), stdev = 0.041
  CI (99.9%): [2.522, 4.027] (assumes normal distribution)


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
# Warmup Iteration   1: 8.764 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 3.670 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.609 ±(99.9%) 0.004 ms/op
Iteration   1: 3.579 ±(99.9%) 0.005 ms/op
Iteration   2: 3.411 ±(99.9%) 0.009 ms/op
Iteration   3: 3.398 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.463 ±(99.9%) 1.843 ms/op [Average]
  (min, avg, max) = (3.398, 3.463, 3.579), stdev = 0.101
  CI (99.9%): [1.620, 5.305] (assumes normal distribution)


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
# Warmup Iteration   1: 10.809 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 4.363 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.987 ±(99.9%) 0.016 ms/op
Iteration   1: 3.933 ±(99.9%) 0.013 ms/op
Iteration   2: 3.868 ±(99.9%) 0.016 ms/op
Iteration   3: 3.839 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.880 ±(99.9%) 0.871 ms/op [Average]
  (min, avg, max) = (3.839, 3.880, 3.933), stdev = 0.048
  CI (99.9%): [3.009, 4.751] (assumes normal distribution)


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
# Warmup Iteration   1: 9.355 ±(99.9%) 0.123 ms/op
# Warmup Iteration   2: 4.087 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.527 ±(99.9%) 0.011 ms/op
Iteration   1: 3.343 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.858 ms/op
                 createUser·p0.50:   3.334 ms/op
                 createUser·p0.90:   3.588 ms/op
                 createUser·p0.95:   3.895 ms/op
                 createUser·p0.99:   5.628 ms/op
                 createUser·p0.999:  19.923 ms/op
                 createUser·p0.9999: 23.378 ms/op
                 createUser·p1.00:   24.150 ms/op

Iteration   2: 3.335 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.671 ms/op
                 createUser·p0.50:   3.199 ms/op
                 createUser·p0.90:   3.731 ms/op
                 createUser·p0.95:   4.030 ms/op
                 createUser·p0.99:   5.652 ms/op
                 createUser·p0.999:  21.926 ms/op
                 createUser·p0.9999: 29.701 ms/op
                 createUser·p1.00:   30.900 ms/op

Iteration   3: 3.455 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.569 ms/op
                 createUser·p0.50:   3.342 ms/op
                 createUser·p0.90:   3.953 ms/op
                 createUser·p0.95:   4.284 ms/op
                 createUser·p0.99:   5.800 ms/op
                 createUser·p0.999:  15.955 ms/op
                 createUser·p0.9999: 28.082 ms/op
                 createUser·p1.00:   28.606 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 284204
  mean =      3.377 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12471 
    [ 2.500,  5.000) = 266276 
    [ 5.000,  7.500) = 4593 
    [ 7.500, 10.000) = 425 
    [10.000, 12.500) = 120 
    [12.500, 15.000) = 31 
    [15.000, 17.500) = 16 
    [17.500, 20.000) = 18 
    [20.000, 22.500) = 91 
    [22.500, 25.000) = 90 
    [25.000, 27.500) = 13 
    [27.500, 30.000) = 54 
    [30.000, 32.500) = 6 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.858 ms/op
     p(50.0000) =      3.310 ms/op
     p(90.0000) =      3.781 ms/op
     p(95.0000) =      4.100 ms/op
     p(99.0000) =      5.750 ms/op
     p(99.9000) =     15.968 ms/op
     p(99.9900) =     28.246 ms/op
     p(99.9990) =     30.840 ms/op
     p(99.9999) =     30.900 ms/op
    p(100.0000) =     30.900 ms/op


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
# Warmup Iteration   1: 8.976 ±(99.9%) 0.117 ms/op
# Warmup Iteration   2: 3.776 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.464 ±(99.9%) 0.009 ms/op
Iteration   1: 3.331 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.810 ms/op
                 existUser·p0.50:   3.219 ms/op
                 existUser·p0.90:   3.580 ms/op
                 existUser·p0.95:   3.850 ms/op
                 existUser·p0.99:   6.140 ms/op
                 existUser·p0.999:  15.016 ms/op
                 existUser·p0.9999: 19.195 ms/op
                 existUser·p1.00:   19.956 ms/op

Iteration   2: 3.389 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.767 ms/op
                 existUser·p0.50:   3.359 ms/op
                 existUser·p0.90:   3.662 ms/op
                 existUser·p0.95:   3.916 ms/op
                 existUser·p0.99:   5.931 ms/op
                 existUser·p0.999:  16.752 ms/op
                 existUser·p0.9999: 31.803 ms/op
                 existUser·p1.00:   33.161 ms/op

Iteration   3: 3.461 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.405 ms/op
                 existUser·p0.50:   3.396 ms/op
                 existUser·p0.90:   3.826 ms/op
                 existUser·p0.95:   4.121 ms/op
                 existUser·p0.99:   5.767 ms/op
                 existUser·p0.999:  16.908 ms/op
                 existUser·p0.9999: 22.012 ms/op
                 existUser·p1.00:   22.479 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 282975
  mean =      3.393 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11592 
    [ 2.500,  5.000) = 265931 
    [ 5.000,  7.500) = 4288 
    [ 7.500, 10.000) = 750 
    [10.000, 12.500) = 91 
    [12.500, 15.000) = 21 
    [15.000, 17.500) = 99 
    [17.500, 20.000) = 119 
    [20.000, 22.500) = 52 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 8 
    [30.000, 32.500) = 19 
    [32.500, 35.000) = 5 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.405 ms/op
     p(50.0000) =      3.334 ms/op
     p(90.0000) =      3.711 ms/op
     p(95.0000) =      3.977 ms/op
     p(99.0000) =      5.988 ms/op
     p(99.9000) =     15.729 ms/op
     p(99.9900) =     29.597 ms/op
     p(99.9990) =     33.161 ms/op
     p(99.9999) =     33.161 ms/op
    p(100.0000) =     33.161 ms/op


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
# Warmup Iteration   1: 9.355 ±(99.9%) 0.133 ms/op
# Warmup Iteration   2: 3.748 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.434 ±(99.9%) 0.008 ms/op
Iteration   1: 3.407 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.466 ms/op
                 getUser·p0.50:   3.236 ms/op
                 getUser·p0.90:   3.760 ms/op
                 getUser·p0.95:   4.342 ms/op
                 getUser·p0.99:   6.463 ms/op
                 getUser·p0.999:  18.779 ms/op
                 getUser·p0.9999: 24.432 ms/op
                 getUser·p1.00:   24.707 ms/op

Iteration   2: 3.382 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.184 ms/op
                 getUser·p0.50:   3.236 ms/op
                 getUser·p0.90:   3.723 ms/op
                 getUser·p0.95:   3.908 ms/op
                 getUser·p0.99:   6.255 ms/op
                 getUser·p0.999:  20.412 ms/op
                 getUser·p0.9999: 32.801 ms/op
                 getUser·p1.00:   34.144 ms/op

Iteration   3: 3.545 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.563 ms/op
                 getUser·p0.50:   3.367 ms/op
                 getUser·p0.90:   4.166 ms/op
                 getUser·p0.95:   4.506 ms/op
                 getUser·p0.99:   5.956 ms/op
                 getUser·p0.999:  10.256 ms/op
                 getUser·p0.9999: 24.674 ms/op
                 getUser·p1.00:   27.984 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 278643
  mean =      3.443 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8075 
    [ 2.500,  5.000) = 261811 
    [ 5.000,  7.500) = 7447 
    [ 7.500, 10.000) = 927 
    [10.000, 12.500) = 67 
    [12.500, 15.000) = 28 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 18 
    [20.000, 22.500) = 59 
    [22.500, 25.000) = 139 
    [25.000, 27.500) = 7 
    [27.500, 30.000) = 1 
    [30.000, 32.500) = 12 
    [32.500, 35.000) = 20 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.184 ms/op
     p(50.0000) =      3.301 ms/op
     p(90.0000) =      3.936 ms/op
     p(95.0000) =      4.301 ms/op
     p(99.0000) =      6.250 ms/op
     p(99.9000) =     15.194 ms/op
     p(99.9900) =     31.897 ms/op
     p(99.9990) =     34.144 ms/op
     p(99.9999) =     34.144 ms/op
    p(100.0000) =     34.144 ms/op


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
# Warmup Iteration   1: 11.883 ±(99.9%) 0.151 ms/op
# Warmup Iteration   2: 4.560 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.133 ±(99.9%) 0.013 ms/op
Iteration   1: 4.110 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.552 ms/op
                 listUser·p0.50:   3.920 ms/op
                 listUser·p0.90:   4.522 ms/op
                 listUser·p0.95:   5.120 ms/op
                 listUser·p0.99:   7.741 ms/op
                 listUser·p0.999:  20.551 ms/op
                 listUser·p0.9999: 22.977 ms/op
                 listUser·p1.00:   24.347 ms/op

Iteration   2: 4.002 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.554 ms/op
                 listUser·p0.50:   3.805 ms/op
                 listUser·p0.90:   4.522 ms/op
                 listUser·p0.95:   4.948 ms/op
                 listUser·p0.99:   7.445 ms/op
                 listUser·p0.999:  15.962 ms/op
                 listUser·p0.9999: 22.610 ms/op
                 listUser·p1.00:   24.674 ms/op

Iteration   3: 3.943 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.191 ms/op
                 listUser·p0.50:   3.768 ms/op
                 listUser·p0.90:   4.407 ms/op
                 listUser·p0.95:   4.661 ms/op
                 listUser·p0.99:   7.291 ms/op
                 listUser·p0.999:  13.926 ms/op
                 listUser·p0.9999: 25.231 ms/op
                 listUser·p1.00:   26.706 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 238854
  mean =      4.017 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 52 
    [ 2.500,  5.000) = 228224 
    [ 5.000,  7.500) = 8219 
    [ 7.500, 10.000) = 1696 
    [10.000, 12.500) = 192 
    [12.500, 15.000) = 165 
    [15.000, 17.500) = 116 
    [17.500, 20.000) = 44 
    [20.000, 22.500) = 81 
    [22.500, 25.000) = 47 
    [25.000, 27.500) = 18 

  Percentiles, ms/op:
      p(0.0000) =      0.554 ms/op
     p(50.0000) =      3.822 ms/op
     p(90.0000) =      4.481 ms/op
     p(95.0000) =      4.891 ms/op
     p(99.0000) =      7.471 ms/op
     p(99.9000) =     16.105 ms/op
     p(99.9900) =     23.662 ms/op
     p(99.9990) =     25.461 ms/op
     p(99.9999) =     26.706 ms/op
    p(100.0000) =     26.706 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.236 ± 1.987  ops/ms
ClientPb.existUser                       thrpt       3   9.681 ± 3.211  ops/ms
ClientPb.getUser                         thrpt       3   9.342 ± 1.191  ops/ms
ClientPb.listUser                        thrpt       3   7.936 ± 2.306  ops/ms
ClientPb.createUser                       avgt       3   3.439 ± 1.948   ms/op
ClientPb.existUser                        avgt       3   3.274 ± 0.753   ms/op
ClientPb.getUser                          avgt       3   3.463 ± 1.843   ms/op
ClientPb.listUser                         avgt       3   3.880 ± 0.871   ms/op
ClientPb.createUser                     sample  284204   3.377 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.858           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.310           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.781           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.100           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.750           ms/op
ClientPb.createUser:createUser·p0.999   sample          15.968           ms/op
ClientPb.createUser:createUser·p0.9999  sample          28.246           ms/op
ClientPb.createUser:createUser·p1.00    sample          30.900           ms/op
ClientPb.existUser                      sample  282975   3.393 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.405           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.334           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.711           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.977           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.988           ms/op
ClientPb.existUser:existUser·p0.999     sample          15.729           ms/op
ClientPb.existUser:existUser·p0.9999    sample          29.597           ms/op
ClientPb.existUser:existUser·p1.00      sample          33.161           ms/op
ClientPb.getUser                        sample  278643   3.443 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.184           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.301           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.936           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.301           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.250           ms/op
ClientPb.getUser:getUser·p0.999         sample          15.194           ms/op
ClientPb.getUser:getUser·p0.9999        sample          31.897           ms/op
ClientPb.getUser:getUser·p1.00          sample          34.144           ms/op
ClientPb.listUser                       sample  238854   4.017 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.554           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.822           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.481           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.891           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.471           ms/op
ClientPb.listUser:listUser·p0.999       sample          16.105           ms/op
ClientPb.listUser:listUser·p0.9999      sample          23.662           ms/op
ClientPb.listUser:listUser·p1.00        sample          26.706           ms/op
