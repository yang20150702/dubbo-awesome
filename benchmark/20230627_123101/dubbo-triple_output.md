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
# Warmup Iteration   1: 1.970 ops/ms
# Warmup Iteration   2: 4.785 ops/ms
# Warmup Iteration   3: 8.947 ops/ms
Iteration   1: 8.965 ops/ms
Iteration   2: 9.402 ops/ms
Iteration   3: 9.440 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.269 ±(99.9%) 4.817 ops/ms [Average]
  (min, avg, max) = (8.965, 9.269, 9.440), stdev = 0.264
  CI (99.9%): [4.452, 14.086] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:08
# Fork: 1 of 1
# Warmup Iteration   1: 2.772 ops/ms
# Warmup Iteration   2: 8.063 ops/ms
# Warmup Iteration   3: 9.436 ops/ms
Iteration   1: 9.671 ops/ms
Iteration   2: 9.606 ops/ms
Iteration   3: 9.967 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.748 ±(99.9%) 3.517 ops/ms [Average]
  (min, avg, max) = (9.606, 9.748, 9.967), stdev = 0.193
  CI (99.9%): [6.231, 13.265] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:01
# Fork: 1 of 1
# Warmup Iteration   1: 2.865 ops/ms
# Warmup Iteration   2: 8.390 ops/ms
# Warmup Iteration   3: 8.713 ops/ms
Iteration   1: 9.248 ops/ms
Iteration   2: 9.367 ops/ms
Iteration   3: 9.123 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.246 ±(99.9%) 2.227 ops/ms [Average]
  (min, avg, max) = (9.123, 9.246, 9.367), stdev = 0.122
  CI (99.9%): [7.019, 11.473] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 2.750 ops/ms
# Warmup Iteration   2: 7.416 ops/ms
# Warmup Iteration   3: 7.735 ops/ms
Iteration   1: 7.931 ops/ms
Iteration   2: 8.021 ops/ms
Iteration   3: 8.000 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.984 ±(99.9%) 0.857 ops/ms [Average]
  (min, avg, max) = (7.931, 7.984, 8.021), stdev = 0.047
  CI (99.9%): [7.127, 8.842] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:45
# Fork: 1 of 1
# Warmup Iteration   1: 11.559 ±(99.9%) 0.067 ms/op
# Warmup Iteration   2: 3.737 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.635 ±(99.9%) 0.006 ms/op
Iteration   1: 3.469 ±(99.9%) 0.007 ms/op
Iteration   2: 3.454 ±(99.9%) 0.004 ms/op
Iteration   3: 3.430 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.451 ±(99.9%) 0.362 ms/op [Average]
  (min, avg, max) = (3.430, 3.451, 3.469), stdev = 0.020
  CI (99.9%): [3.090, 3.813] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 10.330 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.591 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.476 ±(99.9%) 0.006 ms/op
Iteration   1: 3.415 ±(99.9%) 0.004 ms/op
Iteration   2: 3.212 ±(99.9%) 0.012 ms/op
Iteration   3: 3.277 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.301 ±(99.9%) 1.886 ms/op [Average]
  (min, avg, max) = (3.212, 3.301, 3.415), stdev = 0.103
  CI (99.9%): [1.415, 5.188] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 10.500 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 3.904 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.553 ±(99.9%) 0.008 ms/op
Iteration   1: 3.472 ±(99.9%) 0.007 ms/op
Iteration   2: 3.354 ±(99.9%) 0.008 ms/op
Iteration   3: 3.384 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.403 ±(99.9%) 1.112 ms/op [Average]
  (min, avg, max) = (3.354, 3.403, 3.472), stdev = 0.061
  CI (99.9%): [2.291, 4.515] (assumes normal distribution)


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
# Warmup Iteration   1: 11.277 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 4.599 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.154 ±(99.9%) 0.006 ms/op
Iteration   1: 4.003 ±(99.9%) 0.009 ms/op
Iteration   2: 3.989 ±(99.9%) 0.013 ms/op
Iteration   3: 4.035 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.009 ±(99.9%) 0.433 ms/op [Average]
  (min, avg, max) = (3.989, 4.009, 4.035), stdev = 0.024
  CI (99.9%): [3.577, 4.442] (assumes normal distribution)


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
# Warmup Iteration   1: 10.839 ±(99.9%) 0.134 ms/op
# Warmup Iteration   2: 4.158 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 3.741 ±(99.9%) 0.013 ms/op
Iteration   1: 3.602 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.661 ms/op
                 createUser·p0.50:   3.404 ms/op
                 createUser·p0.90:   4.137 ms/op
                 createUser·p0.95:   4.907 ms/op
                 createUser·p0.99:   7.438 ms/op
                 createUser·p0.999:  19.661 ms/op
                 createUser·p0.9999: 23.991 ms/op
                 createUser·p1.00:   24.478 ms/op

Iteration   2: 3.551 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.694 ms/op
                 createUser·p0.50:   3.338 ms/op
                 createUser·p0.90:   4.243 ms/op
                 createUser·p0.95:   4.833 ms/op
                 createUser·p0.99:   6.504 ms/op
                 createUser·p0.999:  23.228 ms/op
                 createUser·p0.9999: 25.460 ms/op
                 createUser·p1.00:   26.771 ms/op

Iteration   3: 3.501 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.606 ms/op
                 createUser·p0.50:   3.416 ms/op
                 createUser·p0.90:   3.944 ms/op
                 createUser·p0.95:   4.211 ms/op
                 createUser·p0.99:   5.792 ms/op
                 createUser·p0.999:  23.418 ms/op
                 createUser·p0.9999: 36.683 ms/op
                 createUser·p1.00:   38.142 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 270113
  mean =      3.551 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5421 
    [ 2.500,  5.000) = 256067 
    [ 5.000,  7.500) = 6910 
    [ 7.500, 10.000) = 1156 
    [10.000, 12.500) = 226 
    [12.500, 15.000) = 12 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 16 
    [20.000, 22.500) = 66 
    [22.500, 25.000) = 144 
    [25.000, 27.500) = 42 
    [27.500, 30.000) = 21 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 7 
    [35.000, 37.500) = 22 

  Percentiles, ms/op:
      p(0.0000) =      1.606 ms/op
     p(50.0000) =      3.383 ms/op
     p(90.0000) =      4.092 ms/op
     p(95.0000) =      4.653 ms/op
     p(99.0000) =      6.939 ms/op
     p(99.9000) =     21.951 ms/op
     p(99.9900) =     34.995 ms/op
     p(99.9990) =     37.899 ms/op
     p(99.9999) =     38.142 ms/op
    p(100.0000) =     38.142 ms/op


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
# Warmup Iteration   1: 8.503 ±(99.9%) 0.107 ms/op
# Warmup Iteration   2: 3.761 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.314 ±(99.9%) 0.008 ms/op
Iteration   1: 3.405 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.544 ms/op
                 existUser·p0.50:   3.383 ms/op
                 existUser·p0.90:   3.662 ms/op
                 existUser·p0.95:   4.076 ms/op
                 existUser·p0.99:   5.718 ms/op
                 existUser·p0.999:  19.592 ms/op
                 existUser·p0.9999: 23.173 ms/op
                 existUser·p1.00:   24.478 ms/op

Iteration   2: 3.468 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.245 ms/op
                 existUser·p0.50:   3.379 ms/op
                 existUser·p0.90:   3.932 ms/op
                 existUser·p0.95:   4.383 ms/op
                 existUser·p0.99:   6.267 ms/op
                 existUser·p0.999:  13.189 ms/op
                 existUser·p0.9999: 30.500 ms/op
                 existUser·p1.00:   30.867 ms/op

Iteration   3: 3.464 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.636 ms/op
                 existUser·p0.50:   3.330 ms/op
                 existUser·p0.90:   3.895 ms/op
                 existUser·p0.95:   4.325 ms/op
                 existUser·p0.99:   6.265 ms/op
                 existUser·p0.999:  22.698 ms/op
                 existUser·p0.9999: 29.811 ms/op
                 existUser·p1.00:   30.638 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 278635
  mean =      3.446 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15184 
    [ 2.500,  5.000) = 255585 
    [ 5.000,  7.500) = 6742 
    [ 7.500, 10.000) = 632 
    [10.000, 12.500) = 174 
    [12.500, 15.000) = 61 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 11 
    [20.000, 22.500) = 90 
    [22.500, 25.000) = 58 
    [25.000, 27.500) = 12 
    [27.500, 30.000) = 64 
    [30.000, 32.500) = 21 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.544 ms/op
     p(50.0000) =      3.371 ms/op
     p(90.0000) =      3.854 ms/op
     p(95.0000) =      4.243 ms/op
     p(99.0000) =      6.078 ms/op
     p(99.9000) =     14.844 ms/op
     p(99.9900) =     29.852 ms/op
     p(99.9990) =     30.757 ms/op
     p(99.9999) =     30.867 ms/op
    p(100.0000) =     30.867 ms/op


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
# Warmup Iteration   1: 9.238 ±(99.9%) 0.117 ms/op
# Warmup Iteration   2: 3.954 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.649 ±(99.9%) 0.012 ms/op
Iteration   1: 3.413 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.307 ms/op
                 getUser·p0.50:   3.326 ms/op
                 getUser·p0.90:   3.707 ms/op
                 getUser·p0.95:   3.903 ms/op
                 getUser·p0.99:   5.898 ms/op
                 getUser·p0.999:  21.156 ms/op
                 getUser·p0.9999: 23.438 ms/op
                 getUser·p1.00:   24.084 ms/op

Iteration   2: 3.584 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.630 ms/op
                 getUser·p0.50:   3.400 ms/op
                 getUser·p0.90:   3.998 ms/op
                 getUser·p0.95:   4.923 ms/op
                 getUser·p0.99:   6.816 ms/op
                 getUser·p0.999:  23.691 ms/op
                 getUser·p0.9999: 29.527 ms/op
                 getUser·p1.00:   29.622 ms/op

Iteration   3: 3.589 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.491 ms/op
                 getUser·p0.50:   3.461 ms/op
                 getUser·p0.90:   3.957 ms/op
                 getUser·p0.95:   4.260 ms/op
                 getUser·p0.99:   6.741 ms/op
                 getUser·p0.999:  18.153 ms/op
                 getUser·p0.9999: 31.818 ms/op
                 getUser·p1.00:   33.161 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 271962
  mean =      3.527 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1751 
    [ 2.500,  5.000) = 261340 
    [ 5.000,  7.500) = 7424 
    [ 7.500, 10.000) = 1017 
    [10.000, 12.500) = 130 
    [12.500, 15.000) = 12 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 23 
    [20.000, 22.500) = 71 
    [22.500, 25.000) = 77 
    [25.000, 27.500) = 49 
    [27.500, 30.000) = 40 
    [30.000, 32.500) = 26 
    [32.500, 35.000) = 2 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.307 ms/op
     p(50.0000) =      3.383 ms/op
     p(90.0000) =      3.891 ms/op
     p(95.0000) =      4.235 ms/op
     p(99.0000) =      6.426 ms/op
     p(99.9000) =     19.533 ms/op
     p(99.9900) =     30.697 ms/op
     p(99.9990) =     32.469 ms/op
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
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 11.418 ±(99.9%) 0.161 ms/op
# Warmup Iteration   2: 4.478 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.232 ±(99.9%) 0.015 ms/op
Iteration   1: 4.174 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.413 ms/op
                 listUser·p0.50:   4.043 ms/op
                 listUser·p0.90:   4.506 ms/op
                 listUser·p0.95:   4.801 ms/op
                 listUser·p0.99:   7.684 ms/op
                 listUser·p0.999:  19.235 ms/op
                 listUser·p0.9999: 31.238 ms/op
                 listUser·p1.00:   32.244 ms/op

Iteration   2: 4.033 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.617 ms/op
                 listUser·p0.50:   3.879 ms/op
                 listUser·p0.90:   4.555 ms/op
                 listUser·p0.95:   4.907 ms/op
                 listUser·p0.99:   7.905 ms/op
                 listUser·p0.999:  14.562 ms/op
                 listUser·p0.9999: 16.467 ms/op
                 listUser·p1.00:   17.891 ms/op

Iteration   3: 4.138 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.175 ms/op
                 listUser·p0.50:   4.026 ms/op
                 listUser·p0.90:   4.743 ms/op
                 listUser·p0.95:   5.095 ms/op
                 listUser·p0.99:   7.324 ms/op
                 listUser·p0.999:  14.664 ms/op
                 listUser·p0.9999: 17.156 ms/op
                 listUser·p1.00:   17.334 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 233180
  mean =      4.114 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 38 
    [ 2.500,  5.000) = 222066 
    [ 5.000,  7.500) = 8752 
    [ 7.500, 10.000) = 1640 
    [10.000, 12.500) = 279 
    [12.500, 15.000) = 185 
    [15.000, 17.500) = 120 
    [17.500, 20.000) = 30 
    [20.000, 22.500) = 6 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 23 
    [27.500, 30.000) = 23 
    [30.000, 32.500) = 18 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.413 ms/op
     p(50.0000) =      3.973 ms/op
     p(90.0000) =      4.596 ms/op
     p(95.0000) =      4.964 ms/op
     p(99.0000) =      7.496 ms/op
     p(99.9000) =     14.877 ms/op
     p(99.9900) =     29.536 ms/op
     p(99.9990) =     31.818 ms/op
     p(99.9999) =     32.244 ms/op
    p(100.0000) =     32.244 ms/op


# Run complete. Total time: 00:13:12

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.269 ± 4.817  ops/ms
ClientPb.existUser                       thrpt       3   9.748 ± 3.517  ops/ms
ClientPb.getUser                         thrpt       3   9.246 ± 2.227  ops/ms
ClientPb.listUser                        thrpt       3   7.984 ± 0.857  ops/ms
ClientPb.createUser                       avgt       3   3.451 ± 0.362   ms/op
ClientPb.existUser                        avgt       3   3.301 ± 1.886   ms/op
ClientPb.getUser                          avgt       3   3.403 ± 1.112   ms/op
ClientPb.listUser                         avgt       3   4.009 ± 0.433   ms/op
ClientPb.createUser                     sample  270113   3.551 ± 0.007   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.606           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.383           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.092           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.653           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.939           ms/op
ClientPb.createUser:createUser·p0.999   sample          21.951           ms/op
ClientPb.createUser:createUser·p0.9999  sample          34.995           ms/op
ClientPb.createUser:createUser·p1.00    sample          38.142           ms/op
ClientPb.existUser                      sample  278635   3.446 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.544           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.371           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.854           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.243           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.078           ms/op
ClientPb.existUser:existUser·p0.999     sample          14.844           ms/op
ClientPb.existUser:existUser·p0.9999    sample          29.852           ms/op
ClientPb.existUser:existUser·p1.00      sample          30.867           ms/op
ClientPb.getUser                        sample  271962   3.527 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.307           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.383           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.891           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.235           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.426           ms/op
ClientPb.getUser:getUser·p0.999         sample          19.533           ms/op
ClientPb.getUser:getUser·p0.9999        sample          30.697           ms/op
ClientPb.getUser:getUser·p1.00          sample          33.161           ms/op
ClientPb.listUser                       sample  233180   4.114 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.413           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.973           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.596           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.964           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.496           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.877           ms/op
ClientPb.listUser:listUser·p0.9999      sample          29.536           ms/op
ClientPb.listUser:listUser·p1.00        sample          32.244           ms/op
