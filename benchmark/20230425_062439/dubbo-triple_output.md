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
# Warmup Iteration   1: 2.006 ops/ms
# Warmup Iteration   2: 5.377 ops/ms
# Warmup Iteration   3: 8.350 ops/ms
Iteration   1: 9.200 ops/ms
Iteration   2: 9.190 ops/ms
Iteration   3: 9.047 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.145 ±(99.9%) 1.557 ops/ms [Average]
  (min, avg, max) = (9.047, 9.145, 9.200), stdev = 0.085
  CI (99.9%): [7.589, 10.702] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:07
# Fork: 1 of 1
# Warmup Iteration   1: 2.740 ops/ms
# Warmup Iteration   2: 8.132 ops/ms
# Warmup Iteration   3: 9.618 ops/ms
Iteration   1: 9.695 ops/ms
Iteration   2: 9.648 ops/ms
Iteration   3: 9.675 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.673 ±(99.9%) 0.426 ops/ms [Average]
  (min, avg, max) = (9.648, 9.673, 9.695), stdev = 0.023
  CI (99.9%): [9.246, 10.099] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 2.703 ops/ms
# Warmup Iteration   2: 8.335 ops/ms
# Warmup Iteration   3: 9.333 ops/ms
Iteration   1: 9.599 ops/ms
Iteration   2: 9.684 ops/ms
Iteration   3: 9.428 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.571 ±(99.9%) 2.379 ops/ms [Average]
  (min, avg, max) = (9.428, 9.571, 9.684), stdev = 0.130
  CI (99.9%): [7.191, 11.950] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:49
# Fork: 1 of 1
# Warmup Iteration   1: 2.956 ops/ms
# Warmup Iteration   2: 7.255 ops/ms
# Warmup Iteration   3: 7.772 ops/ms
Iteration   1: 7.977 ops/ms
Iteration   2: 8.359 ops/ms
Iteration   3: 8.080 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.139 ±(99.9%) 3.606 ops/ms [Average]
  (min, avg, max) = (7.977, 8.139, 8.359), stdev = 0.198
  CI (99.9%): [4.533, 11.745] (assumes normal distribution)


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
# Warmup Iteration   1: 9.986 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 3.849 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.536 ±(99.9%) 0.003 ms/op
Iteration   1: 3.517 ±(99.9%) 0.005 ms/op
Iteration   2: 3.419 ±(99.9%) 0.008 ms/op
Iteration   3: 3.402 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.446 ±(99.9%) 1.135 ms/op [Average]
  (min, avg, max) = (3.402, 3.446, 3.517), stdev = 0.062
  CI (99.9%): [2.311, 4.580] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 9.662 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 3.657 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.443 ±(99.9%) 0.004 ms/op
Iteration   1: 3.341 ±(99.9%) 0.009 ms/op
Iteration   2: 3.201 ±(99.9%) 0.009 ms/op
Iteration   3: 3.273 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.272 ±(99.9%) 1.278 ms/op [Average]
  (min, avg, max) = (3.201, 3.272, 3.341), stdev = 0.070
  CI (99.9%): [1.994, 4.550] (assumes normal distribution)


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
# Warmup Iteration   1: 9.950 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 3.778 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.521 ±(99.9%) 0.005 ms/op
Iteration   1: 3.341 ±(99.9%) 0.008 ms/op
Iteration   2: 3.380 ±(99.9%) 0.004 ms/op
Iteration   3: 3.410 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.377 ±(99.9%) 0.634 ms/op [Average]
  (min, avg, max) = (3.341, 3.377, 3.410), stdev = 0.035
  CI (99.9%): [2.742, 4.011] (assumes normal distribution)


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
# Warmup Iteration   1: 9.985 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 4.584 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.121 ±(99.9%) 0.008 ms/op
Iteration   1: 3.925 ±(99.9%) 0.014 ms/op
Iteration   2: 3.888 ±(99.9%) 0.015 ms/op
Iteration   3: 4.065 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.959 ±(99.9%) 1.700 ms/op [Average]
  (min, avg, max) = (3.888, 3.959, 4.065), stdev = 0.093
  CI (99.9%): [2.260, 5.659] (assumes normal distribution)


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
# Warmup Iteration   1: 9.162 ±(99.9%) 0.119 ms/op
# Warmup Iteration   2: 3.928 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.422 ±(99.9%) 0.009 ms/op
Iteration   1: 3.433 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.186 ms/op
                 createUser·p0.50:   3.289 ms/op
                 createUser·p0.90:   3.928 ms/op
                 createUser·p0.95:   4.309 ms/op
                 createUser·p0.99:   5.877 ms/op
                 createUser·p0.999:  19.159 ms/op
                 createUser·p0.9999: 22.381 ms/op
                 createUser·p1.00:   22.774 ms/op

Iteration   2: 3.396 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.386 ms/op
                 createUser·p0.50:   3.289 ms/op
                 createUser·p0.90:   3.850 ms/op
                 createUser·p0.95:   4.067 ms/op
                 createUser·p0.99:   5.284 ms/op
                 createUser·p0.999:  23.717 ms/op
                 createUser·p0.9999: 34.707 ms/op
                 createUser·p1.00:   36.110 ms/op

Iteration   3: 3.352 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.192 ms/op
                 createUser·p0.50:   3.228 ms/op
                 createUser·p0.90:   3.736 ms/op
                 createUser·p0.95:   3.990 ms/op
                 createUser·p0.99:   5.726 ms/op
                 createUser·p0.999:  22.213 ms/op
                 createUser·p0.9999: 30.278 ms/op
                 createUser·p1.00:   30.933 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 282751
  mean =      3.393 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4579 
    [ 2.500,  5.000) = 273106 
    [ 5.000,  7.500) = 4180 
    [ 7.500, 10.000) = 490 
    [10.000, 12.500) = 70 
    [12.500, 15.000) = 6 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 42 
    [20.000, 22.500) = 81 
    [22.500, 25.000) = 82 
    [25.000, 27.500) = 36 
    [27.500, 30.000) = 27 
    [30.000, 32.500) = 20 
    [32.500, 35.000) = 28 
    [35.000, 37.500) = 4 

  Percentiles, ms/op:
      p(0.0000) =      1.186 ms/op
     p(50.0000) =      3.260 ms/op
     p(90.0000) =      3.838 ms/op
     p(95.0000) =      4.116 ms/op
     p(99.0000) =      5.669 ms/op
     p(99.9000) =     19.767 ms/op
     p(99.9900) =     33.781 ms/op
     p(99.9990) =     35.150 ms/op
     p(99.9999) =     36.110 ms/op
    p(100.0000) =     36.110 ms/op


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
# Warmup Iteration   1: 8.966 ±(99.9%) 0.111 ms/op
# Warmup Iteration   2: 3.716 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.393 ±(99.9%) 0.009 ms/op
Iteration   1: 3.407 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.536 ms/op
                 existUser·p0.50:   3.273 ms/op
                 existUser·p0.90:   3.924 ms/op
                 existUser·p0.95:   4.366 ms/op
                 existUser·p0.99:   5.595 ms/op
                 existUser·p0.999:  19.731 ms/op
                 existUser·p0.9999: 22.401 ms/op
                 existUser·p1.00:   23.855 ms/op

Iteration   2: 3.343 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.735 ms/op
                 existUser·p0.50:   3.256 ms/op
                 existUser·p0.90:   3.777 ms/op
                 existUser·p0.95:   4.121 ms/op
                 existUser·p0.99:   5.734 ms/op
                 existUser·p0.999:  22.196 ms/op
                 existUser·p0.9999: 30.909 ms/op
                 existUser·p1.00:   32.211 ms/op

Iteration   3: 3.287 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.231 ms/op
                 existUser·p0.50:   3.199 ms/op
                 existUser·p0.90:   3.527 ms/op
                 existUser·p0.95:   3.756 ms/op
                 existUser·p0.99:   5.677 ms/op
                 existUser·p0.999:  12.243 ms/op
                 existUser·p0.9999: 26.485 ms/op
                 existUser·p1.00:   27.361 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 286962
  mean =      3.345 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12808 
    [ 2.500,  5.000) = 267478 
    [ 5.000,  7.500) = 5833 
    [ 7.500, 10.000) = 457 
    [10.000, 12.500) = 74 
    [12.500, 15.000) = 24 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 16 
    [20.000, 22.500) = 107 
    [22.500, 25.000) = 69 
    [25.000, 27.500) = 64 
    [27.500, 30.000) = 9 
    [30.000, 32.500) = 23 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.735 ms/op
     p(50.0000) =      3.244 ms/op
     p(90.0000) =      3.740 ms/op
     p(95.0000) =      4.137 ms/op
     p(99.0000) =      5.669 ms/op
     p(99.9000) =     19.340 ms/op
     p(99.9900) =     29.279 ms/op
     p(99.9990) =     32.019 ms/op
     p(99.9999) =     32.211 ms/op
    p(100.0000) =     32.211 ms/op


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
# Warmup Iteration   1: 10.745 ±(99.9%) 0.126 ms/op
# Warmup Iteration   2: 3.849 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.720 ±(99.9%) 0.013 ms/op
Iteration   1: 3.666 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.710 ms/op
                 getUser·p0.50:   3.482 ms/op
                 getUser·p0.90:   4.194 ms/op
                 getUser·p0.95:   4.776 ms/op
                 getUser·p0.99:   7.504 ms/op
                 getUser·p0.999:  20.866 ms/op
                 getUser·p0.9999: 23.090 ms/op
                 getUser·p1.00:   23.888 ms/op

Iteration   2: 3.471 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   2.009 ms/op
                 getUser·p0.50:   3.404 ms/op
                 getUser·p0.90:   3.949 ms/op
                 getUser·p0.95:   4.284 ms/op
                 getUser·p0.99:   6.013 ms/op
                 getUser·p0.999:  22.544 ms/op
                 getUser·p0.9999: 27.361 ms/op
                 getUser·p1.00:   28.574 ms/op

Iteration   3: 3.454 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.581 ms/op
                 getUser·p0.50:   3.330 ms/op
                 getUser·p0.90:   3.744 ms/op
                 getUser·p0.95:   3.916 ms/op
                 getUser·p0.99:   5.988 ms/op
                 getUser·p0.999:  19.839 ms/op
                 getUser·p0.9999: 28.934 ms/op
                 getUser·p1.00:   29.786 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 272030
  mean =      3.528 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7921 
    [ 2.500,  5.000) = 256117 
    [ 5.000,  7.500) = 6224 
    [ 7.500, 10.000) = 1088 
    [10.000, 12.500) = 308 
    [12.500, 15.000) = 50 
    [15.000, 17.500) = 28 
    [17.500, 20.000) = 12 
    [20.000, 22.500) = 103 
    [22.500, 25.000) = 64 
    [25.000, 27.500) = 73 

  Percentiles, ms/op:
      p(0.0000) =      1.581 ms/op
     p(50.0000) =      3.404 ms/op
     p(90.0000) =      3.977 ms/op
     p(95.0000) =      4.317 ms/op
     p(99.0000) =      6.636 ms/op
     p(99.9000) =     20.218 ms/op
     p(99.9900) =     27.984 ms/op
     p(99.9990) =     29.566 ms/op
     p(99.9999) =     29.786 ms/op
    p(100.0000) =     29.786 ms/op


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
# Warmup Iteration   1: 11.173 ±(99.9%) 0.147 ms/op
# Warmup Iteration   2: 4.531 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.329 ±(99.9%) 0.015 ms/op
Iteration   1: 4.070 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.634 ms/op
                 listUser·p0.50:   3.887 ms/op
                 listUser·p0.90:   4.440 ms/op
                 listUser·p0.95:   4.792 ms/op
                 listUser·p0.99:   7.823 ms/op
                 listUser·p0.999:  21.234 ms/op
                 listUser·p0.9999: 25.035 ms/op
                 listUser·p1.00:   25.625 ms/op

Iteration   2: 4.167 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   2.154 ms/op
                 listUser·p0.50:   4.002 ms/op
                 listUser·p0.90:   4.563 ms/op
                 listUser·p0.95:   5.022 ms/op
                 listUser·p0.99:   8.004 ms/op
                 listUser·p0.999:  20.414 ms/op
                 listUser·p0.9999: 23.298 ms/op
                 listUser·p1.00:   23.921 ms/op

Iteration   3: 4.014 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.458 ms/op
                 listUser·p0.50:   3.842 ms/op
                 listUser·p0.90:   4.350 ms/op
                 listUser·p0.95:   4.628 ms/op
                 listUser·p0.99:   7.881 ms/op
                 listUser·p0.999:  15.869 ms/op
                 listUser·p0.9999: 23.135 ms/op
                 listUser·p1.00:   23.921 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 235119
  mean =      4.083 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16 
    [ 2.500,  5.000) = 225307 
    [ 5.000,  7.500) = 6970 
    [ 7.500, 10.000) = 1815 
    [10.000, 12.500) = 418 
    [12.500, 15.000) = 191 
    [15.000, 17.500) = 133 
    [17.500, 20.000) = 55 
    [20.000, 22.500) = 102 
    [22.500, 25.000) = 104 
    [25.000, 27.500) = 8 

  Percentiles, ms/op:
      p(0.0000) =      1.634 ms/op
     p(50.0000) =      3.887 ms/op
     p(90.0000) =      4.456 ms/op
     p(95.0000) =      4.792 ms/op
     p(99.0000) =      7.897 ms/op
     p(99.9000) =     18.448 ms/op
     p(99.9900) =     23.855 ms/op
     p(99.9990) =     25.559 ms/op
     p(99.9999) =     25.625 ms/op
    p(100.0000) =     25.625 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.145 ± 1.557  ops/ms
ClientPb.existUser                       thrpt       3   9.673 ± 0.426  ops/ms
ClientPb.getUser                         thrpt       3   9.571 ± 2.379  ops/ms
ClientPb.listUser                        thrpt       3   8.139 ± 3.606  ops/ms
ClientPb.createUser                       avgt       3   3.446 ± 1.135   ms/op
ClientPb.existUser                        avgt       3   3.272 ± 1.278   ms/op
ClientPb.getUser                          avgt       3   3.377 ± 0.634   ms/op
ClientPb.listUser                         avgt       3   3.959 ± 1.700   ms/op
ClientPb.createUser                     sample  282751   3.393 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.186           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.260           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.838           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.116           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.669           ms/op
ClientPb.createUser:createUser·p0.999   sample          19.767           ms/op
ClientPb.createUser:createUser·p0.9999  sample          33.781           ms/op
ClientPb.createUser:createUser·p1.00    sample          36.110           ms/op
ClientPb.existUser                      sample  286962   3.345 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.735           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.244           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.740           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.137           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.669           ms/op
ClientPb.existUser:existUser·p0.999     sample          19.340           ms/op
ClientPb.existUser:existUser·p0.9999    sample          29.279           ms/op
ClientPb.existUser:existUser·p1.00      sample          32.211           ms/op
ClientPb.getUser                        sample  272030   3.528 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.581           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.404           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.977           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.317           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.636           ms/op
ClientPb.getUser:getUser·p0.999         sample          20.218           ms/op
ClientPb.getUser:getUser·p0.9999        sample          27.984           ms/op
ClientPb.getUser:getUser·p1.00          sample          29.786           ms/op
ClientPb.listUser                       sample  235119   4.083 ± 0.007   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.634           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.887           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.456           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.792           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.897           ms/op
ClientPb.listUser:listUser·p0.999       sample          18.448           ms/op
ClientPb.listUser:listUser·p0.9999      sample          23.855           ms/op
ClientPb.listUser:listUser·p1.00        sample          25.625           ms/op
