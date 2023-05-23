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
# Warmup Iteration   1: 1.851 ops/ms
# Warmup Iteration   2: 4.846 ops/ms
# Warmup Iteration   3: 7.471 ops/ms
Iteration   1: 8.582 ops/ms
Iteration   2: 8.502 ops/ms
Iteration   3: 8.439 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  8.508 ±(99.9%) 1.303 ops/ms [Average]
  (min, avg, max) = (8.439, 8.508, 8.582), stdev = 0.071
  CI (99.9%): [7.204, 9.811] (assumes normal distribution)


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
# Warmup Iteration   1: 2.847 ops/ms
# Warmup Iteration   2: 8.188 ops/ms
# Warmup Iteration   3: 8.850 ops/ms
Iteration   1: 8.821 ops/ms
Iteration   2: 8.997 ops/ms
Iteration   3: 8.927 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.915 ±(99.9%) 1.618 ops/ms [Average]
  (min, avg, max) = (8.821, 8.915, 8.997), stdev = 0.089
  CI (99.9%): [7.297, 10.534] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:57
# Fork: 1 of 1
# Warmup Iteration   1: 2.632 ops/ms
# Warmup Iteration   2: 7.800 ops/ms
# Warmup Iteration   3: 8.609 ops/ms
Iteration   1: 9.052 ops/ms
Iteration   2: 8.851 ops/ms
Iteration   3: 8.355 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  8.753 ±(99.9%) 6.540 ops/ms [Average]
  (min, avg, max) = (8.355, 8.753, 9.052), stdev = 0.358
  CI (99.9%): [2.213, 15.293] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:50
# Fork: 1 of 1
# Warmup Iteration   1: 2.593 ops/ms
# Warmup Iteration   2: 6.585 ops/ms
# Warmup Iteration   3: 7.198 ops/ms
Iteration   1: 7.539 ops/ms
Iteration   2: 7.766 ops/ms
Iteration   3: 7.882 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.729 ±(99.9%) 3.181 ops/ms [Average]
  (min, avg, max) = (7.539, 7.729, 7.882), stdev = 0.174
  CI (99.9%): [4.548, 10.909] (assumes normal distribution)


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
# Warmup Iteration   1: 10.381 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.909 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.608 ±(99.9%) 0.013 ms/op
Iteration   1: 3.743 ±(99.9%) 0.008 ms/op
Iteration   2: 3.770 ±(99.9%) 0.005 ms/op
Iteration   3: 3.513 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.675 ±(99.9%) 2.581 ms/op [Average]
  (min, avg, max) = (3.513, 3.675, 3.770), stdev = 0.141
  CI (99.9%): [1.094, 6.256] (assumes normal distribution)


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
# Warmup Iteration   1: 8.712 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.804 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.444 ±(99.9%) 0.007 ms/op
Iteration   1: 3.551 ±(99.9%) 0.007 ms/op
Iteration   2: 3.433 ±(99.9%) 0.008 ms/op
Iteration   3: 3.473 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.486 ±(99.9%) 1.099 ms/op [Average]
  (min, avg, max) = (3.433, 3.486, 3.551), stdev = 0.060
  CI (99.9%): [2.387, 4.584] (assumes normal distribution)


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
# Warmup Iteration   1: 11.368 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 3.978 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.794 ±(99.9%) 0.009 ms/op
Iteration   1: 3.731 ±(99.9%) 0.005 ms/op
Iteration   2: 3.657 ±(99.9%) 0.010 ms/op
Iteration   3: 3.614 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.668 ±(99.9%) 1.081 ms/op [Average]
  (min, avg, max) = (3.614, 3.668, 3.731), stdev = 0.059
  CI (99.9%): [2.587, 4.748] (assumes normal distribution)


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
# Warmup Iteration   1: 11.611 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 4.577 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.423 ±(99.9%) 0.009 ms/op
Iteration   1: 4.412 ±(99.9%) 0.011 ms/op
Iteration   2: 4.178 ±(99.9%) 0.014 ms/op
Iteration   3: 4.232 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.274 ±(99.9%) 2.232 ms/op [Average]
  (min, avg, max) = (4.178, 4.274, 4.412), stdev = 0.122
  CI (99.9%): [2.042, 6.506] (assumes normal distribution)


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
# Warmup Iteration   1: 9.758 ±(99.9%) 0.126 ms/op
# Warmup Iteration   2: 4.280 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 3.738 ±(99.9%) 0.012 ms/op
Iteration   1: 3.558 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.733 ms/op
                 createUser·p0.50:   3.490 ms/op
                 createUser·p0.90:   3.949 ms/op
                 createUser·p0.95:   4.481 ms/op
                 createUser·p0.99:   6.439 ms/op
                 createUser·p0.999:  21.249 ms/op
                 createUser·p0.9999: 26.674 ms/op
                 createUser·p1.00:   28.901 ms/op

Iteration   2: 3.540 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.436 ms/op
                 createUser·p0.50:   3.437 ms/op
                 createUser·p0.90:   4.063 ms/op
                 createUser·p0.95:   4.432 ms/op
                 createUser·p0.99:   6.103 ms/op
                 createUser·p0.999:  23.462 ms/op
                 createUser·p0.9999: 33.258 ms/op
                 createUser·p1.00:   36.766 ms/op

Iteration   3: 3.667 ±(99.9%) 0.015 ms/op
                 createUser·p0.00:   1.507 ms/op
                 createUser·p0.50:   3.576 ms/op
                 createUser·p0.90:   4.293 ms/op
                 createUser·p0.95:   4.743 ms/op
                 createUser·p0.99:   6.259 ms/op
                 createUser·p0.999:  26.082 ms/op
                 createUser·p0.9999: 41.146 ms/op
                 createUser·p1.00:   41.878 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 267442
  mean =      3.587 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 259271 
    [ 5.000, 10.000) = 7617 
    [10.000, 15.000) = 226 
    [15.000, 20.000) = 22 
    [20.000, 25.000) = 125 
    [25.000, 30.000) = 85 
    [30.000, 35.000) = 34 
    [35.000, 40.000) = 45 
    [40.000, 45.000) = 17 

  Percentiles, ms/op:
      p(0.0000) =      1.436 ms/op
     p(50.0000) =      3.498 ms/op
     p(90.0000) =      4.100 ms/op
     p(95.0000) =      4.579 ms/op
     p(99.0000) =      6.247 ms/op
     p(99.9000) =     22.923 ms/op
     p(99.9900) =     39.535 ms/op
     p(99.9990) =     41.550 ms/op
     p(99.9999) =     41.878 ms/op
    p(100.0000) =     41.878 ms/op


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
# Warmup Iteration   1: 8.699 ±(99.9%) 0.111 ms/op
# Warmup Iteration   2: 3.731 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.549 ±(99.9%) 0.009 ms/op
Iteration   1: 3.507 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.481 ms/op
                 existUser·p0.50:   3.469 ms/op
                 existUser·p0.90:   3.834 ms/op
                 existUser·p0.95:   4.076 ms/op
                 existUser·p0.99:   5.619 ms/op
                 existUser·p0.999:  20.611 ms/op
                 existUser·p0.9999: 28.459 ms/op
                 existUser·p1.00:   28.934 ms/op

Iteration   2: 3.670 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.436 ms/op
                 existUser·p0.50:   3.600 ms/op
                 existUser·p0.90:   4.174 ms/op
                 existUser·p0.95:   4.694 ms/op
                 existUser·p0.99:   6.857 ms/op
                 existUser·p0.999:  13.697 ms/op
                 existUser·p0.9999: 27.502 ms/op
                 existUser·p1.00:   28.049 ms/op

Iteration   3: 3.616 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   1.618 ms/op
                 existUser·p0.50:   3.514 ms/op
                 existUser·p0.90:   4.084 ms/op
                 existUser·p0.95:   4.497 ms/op
                 existUser·p0.99:   5.962 ms/op
                 existUser·p0.999:  25.518 ms/op
                 existUser·p0.9999: 49.228 ms/op
                 existUser·p1.00:   49.807 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 266758
  mean =      3.597 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 259747 
    [ 5.000, 10.000) = 6500 
    [10.000, 15.000) = 236 
    [15.000, 20.000) = 19 
    [20.000, 25.000) = 55 
    [25.000, 30.000) = 169 
    [30.000, 35.000) = 0 
    [35.000, 40.000) = 0 
    [40.000, 45.000) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.436 ms/op
     p(50.0000) =      3.523 ms/op
     p(90.0000) =      4.010 ms/op
     p(95.0000) =      4.407 ms/op
     p(99.0000) =      6.201 ms/op
     p(99.9000) =     15.973 ms/op
     p(99.9900) =     47.097 ms/op
     p(99.9990) =     49.523 ms/op
     p(99.9999) =     49.807 ms/op
    p(100.0000) =     49.807 ms/op


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
# Warmup Iteration   1: 10.828 ±(99.9%) 0.162 ms/op
# Warmup Iteration   2: 4.082 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.930 ±(99.9%) 0.012 ms/op
Iteration   1: 3.865 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.423 ms/op
                 getUser·p0.50:   3.695 ms/op
                 getUser·p0.90:   4.481 ms/op
                 getUser·p0.95:   5.046 ms/op
                 getUser·p0.99:   7.799 ms/op
                 getUser·p0.999:  24.084 ms/op
                 getUser·p0.9999: 30.337 ms/op
                 getUser·p1.00:   31.687 ms/op

Iteration   2: 3.702 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.800 ms/op
                 getUser·p0.50:   3.584 ms/op
                 getUser·p0.90:   4.366 ms/op
                 getUser·p0.95:   4.743 ms/op
                 getUser·p0.99:   6.398 ms/op
                 getUser·p0.999:  22.402 ms/op
                 getUser·p0.9999: 32.473 ms/op
                 getUser·p1.00:   33.128 ms/op

Iteration   3: 3.619 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.911 ms/op
                 getUser·p0.50:   3.535 ms/op
                 getUser·p0.90:   4.104 ms/op
                 getUser·p0.95:   4.571 ms/op
                 getUser·p0.99:   6.676 ms/op
                 getUser·p0.999:  23.119 ms/op
                 getUser·p0.9999: 29.665 ms/op
                 getUser·p1.00:   30.966 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 257539
  mean =      3.726 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3077 
    [ 2.500,  5.000) = 244336 
    [ 5.000,  7.500) = 8076 
    [ 7.500, 10.000) = 1377 
    [10.000, 12.500) = 283 
    [12.500, 15.000) = 68 
    [15.000, 17.500) = 17 
    [17.500, 20.000) = 17 
    [20.000, 22.500) = 26 
    [22.500, 25.000) = 91 
    [25.000, 27.500) = 70 
    [27.500, 30.000) = 58 
    [30.000, 32.500) = 36 
    [32.500, 35.000) = 7 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.423 ms/op
     p(50.0000) =      3.617 ms/op
     p(90.0000) =      4.334 ms/op
     p(95.0000) =      4.776 ms/op
     p(99.0000) =      7.021 ms/op
     p(99.9000) =     22.577 ms/op
     p(99.9900) =     30.704 ms/op
     p(99.9990) =     32.879 ms/op
     p(99.9999) =     33.128 ms/op
    p(100.0000) =     33.128 ms/op


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
# Warmup Iteration   1: 12.615 ±(99.9%) 0.173 ms/op
# Warmup Iteration   2: 4.788 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 4.537 ±(99.9%) 0.016 ms/op
Iteration   1: 4.485 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   1.477 ms/op
                 listUser·p0.50:   4.260 ms/op
                 listUser·p0.90:   5.087 ms/op
                 listUser·p0.95:   5.759 ms/op
                 listUser·p0.99:   8.471 ms/op
                 listUser·p0.999:  24.609 ms/op
                 listUser·p0.9999: 28.705 ms/op
                 listUser·p1.00:   29.458 ms/op

Iteration   2: 4.191 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.224 ms/op
                 listUser·p0.50:   4.141 ms/op
                 listUser·p0.90:   4.522 ms/op
                 listUser·p0.95:   5.153 ms/op
                 listUser·p0.99:   7.569 ms/op
                 listUser·p0.999:  16.713 ms/op
                 listUser·p0.9999: 21.103 ms/op
                 listUser·p1.00:   21.135 ms/op

Iteration   3: 4.086 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.591 ms/op
                 listUser·p0.50:   3.969 ms/op
                 listUser·p0.90:   4.612 ms/op
                 listUser·p0.95:   5.087 ms/op
                 listUser·p0.99:   7.707 ms/op
                 listUser·p0.999:  15.740 ms/op
                 listUser·p0.9999: 18.448 ms/op
                 listUser·p1.00:   18.547 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 226036
  mean =      4.247 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 113 
    [ 2.500,  5.000) = 208417 
    [ 5.000,  7.500) = 14308 
    [ 7.500, 10.000) = 2196 
    [10.000, 12.500) = 393 
    [12.500, 15.000) = 168 
    [15.000, 17.500) = 203 
    [17.500, 20.000) = 68 
    [20.000, 22.500) = 46 
    [22.500, 25.000) = 58 
    [25.000, 27.500) = 49 

  Percentiles, ms/op:
      p(0.0000) =      1.477 ms/op
     p(50.0000) =      4.116 ms/op
     p(90.0000) =      4.841 ms/op
     p(95.0000) =      5.325 ms/op
     p(99.0000) =      7.971 ms/op
     p(99.9000) =     17.629 ms/op
     p(99.9900) =     26.797 ms/op
     p(99.9990) =     29.349 ms/op
     p(99.9999) =     29.458 ms/op
    p(100.0000) =     29.458 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   8.508 ± 1.303  ops/ms
ClientPb.existUser                       thrpt       3   8.915 ± 1.618  ops/ms
ClientPb.getUser                         thrpt       3   8.753 ± 6.540  ops/ms
ClientPb.listUser                        thrpt       3   7.729 ± 3.181  ops/ms
ClientPb.createUser                       avgt       3   3.675 ± 2.581   ms/op
ClientPb.existUser                        avgt       3   3.486 ± 1.099   ms/op
ClientPb.getUser                          avgt       3   3.668 ± 1.081   ms/op
ClientPb.listUser                         avgt       3   4.274 ± 2.232   ms/op
ClientPb.createUser                     sample  267442   3.587 ± 0.007   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.436           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.498           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.100           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.579           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.247           ms/op
ClientPb.createUser:createUser·p0.999   sample          22.923           ms/op
ClientPb.createUser:createUser·p0.9999  sample          39.535           ms/op
ClientPb.createUser:createUser·p1.00    sample          41.878           ms/op
ClientPb.existUser                      sample  266758   3.597 ± 0.007   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.436           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.523           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.010           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.407           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.201           ms/op
ClientPb.existUser:existUser·p0.999     sample          15.973           ms/op
ClientPb.existUser:existUser·p0.9999    sample          47.097           ms/op
ClientPb.existUser:existUser·p1.00      sample          49.807           ms/op
ClientPb.getUser                        sample  257539   3.726 ± 0.007   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.423           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.617           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.334           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.776           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.021           ms/op
ClientPb.getUser:getUser·p0.999         sample          22.577           ms/op
ClientPb.getUser:getUser·p0.9999        sample          30.704           ms/op
ClientPb.getUser:getUser·p1.00          sample          33.128           ms/op
ClientPb.listUser                       sample  226036   4.247 ± 0.007   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.477           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.116           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.841           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.325           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.971           ms/op
ClientPb.listUser:listUser·p0.999       sample          17.629           ms/op
ClientPb.listUser:listUser·p0.9999      sample          26.797           ms/op
ClientPb.listUser:listUser·p1.00        sample          29.458           ms/op
