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
# Warmup Iteration   1: 2.073 ops/ms
# Warmup Iteration   2: 5.436 ops/ms
# Warmup Iteration   3: 8.465 ops/ms
Iteration   1: 9.077 ops/ms
Iteration   2: 8.754 ops/ms
Iteration   3: 9.253 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.028 ±(99.9%) 4.621 ops/ms [Average]
  (min, avg, max) = (8.754, 9.028, 9.253), stdev = 0.253
  CI (99.9%): [4.407, 13.649] (assumes normal distribution)


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
# Warmup Iteration   1: 2.845 ops/ms
# Warmup Iteration   2: 8.485 ops/ms
# Warmup Iteration   3: 9.362 ops/ms
Iteration   1: 9.557 ops/ms
Iteration   2: 9.481 ops/ms
Iteration   3: 9.485 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.508 ±(99.9%) 0.773 ops/ms [Average]
  (min, avg, max) = (9.481, 9.508, 9.557), stdev = 0.042
  CI (99.9%): [8.735, 10.280] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:02
# Fork: 1 of 1
# Warmup Iteration   1: 2.864 ops/ms
# Warmup Iteration   2: 8.687 ops/ms
# Warmup Iteration   3: 8.819 ops/ms
Iteration   1: 9.416 ops/ms
Iteration   2: 9.163 ops/ms
Iteration   3: 9.035 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.205 ±(99.9%) 3.533 ops/ms [Average]
  (min, avg, max) = (9.035, 9.205, 9.416), stdev = 0.194
  CI (99.9%): [5.672, 12.738] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:53
# Fork: 1 of 1
# Warmup Iteration   1: 2.741 ops/ms
# Warmup Iteration   2: 7.193 ops/ms
# Warmup Iteration   3: 7.460 ops/ms
Iteration   1: 7.656 ops/ms
Iteration   2: 7.686 ops/ms
Iteration   3: 7.782 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.708 ±(99.9%) 1.203 ops/ms [Average]
  (min, avg, max) = (7.656, 7.708, 7.782), stdev = 0.066
  CI (99.9%): [6.505, 8.910] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 10.751 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 3.749 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.664 ±(99.9%) 0.003 ms/op
Iteration   1: 3.581 ±(99.9%) 0.005 ms/op
Iteration   2: 3.547 ±(99.9%) 0.006 ms/op
Iteration   3: 3.489 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.539 ±(99.9%) 0.852 ms/op [Average]
  (min, avg, max) = (3.489, 3.539, 3.581), stdev = 0.047
  CI (99.9%): [2.687, 4.391] (assumes normal distribution)


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
# Warmup Iteration   1: 8.747 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.754 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.391 ±(99.9%) 0.006 ms/op
Iteration   1: 3.342 ±(99.9%) 0.005 ms/op
Iteration   2: 3.377 ±(99.9%) 0.005 ms/op
Iteration   3: 3.372 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.364 ±(99.9%) 0.348 ms/op [Average]
  (min, avg, max) = (3.342, 3.364, 3.377), stdev = 0.019
  CI (99.9%): [3.016, 3.711] (assumes normal distribution)


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
# Warmup Iteration   1: 10.893 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.806 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.557 ±(99.9%) 0.003 ms/op
Iteration   1: 3.578 ±(99.9%) 0.006 ms/op
Iteration   2: 3.455 ±(99.9%) 0.003 ms/op
Iteration   3: 3.413 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.482 ±(99.9%) 1.568 ms/op [Average]
  (min, avg, max) = (3.413, 3.482, 3.578), stdev = 0.086
  CI (99.9%): [1.914, 5.050] (assumes normal distribution)


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
# Warmup Iteration   1: 11.402 ±(99.9%) 0.059 ms/op
# Warmup Iteration   2: 4.509 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.171 ±(99.9%) 0.009 ms/op
Iteration   1: 4.180 ±(99.9%) 0.007 ms/op
Iteration   2: 4.104 ±(99.9%) 0.008 ms/op
Iteration   3: 4.120 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.135 ±(99.9%) 0.729 ms/op [Average]
  (min, avg, max) = (4.104, 4.135, 4.180), stdev = 0.040
  CI (99.9%): [3.405, 4.864] (assumes normal distribution)


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
# Warmup Iteration   1: 10.984 ±(99.9%) 0.128 ms/op
# Warmup Iteration   2: 4.171 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 3.807 ±(99.9%) 0.016 ms/op
Iteration   1: 3.514 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.913 ms/op
                 createUser·p0.50:   3.387 ms/op
                 createUser·p0.90:   3.973 ms/op
                 createUser·p0.95:   4.284 ms/op
                 createUser·p0.99:   6.603 ms/op
                 createUser·p0.999:  19.726 ms/op
                 createUser·p0.9999: 23.134 ms/op
                 createUser·p1.00:   23.888 ms/op

Iteration   2: 3.634 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.118 ms/op
                 createUser·p0.50:   3.469 ms/op
                 createUser·p0.90:   4.178 ms/op
                 createUser·p0.95:   4.514 ms/op
                 createUser·p0.99:   7.471 ms/op
                 createUser·p0.999:  21.988 ms/op
                 createUser·p0.9999: 25.566 ms/op
                 createUser·p1.00:   26.477 ms/op

Iteration   3: 3.552 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.198 ms/op
                 createUser·p0.50:   3.363 ms/op
                 createUser·p0.90:   4.010 ms/op
                 createUser·p0.95:   4.342 ms/op
                 createUser·p0.99:   7.447 ms/op
                 createUser·p0.999:  21.815 ms/op
                 createUser·p0.9999: 27.951 ms/op
                 createUser·p1.00:   28.443 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 268980
  mean =      3.566 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3240 
    [ 2.500,  5.000) = 257628 
    [ 5.000,  7.500) = 6023 
    [ 7.500, 10.000) = 1404 
    [10.000, 12.500) = 276 
    [12.500, 15.000) = 62 
    [15.000, 17.500) = 26 
    [17.500, 20.000) = 27 
    [20.000, 22.500) = 131 
    [22.500, 25.000) = 106 
    [25.000, 27.500) = 44 

  Percentiles, ms/op:
      p(0.0000) =      0.913 ms/op
     p(50.0000) =      3.400 ms/op
     p(90.0000) =      4.059 ms/op
     p(95.0000) =      4.391 ms/op
     p(99.0000) =      7.184 ms/op
     p(99.9000) =     21.168 ms/op
     p(99.9900) =     26.578 ms/op
     p(99.9990) =     28.297 ms/op
     p(99.9999) =     28.443 ms/op
    p(100.0000) =     28.443 ms/op


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
# Warmup Iteration   1: 10.287 ±(99.9%) 0.135 ms/op
# Warmup Iteration   2: 3.721 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.475 ±(99.9%) 0.009 ms/op
Iteration   1: 3.372 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.128 ms/op
                 existUser·p0.50:   3.297 ms/op
                 existUser·p0.90:   3.719 ms/op
                 existUser·p0.95:   4.088 ms/op
                 existUser·p0.99:   6.324 ms/op
                 existUser·p0.999:  19.110 ms/op
                 existUser·p0.9999: 22.594 ms/op
                 existUser·p1.00:   23.233 ms/op

Iteration   2: 3.439 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.231 ms/op
                 existUser·p0.50:   3.310 ms/op
                 existUser·p0.90:   3.846 ms/op
                 existUser·p0.95:   4.383 ms/op
                 existUser·p0.99:   6.668 ms/op
                 existUser·p0.999:  21.070 ms/op
                 existUser·p0.9999: 25.950 ms/op
                 existUser·p1.00:   26.903 ms/op

Iteration   3: 3.379 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.552 ms/op
                 existUser·p0.50:   3.301 ms/op
                 existUser·p0.90:   3.764 ms/op
                 existUser·p0.95:   4.190 ms/op
                 existUser·p0.99:   6.201 ms/op
                 existUser·p0.999:  14.206 ms/op
                 existUser·p0.9999: 26.965 ms/op
                 existUser·p1.00:   27.591 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 282502
  mean =      3.397 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11879 
    [ 2.500,  5.000) = 262082 
    [ 5.000,  7.500) = 7428 
    [ 7.500, 10.000) = 559 
    [10.000, 12.500) = 142 
    [12.500, 15.000) = 82 
    [15.000, 17.500) = 21 
    [17.500, 20.000) = 28 
    [20.000, 22.500) = 149 
    [22.500, 25.000) = 78 
    [25.000, 27.500) = 51 

  Percentiles, ms/op:
      p(0.0000) =      1.128 ms/op
     p(50.0000) =      3.301 ms/op
     p(90.0000) =      3.772 ms/op
     p(95.0000) =      4.202 ms/op
     p(99.0000) =      6.398 ms/op
     p(99.9000) =     19.824 ms/op
     p(99.9900) =     26.149 ms/op
     p(99.9990) =     27.531 ms/op
     p(99.9999) =     27.591 ms/op
    p(100.0000) =     27.591 ms/op


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
# Warmup Iteration   1: 9.422 ±(99.9%) 0.128 ms/op
# Warmup Iteration   2: 3.799 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.532 ±(99.9%) 0.011 ms/op
Iteration   1: 3.609 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   0.714 ms/op
                 getUser·p0.50:   3.338 ms/op
                 getUser·p0.90:   4.059 ms/op
                 getUser·p0.95:   5.759 ms/op
                 getUser·p0.99:   7.471 ms/op
                 getUser·p0.999:  17.695 ms/op
                 getUser·p0.9999: 20.030 ms/op
                 getUser·p1.00:   23.101 ms/op

Iteration   2: 3.484 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.524 ms/op
                 getUser·p0.50:   3.346 ms/op
                 getUser·p0.90:   3.871 ms/op
                 getUser·p0.95:   4.129 ms/op
                 getUser·p0.99:   6.865 ms/op
                 getUser·p0.999:  20.742 ms/op
                 getUser·p0.9999: 23.443 ms/op
                 getUser·p1.00:   24.216 ms/op

Iteration   3: 3.472 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.319 ms/op
                 getUser·p0.50:   3.334 ms/op
                 getUser·p0.90:   3.826 ms/op
                 getUser·p0.95:   4.088 ms/op
                 getUser·p0.99:   6.562 ms/op
                 getUser·p0.999:  18.765 ms/op
                 getUser·p0.9999: 24.241 ms/op
                 getUser·p1.00:   26.706 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 272590
  mean =      3.520 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4498 
    [ 2.500,  5.000) = 257591 
    [ 5.000,  7.500) = 8675 
    [ 7.500, 10.000) = 1134 
    [10.000, 12.500) = 261 
    [12.500, 15.000) = 64 
    [15.000, 17.500) = 60 
    [17.500, 20.000) = 114 
    [20.000, 22.500) = 113 
    [22.500, 25.000) = 76 
    [25.000, 27.500) = 4 

  Percentiles, ms/op:
      p(0.0000) =      0.714 ms/op
     p(50.0000) =      3.342 ms/op
     p(90.0000) =      3.899 ms/op
     p(95.0000) =      4.358 ms/op
     p(99.0000) =      7.168 ms/op
     p(99.9000) =     18.252 ms/op
     p(99.9900) =     23.748 ms/op
     p(99.9990) =     25.336 ms/op
     p(99.9999) =     26.706 ms/op
    p(100.0000) =     26.706 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 10.911 ±(99.9%) 0.164 ms/op
# Warmup Iteration   2: 4.526 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.212 ±(99.9%) 0.012 ms/op
Iteration   1: 4.321 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.565 ms/op
                 listUser·p0.50:   4.145 ms/op
                 listUser·p0.90:   4.792 ms/op
                 listUser·p0.95:   5.390 ms/op
                 listUser·p0.99:   8.208 ms/op
                 listUser·p0.999:  21.365 ms/op
                 listUser·p0.9999: 24.262 ms/op
                 listUser·p1.00:   24.642 ms/op

Iteration   2: 4.127 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.204 ms/op
                 listUser·p0.50:   4.002 ms/op
                 listUser·p0.90:   4.506 ms/op
                 listUser·p0.95:   4.776 ms/op
                 listUser·p0.99:   7.504 ms/op
                 listUser·p0.999:  15.032 ms/op
                 listUser·p0.9999: 17.564 ms/op
                 listUser·p1.00:   18.416 ms/op

Iteration   3: 4.184 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.473 ms/op
                 listUser·p0.50:   3.969 ms/op
                 listUser·p0.90:   4.653 ms/op
                 listUser·p0.95:   5.071 ms/op
                 listUser·p0.99:   8.880 ms/op
                 listUser·p0.999:  15.630 ms/op
                 listUser·p0.9999: 29.461 ms/op
                 listUser·p1.00:   32.113 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 227880
  mean =      4.209 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 82 
    [ 2.500,  5.000) = 215638 
    [ 5.000,  7.500) = 8837 
    [ 7.500, 10.000) = 2401 
    [10.000, 12.500) = 296 
    [12.500, 15.000) = 262 
    [15.000, 17.500) = 171 
    [17.500, 20.000) = 72 
    [20.000, 22.500) = 44 
    [22.500, 25.000) = 56 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 17 
    [30.000, 32.500) = 4 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.473 ms/op
     p(50.0000) =      4.039 ms/op
     p(90.0000) =      4.653 ms/op
     p(95.0000) =      5.054 ms/op
     p(99.0000) =      8.167 ms/op
     p(99.9000) =     16.764 ms/op
     p(99.9900) =     24.642 ms/op
     p(99.9990) =     31.772 ms/op
     p(99.9999) =     32.113 ms/op
    p(100.0000) =     32.113 ms/op


# Run complete. Total time: 00:13:13

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.028 ± 4.621  ops/ms
ClientPb.existUser                       thrpt       3   9.508 ± 0.773  ops/ms
ClientPb.getUser                         thrpt       3   9.205 ± 3.533  ops/ms
ClientPb.listUser                        thrpt       3   7.708 ± 1.203  ops/ms
ClientPb.createUser                       avgt       3   3.539 ± 0.852   ms/op
ClientPb.existUser                        avgt       3   3.364 ± 0.348   ms/op
ClientPb.getUser                          avgt       3   3.482 ± 1.568   ms/op
ClientPb.listUser                         avgt       3   4.135 ± 0.729   ms/op
ClientPb.createUser                     sample  268980   3.566 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.913           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.400           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.059           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.391           ms/op
ClientPb.createUser:createUser·p0.99    sample           7.184           ms/op
ClientPb.createUser:createUser·p0.999   sample          21.168           ms/op
ClientPb.createUser:createUser·p0.9999  sample          26.578           ms/op
ClientPb.createUser:createUser·p1.00    sample          28.443           ms/op
ClientPb.existUser                      sample  282502   3.397 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.128           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.301           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.772           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.202           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.398           ms/op
ClientPb.existUser:existUser·p0.999     sample          19.824           ms/op
ClientPb.existUser:existUser·p0.9999    sample          26.149           ms/op
ClientPb.existUser:existUser·p1.00      sample          27.591           ms/op
ClientPb.getUser                        sample  272590   3.520 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.714           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.342           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.899           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.358           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.168           ms/op
ClientPb.getUser:getUser·p0.999         sample          18.252           ms/op
ClientPb.getUser:getUser·p0.9999        sample          23.748           ms/op
ClientPb.getUser:getUser·p1.00          sample          26.706           ms/op
ClientPb.listUser                       sample  227880   4.209 ± 0.007   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.473           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.039           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.653           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.054           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.167           ms/op
ClientPb.listUser:listUser·p0.999       sample          16.764           ms/op
ClientPb.listUser:listUser·p0.9999      sample          24.642           ms/op
ClientPb.listUser:listUser·p1.00        sample          32.113           ms/op
