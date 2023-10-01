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
# Warmup Iteration   1: 1.978 ops/ms
# Warmup Iteration   2: 5.481 ops/ms
# Warmup Iteration   3: 8.446 ops/ms
Iteration   1: 9.287 ops/ms
Iteration   2: 9.112 ops/ms
Iteration   3: 9.315 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.238 ±(99.9%) 2.004 ops/ms [Average]
  (min, avg, max) = (9.112, 9.238, 9.315), stdev = 0.110
  CI (99.9%): [7.234, 11.242] (assumes normal distribution)


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
# Warmup Iteration   1: 2.844 ops/ms
# Warmup Iteration   2: 9.122 ops/ms
# Warmup Iteration   3: 9.422 ops/ms
Iteration   1: 9.616 ops/ms
Iteration   2: 9.860 ops/ms
Iteration   3: 9.720 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.732 ±(99.9%) 2.233 ops/ms [Average]
  (min, avg, max) = (9.616, 9.732, 9.860), stdev = 0.122
  CI (99.9%): [7.500, 11.965] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:57
# Fork: 1 of 1
# Warmup Iteration   1: 3.001 ops/ms
# Warmup Iteration   2: 8.519 ops/ms
# Warmup Iteration   3: 8.653 ops/ms
Iteration   1: 9.341 ops/ms
Iteration   2: 9.324 ops/ms
Iteration   3: 8.995 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.220 ±(99.9%) 3.552 ops/ms [Average]
  (min, avg, max) = (8.995, 9.220, 9.341), stdev = 0.195
  CI (99.9%): [5.668, 12.772] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:50
# Fork: 1 of 1
# Warmup Iteration   1: 2.697 ops/ms
# Warmup Iteration   2: 7.160 ops/ms
# Warmup Iteration   3: 7.415 ops/ms
Iteration   1: 7.577 ops/ms
Iteration   2: 7.720 ops/ms
Iteration   3: 7.726 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.674 ±(99.9%) 1.540 ops/ms [Average]
  (min, avg, max) = (7.577, 7.674, 7.726), stdev = 0.084
  CI (99.9%): [6.135, 9.214] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:45
# Fork: 1 of 1
# Warmup Iteration   1: 11.011 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 3.804 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.698 ±(99.9%) 0.005 ms/op
Iteration   1: 3.551 ±(99.9%) 0.006 ms/op
Iteration   2: 3.445 ±(99.9%) 0.006 ms/op
Iteration   3: 3.475 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.490 ±(99.9%) 1.000 ms/op [Average]
  (min, avg, max) = (3.445, 3.490, 3.551), stdev = 0.055
  CI (99.9%): [2.490, 4.490] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 8.923 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.621 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.410 ±(99.9%) 0.003 ms/op
Iteration   1: 3.435 ±(99.9%) 0.005 ms/op
Iteration   2: 3.371 ±(99.9%) 0.005 ms/op
Iteration   3: 3.417 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.408 ±(99.9%) 0.606 ms/op [Average]
  (min, avg, max) = (3.371, 3.408, 3.435), stdev = 0.033
  CI (99.9%): [2.802, 4.014] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 10.317 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 3.720 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.568 ±(99.9%) 0.006 ms/op
Iteration   1: 3.574 ±(99.9%) 0.007 ms/op
Iteration   2: 3.607 ±(99.9%) 0.004 ms/op
Iteration   3: 3.403 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.528 ±(99.9%) 1.998 ms/op [Average]
  (min, avg, max) = (3.403, 3.528, 3.607), stdev = 0.110
  CI (99.9%): [1.530, 5.526] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 10.980 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 4.810 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.186 ±(99.9%) 0.009 ms/op
Iteration   1: 4.103 ±(99.9%) 0.010 ms/op
Iteration   2: 4.093 ±(99.9%) 0.008 ms/op
Iteration   3: 4.251 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.149 ±(99.9%) 1.613 ms/op [Average]
  (min, avg, max) = (4.093, 4.149, 4.251), stdev = 0.088
  CI (99.9%): [2.536, 5.762] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 9.664 ±(99.9%) 0.146 ms/op
# Warmup Iteration   2: 3.998 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.393 ±(99.9%) 0.009 ms/op
Iteration   1: 3.538 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.470 ms/op
                 createUser·p0.50:   3.400 ms/op
                 createUser·p0.90:   4.076 ms/op
                 createUser·p0.95:   4.415 ms/op
                 createUser·p0.99:   6.660 ms/op
                 createUser·p0.999:  21.089 ms/op
                 createUser·p0.9999: 23.167 ms/op
                 createUser·p1.00:   24.281 ms/op

Iteration   2: 3.487 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.067 ms/op
                 createUser·p0.50:   3.301 ms/op
                 createUser·p0.90:   3.912 ms/op
                 createUser·p0.95:   4.284 ms/op
                 createUser·p0.99:   7.234 ms/op
                 createUser·p0.999:  22.913 ms/op
                 createUser·p0.9999: 26.340 ms/op
                 createUser·p1.00:   27.263 ms/op

Iteration   3: 3.605 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.159 ms/op
                 createUser·p0.50:   3.445 ms/op
                 createUser·p0.90:   4.219 ms/op
                 createUser·p0.95:   4.866 ms/op
                 createUser·p0.99:   6.521 ms/op
                 createUser·p0.999:  17.433 ms/op
                 createUser·p0.9999: 24.294 ms/op
                 createUser·p1.00:   25.919 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 270844
  mean =      3.543 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3704 
    [ 2.500,  5.000) = 258413 
    [ 5.000,  7.500) = 7101 
    [ 7.500, 10.000) = 933 
    [10.000, 12.500) = 276 
    [12.500, 15.000) = 51 
    [15.000, 17.500) = 67 
    [17.500, 20.000) = 10 
    [20.000, 22.500) = 115 
    [22.500, 25.000) = 133 
    [25.000, 27.500) = 41 

  Percentiles, ms/op:
      p(0.0000) =      1.067 ms/op
     p(50.0000) =      3.379 ms/op
     p(90.0000) =      4.084 ms/op
     p(95.0000) =      4.530 ms/op
     p(99.0000) =      6.939 ms/op
     p(99.9000) =     20.747 ms/op
     p(99.9900) =     25.813 ms/op
     p(99.9990) =     26.724 ms/op
     p(99.9999) =     27.263 ms/op
    p(100.0000) =     27.263 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 8.493 ±(99.9%) 0.105 ms/op
# Warmup Iteration   2: 3.612 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.315 ±(99.9%) 0.009 ms/op
Iteration   1: 3.376 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.007 ms/op
                 existUser·p0.50:   3.265 ms/op
                 existUser·p0.90:   3.752 ms/op
                 existUser·p0.95:   4.141 ms/op
                 existUser·p0.99:   6.660 ms/op
                 existUser·p0.999:  15.472 ms/op
                 existUser·p0.9999: 25.346 ms/op
                 existUser·p1.00:   25.657 ms/op

Iteration   2: 3.363 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.901 ms/op
                 existUser·p0.50:   3.203 ms/op
                 existUser·p0.90:   3.768 ms/op
                 existUser·p0.95:   4.227 ms/op
                 existUser·p0.99:   6.283 ms/op
                 existUser·p0.999:  20.804 ms/op
                 existUser·p0.9999: 26.214 ms/op
                 existUser·p1.00:   27.722 ms/op

Iteration   3: 3.443 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.692 ms/op
                 existUser·p0.50:   3.281 ms/op
                 existUser·p0.90:   3.908 ms/op
                 existUser·p0.95:   4.415 ms/op
                 existUser·p0.99:   6.865 ms/op
                 existUser·p0.999:  20.593 ms/op
                 existUser·p0.9999: 25.657 ms/op
                 existUser·p1.00:   26.542 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 282837
  mean =      3.393 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8845 
    [ 2.500,  5.000) = 265823 
    [ 5.000,  7.500) = 6808 
    [ 7.500, 10.000) = 664 
    [10.000, 12.500) = 238 
    [12.500, 15.000) = 136 
    [15.000, 17.500) = 41 
    [17.500, 20.000) = 7 
    [20.000, 22.500) = 135 
    [22.500, 25.000) = 67 
    [25.000, 27.500) = 69 

  Percentiles, ms/op:
      p(0.0000) =      0.901 ms/op
     p(50.0000) =      3.260 ms/op
     p(90.0000) =      3.805 ms/op
     p(95.0000) =      4.252 ms/op
     p(99.0000) =      6.603 ms/op
     p(99.9000) =     16.812 ms/op
     p(99.9900) =     25.517 ms/op
     p(99.9990) =     27.722 ms/op
     p(99.9999) =     27.722 ms/op
    p(100.0000) =     27.722 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 9.405 ±(99.9%) 0.115 ms/op
# Warmup Iteration   2: 3.765 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.579 ±(99.9%) 0.012 ms/op
Iteration   1: 3.703 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   0.986 ms/op
                 getUser·p0.50:   3.506 ms/op
                 getUser·p0.90:   4.202 ms/op
                 getUser·p0.95:   5.407 ms/op
                 getUser·p0.99:   7.447 ms/op
                 getUser·p0.999:  17.749 ms/op
                 getUser·p0.9999: 22.446 ms/op
                 getUser·p1.00:   23.527 ms/op

Iteration   2: 3.545 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.319 ms/op
                 getUser·p0.50:   3.387 ms/op
                 getUser·p0.90:   3.998 ms/op
                 getUser·p0.95:   4.407 ms/op
                 getUser·p0.99:   6.963 ms/op
                 getUser·p0.999:  22.118 ms/op
                 getUser·p0.9999: 24.932 ms/op
                 getUser·p1.00:   25.592 ms/op

Iteration   3: 3.538 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   0.762 ms/op
                 getUser·p0.50:   3.355 ms/op
                 getUser·p0.90:   3.981 ms/op
                 getUser·p0.95:   4.293 ms/op
                 getUser·p0.99:   6.840 ms/op
                 getUser·p0.999:  19.980 ms/op
                 getUser·p0.9999: 26.542 ms/op
                 getUser·p1.00:   28.705 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 266945
  mean =      3.594 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4002 
    [ 2.500,  5.000) = 252458 
    [ 5.000,  7.500) = 8604 
    [ 7.500, 10.000) = 1065 
    [10.000, 12.500) = 345 
    [12.500, 15.000) = 119 
    [15.000, 17.500) = 22 
    [17.500, 20.000) = 64 
    [20.000, 22.500) = 97 
    [22.500, 25.000) = 136 
    [25.000, 27.500) = 31 

  Percentiles, ms/op:
      p(0.0000) =      0.762 ms/op
     p(50.0000) =      3.412 ms/op
     p(90.0000) =      4.055 ms/op
     p(95.0000) =      4.538 ms/op
     p(99.0000) =      7.160 ms/op
     p(99.9000) =     19.990 ms/op
     p(99.9900) =     25.592 ms/op
     p(99.9990) =     27.108 ms/op
     p(99.9999) =     28.705 ms/op
    p(100.0000) =     28.705 ms/op


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
# Warmup Iteration   1: 11.677 ±(99.9%) 0.155 ms/op
# Warmup Iteration   2: 4.523 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.251 ±(99.9%) 0.013 ms/op
Iteration   1: 4.304 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.548 ms/op
                 listUser·p0.50:   4.145 ms/op
                 listUser·p0.90:   4.702 ms/op
                 listUser·p0.95:   5.218 ms/op
                 listUser·p0.99:   8.536 ms/op
                 listUser·p0.999:  19.193 ms/op
                 listUser·p0.9999: 23.387 ms/op
                 listUser·p1.00:   25.428 ms/op

Iteration   2: 4.203 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.669 ms/op
                 listUser·p0.50:   4.022 ms/op
                 listUser·p0.90:   4.637 ms/op
                 listUser·p0.95:   5.046 ms/op
                 listUser·p0.99:   8.220 ms/op
                 listUser·p0.999:  15.924 ms/op
                 listUser·p0.9999: 21.056 ms/op
                 listUser·p1.00:   21.889 ms/op

Iteration   3: 4.145 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.318 ms/op
                 listUser·p0.50:   4.055 ms/op
                 listUser·p0.90:   4.456 ms/op
                 listUser·p0.95:   4.686 ms/op
                 listUser·p0.99:   7.815 ms/op
                 listUser·p0.999:  15.416 ms/op
                 listUser·p0.9999: 22.456 ms/op
                 listUser·p1.00:   25.166 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 227438
  mean =      4.216 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 97 
    [ 2.500,  5.000) = 216338 
    [ 5.000,  7.500) = 7556 
    [ 7.500, 10.000) = 2383 
    [10.000, 12.500) = 301 
    [12.500, 15.000) = 406 
    [15.000, 17.500) = 179 
    [17.500, 20.000) = 72 
    [20.000, 22.500) = 82 
    [22.500, 25.000) = 22 
    [25.000, 27.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      1.548 ms/op
     p(50.0000) =      4.084 ms/op
     p(90.0000) =      4.604 ms/op
     p(95.0000) =      4.964 ms/op
     p(99.0000) =      8.217 ms/op
     p(99.9000) =     16.592 ms/op
     p(99.9900) =     22.725 ms/op
     p(99.9990) =     25.031 ms/op
     p(99.9999) =     25.428 ms/op
    p(100.0000) =     25.428 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.238 ± 2.004  ops/ms
ClientPb.existUser                       thrpt       3   9.732 ± 2.233  ops/ms
ClientPb.getUser                         thrpt       3   9.220 ± 3.552  ops/ms
ClientPb.listUser                        thrpt       3   7.674 ± 1.540  ops/ms
ClientPb.createUser                       avgt       3   3.490 ± 1.000   ms/op
ClientPb.existUser                        avgt       3   3.408 ± 0.606   ms/op
ClientPb.getUser                          avgt       3   3.528 ± 1.998   ms/op
ClientPb.listUser                         avgt       3   4.149 ± 1.613   ms/op
ClientPb.createUser                     sample  270844   3.543 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.067           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.379           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.084           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.530           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.939           ms/op
ClientPb.createUser:createUser·p0.999   sample          20.747           ms/op
ClientPb.createUser:createUser·p0.9999  sample          25.813           ms/op
ClientPb.createUser:createUser·p1.00    sample          27.263           ms/op
ClientPb.existUser                      sample  282837   3.393 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.901           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.260           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.805           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.252           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.603           ms/op
ClientPb.existUser:existUser·p0.999     sample          16.812           ms/op
ClientPb.existUser:existUser·p0.9999    sample          25.517           ms/op
ClientPb.existUser:existUser·p1.00      sample          27.722           ms/op
ClientPb.getUser                        sample  266945   3.594 ± 0.007   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.762           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.412           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.055           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.538           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.160           ms/op
ClientPb.getUser:getUser·p0.999         sample          19.990           ms/op
ClientPb.getUser:getUser·p0.9999        sample          25.592           ms/op
ClientPb.getUser:getUser·p1.00          sample          28.705           ms/op
ClientPb.listUser                       sample  227438   4.216 ± 0.007   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.548           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.084           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.604           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.964           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.217           ms/op
ClientPb.listUser:listUser·p0.999       sample          16.592           ms/op
ClientPb.listUser:listUser·p0.9999      sample          22.725           ms/op
ClientPb.listUser:listUser·p1.00        sample          25.428           ms/op
