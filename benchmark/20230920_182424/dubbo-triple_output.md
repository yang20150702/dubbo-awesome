# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 1.931 ops/ms
# Warmup Iteration   2: 4.722 ops/ms
# Warmup Iteration   3: 8.638 ops/ms
Iteration   1: 8.582 ops/ms
Iteration   2: 9.031 ops/ms
Iteration   3: 8.905 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  8.839 ±(99.9%) 4.227 ops/ms [Average]
  (min, avg, max) = (8.582, 8.839, 9.031), stdev = 0.232
  CI (99.9%): [4.613, 13.066] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:09
# Fork: 1 of 1
# Warmup Iteration   1: 2.552 ops/ms
# Warmup Iteration   2: 8.246 ops/ms
# Warmup Iteration   3: 9.158 ops/ms
Iteration   1: 9.320 ops/ms
Iteration   2: 9.336 ops/ms
Iteration   3: 9.483 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.380 ±(99.9%) 1.643 ops/ms [Average]
  (min, avg, max) = (9.320, 9.380, 9.483), stdev = 0.090
  CI (99.9%): [7.736, 11.023] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:11:03
# Fork: 1 of 1
# Warmup Iteration   1: 2.712 ops/ms
# Warmup Iteration   2: 8.324 ops/ms
# Warmup Iteration   3: 8.965 ops/ms
Iteration   1: 8.872 ops/ms
Iteration   2: 9.179 ops/ms
Iteration   3: 9.106 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.052 ±(99.9%) 2.921 ops/ms [Average]
  (min, avg, max) = (8.872, 9.052, 9.179), stdev = 0.160
  CI (99.9%): [6.131, 11.973] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:56
# Fork: 1 of 1
# Warmup Iteration   1: 2.595 ops/ms
# Warmup Iteration   2: 6.292 ops/ms
# Warmup Iteration   3: 7.348 ops/ms
Iteration   1: 7.366 ops/ms
Iteration   2: 7.398 ops/ms
Iteration   3: 7.505 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.423 ±(99.9%) 1.324 ops/ms [Average]
  (min, avg, max) = (7.366, 7.423, 7.505), stdev = 0.073
  CI (99.9%): [6.099, 8.748] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:50
# Fork: 1 of 1
# Warmup Iteration   1: 11.789 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 3.847 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.710 ±(99.9%) 0.004 ms/op
Iteration   1: 3.667 ±(99.9%) 0.006 ms/op
Iteration   2: 3.611 ±(99.9%) 0.007 ms/op
Iteration   3: 3.588 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.622 ±(99.9%) 0.736 ms/op [Average]
  (min, avg, max) = (3.588, 3.622, 3.667), stdev = 0.040
  CI (99.9%): [2.886, 4.358] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:43
# Fork: 1 of 1
# Warmup Iteration   1: 9.262 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 3.747 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.509 ±(99.9%) 0.004 ms/op
Iteration   1: 3.468 ±(99.9%) 0.005 ms/op
Iteration   2: 3.482 ±(99.9%) 0.005 ms/op
Iteration   3: 3.403 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.451 ±(99.9%) 0.769 ms/op [Average]
  (min, avg, max) = (3.403, 3.451, 3.482), stdev = 0.042
  CI (99.9%): [2.682, 4.219] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:36
# Fork: 1 of 1
# Warmup Iteration   1: 8.987 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 3.754 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.627 ±(99.9%) 0.006 ms/op
Iteration   1: 3.507 ±(99.9%) 0.008 ms/op
Iteration   2: 3.548 ±(99.9%) 0.005 ms/op
Iteration   3: 3.574 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.543 ±(99.9%) 0.616 ms/op [Average]
  (min, avg, max) = (3.507, 3.543, 3.574), stdev = 0.034
  CI (99.9%): [2.928, 4.159] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 10.590 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 4.559 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.306 ±(99.9%) 0.007 ms/op
Iteration   1: 4.238 ±(99.9%) 0.006 ms/op
Iteration   2: 4.226 ±(99.9%) 0.005 ms/op
Iteration   3: 4.314 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.259 ±(99.9%) 0.871 ms/op [Average]
  (min, avg, max) = (4.226, 4.259, 4.314), stdev = 0.048
  CI (99.9%): [3.388, 5.130] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 10.789 ±(99.9%) 0.140 ms/op
# Warmup Iteration   2: 4.340 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 4.073 ±(99.9%) 0.017 ms/op
Iteration   1: 3.689 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.661 ms/op
                 createUser·p0.50:   3.600 ms/op
                 createUser·p0.90:   4.293 ms/op
                 createUser·p0.95:   4.555 ms/op
                 createUser·p0.99:   5.964 ms/op
                 createUser·p0.999:  21.981 ms/op
                 createUser·p0.9999: 24.521 ms/op
                 createUser·p1.00:   25.068 ms/op

Iteration   2: 3.657 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.290 ms/op
                 createUser·p0.50:   3.490 ms/op
                 createUser·p0.90:   4.342 ms/op
                 createUser·p0.95:   4.571 ms/op
                 createUser·p0.99:   6.021 ms/op
                 createUser·p0.999:  22.627 ms/op
                 createUser·p0.9999: 30.015 ms/op
                 createUser·p1.00:   30.441 ms/op

Iteration   3: 3.627 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.169 ms/op
                 createUser·p0.50:   3.502 ms/op
                 createUser·p0.90:   4.141 ms/op
                 createUser·p0.95:   4.424 ms/op
                 createUser·p0.99:   6.062 ms/op
                 createUser·p0.999:  18.145 ms/op
                 createUser·p0.9999: 29.861 ms/op
                 createUser·p1.00:   30.638 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 262449
  mean =      3.658 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3009 
    [ 2.500,  5.000) = 253827 
    [ 5.000,  7.500) = 4544 
    [ 7.500, 10.000) = 538 
    [10.000, 12.500) = 189 
    [12.500, 15.000) = 38 
    [15.000, 17.500) = 16 
    [17.500, 20.000) = 22 
    [20.000, 22.500) = 47 
    [22.500, 25.000) = 123 
    [25.000, 27.500) = 28 
    [27.500, 30.000) = 51 
    [30.000, 32.500) = 17 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.169 ms/op
     p(50.0000) =      3.514 ms/op
     p(90.0000) =      4.268 ms/op
     p(95.0000) =      4.530 ms/op
     p(99.0000) =      6.005 ms/op
     p(99.9000) =     20.662 ms/op
     p(99.9900) =     29.721 ms/op
     p(99.9990) =     30.441 ms/op
     p(99.9999) =     30.638 ms/op
    p(100.0000) =     30.638 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 9.049 ±(99.9%) 0.130 ms/op
# Warmup Iteration   2: 3.751 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.498 ±(99.9%) 0.008 ms/op
Iteration   1: 3.462 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.319 ms/op
                 existUser·p0.50:   3.322 ms/op
                 existUser·p0.90:   3.953 ms/op
                 existUser·p0.95:   4.235 ms/op
                 existUser·p0.99:   5.628 ms/op
                 existUser·p0.999:  20.093 ms/op
                 existUser·p0.9999: 22.807 ms/op
                 existUser·p1.00:   23.658 ms/op

Iteration   2: 3.436 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.380 ms/op
                 existUser·p0.50:   3.351 ms/op
                 existUser·p0.90:   3.944 ms/op
                 existUser·p0.95:   4.219 ms/op
                 existUser·p0.99:   5.695 ms/op
                 existUser·p0.999:  21.737 ms/op
                 existUser·p0.9999: 24.762 ms/op
                 existUser·p1.00:   25.952 ms/op

Iteration   3: 3.490 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.763 ms/op
                 existUser·p0.50:   3.355 ms/op
                 existUser·p0.90:   3.940 ms/op
                 existUser·p0.95:   4.293 ms/op
                 existUser·p0.99:   5.816 ms/op
                 existUser·p0.999:  14.434 ms/op
                 existUser·p0.9999: 26.542 ms/op
                 existUser·p1.00:   27.525 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 277210
  mean =      3.462 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7014 
    [ 2.500,  5.000) = 265702 
    [ 5.000,  7.500) = 3553 
    [ 7.500, 10.000) = 409 
    [10.000, 12.500) = 146 
    [12.500, 15.000) = 116 
    [15.000, 17.500) = 14 
    [17.500, 20.000) = 2 
    [20.000, 22.500) = 86 
    [22.500, 25.000) = 132 
    [25.000, 27.500) = 35 

  Percentiles, ms/op:
      p(0.0000) =      0.763 ms/op
     p(50.0000) =      3.346 ms/op
     p(90.0000) =      3.944 ms/op
     p(95.0000) =      4.252 ms/op
     p(99.0000) =      5.751 ms/op
     p(99.9000) =     14.565 ms/op
     p(99.9900) =     25.592 ms/op
     p(99.9990) =     26.942 ms/op
     p(99.9999) =     27.525 ms/op
    p(100.0000) =     27.525 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 10.997 ±(99.9%) 0.139 ms/op
# Warmup Iteration   2: 3.940 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.737 ±(99.9%) 0.010 ms/op
Iteration   1: 3.605 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.835 ms/op
                 getUser·p0.50:   3.490 ms/op
                 getUser·p0.90:   3.957 ms/op
                 getUser·p0.95:   4.243 ms/op
                 getUser·p0.99:   6.685 ms/op
                 getUser·p0.999:  17.081 ms/op
                 getUser·p0.9999: 18.874 ms/op
                 getUser·p1.00:   19.300 ms/op

Iteration   2: 3.595 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.735 ms/op
                 getUser·p0.50:   3.457 ms/op
                 getUser·p0.90:   3.953 ms/op
                 getUser·p0.95:   4.268 ms/op
                 getUser·p0.99:   6.988 ms/op
                 getUser·p0.999:  18.679 ms/op
                 getUser·p0.9999: 20.811 ms/op
                 getUser·p1.00:   21.660 ms/op

Iteration   3: 3.468 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.391 ms/op
                 getUser·p0.50:   3.363 ms/op
                 getUser·p0.90:   3.850 ms/op
                 getUser·p0.95:   4.043 ms/op
                 getUser·p0.99:   5.546 ms/op
                 getUser·p0.999:  17.185 ms/op
                 getUser·p0.9999: 22.111 ms/op
                 getUser·p1.00:   23.560 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 269830
  mean =      3.555 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1433 
    [ 2.500,  5.000) = 261488 
    [ 5.000,  7.500) = 5587 
    [ 7.500, 10.000) = 852 
    [10.000, 12.500) = 150 
    [12.500, 15.000) = 19 
    [15.000, 17.500) = 51 
    [17.500, 20.000) = 163 
    [20.000, 22.500) = 79 
    [22.500, 25.000) = 8 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.391 ms/op
     p(50.0000) =      3.432 ms/op
     p(90.0000) =      3.924 ms/op
     p(95.0000) =      4.166 ms/op
     p(99.0000) =      6.685 ms/op
     p(99.9000) =     17.269 ms/op
     p(99.9900) =     21.234 ms/op
     p(99.9990) =     23.187 ms/op
     p(99.9999) =     23.560 ms/op
    p(100.0000) =     23.560 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 12.213 ±(99.9%) 0.227 ms/op
# Warmup Iteration   2: 4.700 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.471 ±(99.9%) 0.013 ms/op
Iteration   1: 4.306 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.974 ms/op
                 listUser·p0.50:   4.194 ms/op
                 listUser·p0.90:   4.702 ms/op
                 listUser·p0.95:   4.956 ms/op
                 listUser·p0.99:   7.422 ms/op
                 listUser·p0.999:  21.704 ms/op
                 listUser·p0.9999: 24.347 ms/op
                 listUser·p1.00:   25.461 ms/op

Iteration   2: 4.296 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.470 ms/op
                 listUser·p0.50:   4.166 ms/op
                 listUser·p0.90:   4.719 ms/op
                 listUser·p0.95:   5.022 ms/op
                 listUser·p0.99:   7.537 ms/op
                 listUser·p0.999:  15.492 ms/op
                 listUser·p0.9999: 16.777 ms/op
                 listUser·p1.00:   17.957 ms/op

Iteration   3: 4.283 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.931 ms/op
                 listUser·p0.50:   4.059 ms/op
                 listUser·p0.90:   4.809 ms/op
                 listUser·p0.95:   5.177 ms/op
                 listUser·p0.99:   8.020 ms/op
                 listUser·p0.999:  16.368 ms/op
                 listUser·p0.9999: 19.910 ms/op
                 listUser·p1.00:   20.840 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 223403
  mean =      4.295 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15 
    [ 2.500,  5.000) = 211270 
    [ 5.000,  7.500) = 9713 
    [ 7.500, 10.000) = 1525 
    [10.000, 12.500) = 272 
    [12.500, 15.000) = 262 
    [15.000, 17.500) = 207 
    [17.500, 20.000) = 37 
    [20.000, 22.500) = 49 
    [22.500, 25.000) = 51 
    [25.000, 27.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      1.931 ms/op
     p(50.0000) =      4.149 ms/op
     p(90.0000) =      4.743 ms/op
     p(95.0000) =      5.054 ms/op
     p(99.0000) =      7.635 ms/op
     p(99.9000) =     16.394 ms/op
     p(99.9900) =     23.777 ms/op
     p(99.9990) =     25.095 ms/op
     p(99.9999) =     25.461 ms/op
    p(100.0000) =     25.461 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   8.839 ± 4.227  ops/ms
ClientPb.existUser                       thrpt       3   9.380 ± 1.643  ops/ms
ClientPb.getUser                         thrpt       3   9.052 ± 2.921  ops/ms
ClientPb.listUser                        thrpt       3   7.423 ± 1.324  ops/ms
ClientPb.createUser                       avgt       3   3.622 ± 0.736   ms/op
ClientPb.existUser                        avgt       3   3.451 ± 0.769   ms/op
ClientPb.getUser                          avgt       3   3.543 ± 0.616   ms/op
ClientPb.listUser                         avgt       3   4.259 ± 0.871   ms/op
ClientPb.createUser                     sample  262449   3.658 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.169           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.514           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.268           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.530           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.005           ms/op
ClientPb.createUser:createUser·p0.999   sample          20.662           ms/op
ClientPb.createUser:createUser·p0.9999  sample          29.721           ms/op
ClientPb.createUser:createUser·p1.00    sample          30.638           ms/op
ClientPb.existUser                      sample  277210   3.462 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.763           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.346           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.944           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.252           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.751           ms/op
ClientPb.existUser:existUser·p0.999     sample          14.565           ms/op
ClientPb.existUser:existUser·p0.9999    sample          25.592           ms/op
ClientPb.existUser:existUser·p1.00      sample          27.525           ms/op
ClientPb.getUser                        sample  269830   3.555 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.391           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.432           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.924           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.166           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.685           ms/op
ClientPb.getUser:getUser·p0.999         sample          17.269           ms/op
ClientPb.getUser:getUser·p0.9999        sample          21.234           ms/op
ClientPb.getUser:getUser·p1.00          sample          23.560           ms/op
ClientPb.listUser                       sample  223403   4.295 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.931           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.149           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.743           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.054           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.635           ms/op
ClientPb.listUser:listUser·p0.999       sample          16.394           ms/op
ClientPb.listUser:listUser·p0.9999      sample          23.777           ms/op
ClientPb.listUser:listUser·p1.00        sample          25.461           ms/op
