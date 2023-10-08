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
# Warmup Iteration   1: 2.110 ops/ms
# Warmup Iteration   2: 4.967 ops/ms
# Warmup Iteration   3: 8.437 ops/ms
Iteration   1: 8.861 ops/ms
Iteration   2: 8.973 ops/ms
Iteration   3: 9.373 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.069 ±(99.9%) 4.908 ops/ms [Average]
  (min, avg, max) = (8.861, 9.069, 9.373), stdev = 0.269
  CI (99.9%): [4.161, 13.976] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:10
# Fork: 1 of 1
# Warmup Iteration   1: 2.797 ops/ms
# Warmup Iteration   2: 8.503 ops/ms
# Warmup Iteration   3: 9.246 ops/ms
Iteration   1: 9.387 ops/ms
Iteration   2: 9.437 ops/ms
Iteration   3: 9.611 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.478 ±(99.9%) 2.142 ops/ms [Average]
  (min, avg, max) = (9.387, 9.478, 9.611), stdev = 0.117
  CI (99.9%): [7.337, 11.620] (assumes normal distribution)


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
# Warmup Iteration   1: 2.829 ops/ms
# Warmup Iteration   2: 8.320 ops/ms
# Warmup Iteration   3: 8.791 ops/ms
Iteration   1: 9.055 ops/ms
Iteration   2: 9.186 ops/ms
Iteration   3: 8.895 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.045 ±(99.9%) 2.659 ops/ms [Average]
  (min, avg, max) = (8.895, 9.045, 9.186), stdev = 0.146
  CI (99.9%): [6.386, 11.704] (assumes normal distribution)


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
# Warmup Iteration   1: 2.445 ops/ms
# Warmup Iteration   2: 6.539 ops/ms
# Warmup Iteration   3: 7.188 ops/ms
Iteration   1: 7.301 ops/ms
Iteration   2: 7.336 ops/ms
Iteration   3: 7.587 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.408 ±(99.9%) 2.845 ops/ms [Average]
  (min, avg, max) = (7.301, 7.408, 7.587), stdev = 0.156
  CI (99.9%): [4.563, 10.253] (assumes normal distribution)


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
# Warmup Iteration   1: 11.609 ±(99.9%) 0.066 ms/op
# Warmup Iteration   2: 4.313 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.763 ±(99.9%) 0.003 ms/op
Iteration   1: 3.671 ±(99.9%) 0.004 ms/op
Iteration   2: 3.573 ±(99.9%) 0.005 ms/op
Iteration   3: 3.632 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.625 ±(99.9%) 0.904 ms/op [Average]
  (min, avg, max) = (3.573, 3.625, 3.671), stdev = 0.050
  CI (99.9%): [2.722, 4.529] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 8.227 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 3.632 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.461 ±(99.9%) 0.003 ms/op
Iteration   1: 3.513 ±(99.9%) 0.006 ms/op
Iteration   2: 3.421 ±(99.9%) 0.004 ms/op
Iteration   3: 3.557 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.497 ±(99.9%) 1.265 ms/op [Average]
  (min, avg, max) = (3.421, 3.497, 3.557), stdev = 0.069
  CI (99.9%): [2.232, 4.762] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 11.391 ±(99.9%) 0.054 ms/op
# Warmup Iteration   2: 3.915 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.664 ±(99.9%) 0.004 ms/op
Iteration   1: 3.555 ±(99.9%) 0.004 ms/op
Iteration   2: 3.605 ±(99.9%) 0.004 ms/op
Iteration   3: 3.597 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.586 ±(99.9%) 0.491 ms/op [Average]
  (min, avg, max) = (3.555, 3.586, 3.605), stdev = 0.027
  CI (99.9%): [3.095, 4.076] (assumes normal distribution)


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
# Warmup Iteration   1: 11.853 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 4.804 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.349 ±(99.9%) 0.005 ms/op
Iteration   1: 4.291 ±(99.9%) 0.007 ms/op
Iteration   2: 4.225 ±(99.9%) 0.008 ms/op
Iteration   3: 4.233 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.250 ±(99.9%) 0.655 ms/op [Average]
  (min, avg, max) = (4.225, 4.250, 4.291), stdev = 0.036
  CI (99.9%): [3.594, 4.905] (assumes normal distribution)


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
# Warmup Iteration   1: 11.769 ±(99.9%) 0.162 ms/op
# Warmup Iteration   2: 4.255 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 4.025 ±(99.9%) 0.018 ms/op
Iteration   1: 3.670 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.522 ms/op
                 createUser·p0.50:   3.547 ms/op
                 createUser·p0.90:   4.166 ms/op
                 createUser·p0.95:   4.571 ms/op
                 createUser·p0.99:   7.913 ms/op
                 createUser·p0.999:  18.833 ms/op
                 createUser·p0.9999: 21.398 ms/op
                 createUser·p1.00:   26.345 ms/op

Iteration   2: 3.551 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.849 ms/op
                 createUser·p0.50:   3.437 ms/op
                 createUser·p0.90:   3.899 ms/op
                 createUser·p0.95:   4.293 ms/op
                 createUser·p0.99:   7.234 ms/op
                 createUser·p0.999:  20.026 ms/op
                 createUser·p0.9999: 22.971 ms/op
                 createUser·p1.00:   24.379 ms/op

Iteration   3: 3.614 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.192 ms/op
                 createUser·p0.50:   3.445 ms/op
                 createUser·p0.90:   3.985 ms/op
                 createUser·p0.95:   4.604 ms/op
                 createUser·p0.99:   7.856 ms/op
                 createUser·p0.999:  21.955 ms/op
                 createUser·p0.9999: 25.854 ms/op
                 createUser·p1.00:   26.247 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 265593
  mean =      3.611 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4443 
    [ 2.500,  5.000) = 251710 
    [ 5.000,  7.500) = 6441 
    [ 7.500, 10.000) = 2147 
    [10.000, 12.500) = 300 
    [12.500, 15.000) = 126 
    [15.000, 17.500) = 44 
    [17.500, 20.000) = 125 
    [20.000, 22.500) = 174 
    [22.500, 25.000) = 51 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      1.192 ms/op
     p(50.0000) =      3.465 ms/op
     p(90.0000) =      4.026 ms/op
     p(95.0000) =      4.473 ms/op
     p(99.0000) =      7.725 ms/op
     p(99.9000) =     19.923 ms/op
     p(99.9900) =     25.428 ms/op
     p(99.9990) =     26.247 ms/op
     p(99.9999) =     26.345 ms/op
    p(100.0000) =     26.345 ms/op


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
# Warmup Iteration   1: 11.319 ±(99.9%) 0.140 ms/op
# Warmup Iteration   2: 3.760 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.451 ±(99.9%) 0.010 ms/op
Iteration   1: 3.409 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.632 ms/op
                 existUser·p0.50:   3.363 ms/op
                 existUser·p0.90:   3.703 ms/op
                 existUser·p0.95:   3.990 ms/op
                 existUser·p0.99:   6.154 ms/op
                 existUser·p0.999:  20.746 ms/op
                 existUser·p0.9999: 22.965 ms/op
                 existUser·p1.00:   24.576 ms/op

Iteration   2: 3.497 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.470 ms/op
                 existUser·p0.50:   3.322 ms/op
                 existUser·p0.90:   3.850 ms/op
                 existUser·p0.95:   4.391 ms/op
                 existUser·p0.99:   8.034 ms/op
                 existUser·p0.999:  19.349 ms/op
                 existUser·p0.9999: 24.538 ms/op
                 existUser·p1.00:   25.461 ms/op

Iteration   3: 3.539 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.505 ms/op
                 existUser·p0.50:   3.383 ms/op
                 existUser·p0.90:   4.030 ms/op
                 existUser·p0.95:   4.375 ms/op
                 existUser·p0.99:   6.980 ms/op
                 existUser·p0.999:  23.857 ms/op
                 existUser·p0.9999: 26.378 ms/op
                 existUser·p1.00:   27.394 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 275714
  mean =      3.481 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9354 
    [ 2.500,  5.000) = 258905 
    [ 5.000,  7.500) = 5255 
    [ 7.500, 10.000) = 1286 
    [10.000, 12.500) = 376 
    [12.500, 15.000) = 183 
    [15.000, 17.500) = 58 
    [17.500, 20.000) = 24 
    [20.000, 22.500) = 93 
    [22.500, 25.000) = 108 
    [25.000, 27.500) = 72 

  Percentiles, ms/op:
      p(0.0000) =      1.470 ms/op
     p(50.0000) =      3.359 ms/op
     p(90.0000) =      3.879 ms/op
     p(95.0000) =      4.260 ms/op
     p(99.0000) =      7.127 ms/op
     p(99.9000) =     19.857 ms/op
     p(99.9900) =     25.985 ms/op
     p(99.9990) =     26.949 ms/op
     p(99.9999) =     27.394 ms/op
    p(100.0000) =     27.394 ms/op


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
# Warmup Iteration   1: 11.908 ±(99.9%) 0.211 ms/op
# Warmup Iteration   2: 4.040 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.687 ±(99.9%) 0.012 ms/op
Iteration   1: 3.640 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.757 ms/op
                 getUser·p0.50:   3.461 ms/op
                 getUser·p0.90:   4.088 ms/op
                 getUser·p0.95:   4.661 ms/op
                 getUser·p0.99:   7.979 ms/op
                 getUser·p0.999:  19.276 ms/op
                 getUser·p0.9999: 22.191 ms/op
                 getUser·p1.00:   23.069 ms/op

Iteration   2: 3.577 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.087 ms/op
                 getUser·p0.50:   3.400 ms/op
                 getUser·p0.90:   3.916 ms/op
                 getUser·p0.95:   4.276 ms/op
                 getUser·p0.99:   7.799 ms/op
                 getUser·p0.999:  20.617 ms/op
                 getUser·p0.9999: 27.693 ms/op
                 getUser·p1.00:   29.229 ms/op

Iteration   3: 3.554 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.548 ms/op
                 getUser·p0.50:   3.441 ms/op
                 getUser·p0.90:   3.940 ms/op
                 getUser·p0.95:   4.166 ms/op
                 getUser·p0.99:   7.217 ms/op
                 getUser·p0.999:  20.712 ms/op
                 getUser·p0.9999: 23.626 ms/op
                 getUser·p1.00:   24.052 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 267051
  mean =      3.590 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2485 
    [ 2.500,  5.000) = 255418 
    [ 5.000,  7.500) = 5750 
    [ 7.500, 10.000) = 2498 
    [10.000, 12.500) = 464 
    [12.500, 15.000) = 55 
    [15.000, 17.500) = 45 
    [17.500, 20.000) = 85 
    [20.000, 22.500) = 145 
    [22.500, 25.000) = 87 
    [25.000, 27.500) = 9 

  Percentiles, ms/op:
      p(0.0000) =      1.087 ms/op
     p(50.0000) =      3.437 ms/op
     p(90.0000) =      3.973 ms/op
     p(95.0000) =      4.358 ms/op
     p(99.0000) =      7.741 ms/op
     p(99.9000) =     19.659 ms/op
     p(99.9900) =     23.855 ms/op
     p(99.9990) =     28.650 ms/op
     p(99.9999) =     29.229 ms/op
    p(100.0000) =     29.229 ms/op


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
# Warmup Iteration   1: 13.606 ±(99.9%) 0.183 ms/op
# Warmup Iteration   2: 4.934 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 4.499 ±(99.9%) 0.017 ms/op
Iteration   1: 4.614 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   1.589 ms/op
                 listUser·p0.50:   4.383 ms/op
                 listUser·p0.90:   5.136 ms/op
                 listUser·p0.95:   5.759 ms/op
                 listUser·p0.99:   9.716 ms/op
                 listUser·p0.999:  24.992 ms/op
                 listUser·p0.9999: 27.829 ms/op
                 listUser·p1.00:   50.201 ms/op

Iteration   2: 4.419 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   2.023 ms/op
                 listUser·p0.50:   4.235 ms/op
                 listUser·p0.90:   4.760 ms/op
                 listUser·p0.95:   5.292 ms/op
                 listUser·p0.99:   9.568 ms/op
                 listUser·p0.999:  17.367 ms/op
                 listUser·p0.9999: 18.645 ms/op
                 listUser·p1.00:   18.711 ms/op

Iteration   3: 4.742 ±(99.9%) 0.027 ms/op
                 listUser·p0.00:   2.384 ms/op
                 listUser·p0.50:   4.260 ms/op
                 listUser·p0.90:   5.067 ms/op
                 listUser·p0.95:   7.922 ms/op
                 listUser·p0.99:   16.204 ms/op
                 listUser·p0.999:  23.079 ms/op
                 listUser·p0.9999: 30.066 ms/op
                 listUser·p1.00:   31.228 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 209079
  mean =      4.588 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 188213 
    [ 5.000, 10.000) = 17510 
    [10.000, 15.000) = 2039 
    [15.000, 20.000) = 1024 
    [20.000, 25.000) = 201 
    [25.000, 30.000) = 84 
    [30.000, 35.000) = 7 
    [35.000, 40.000) = 0 
    [40.000, 45.000) = 0 
    [45.000, 50.000) = 0 
    [50.000, 55.000) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.589 ms/op
     p(50.0000) =      4.284 ms/op
     p(90.0000) =      4.997 ms/op
     p(95.0000) =      6.185 ms/op
     p(99.0000) =     12.435 ms/op
     p(99.9000) =     21.823 ms/op
     p(99.9900) =     27.552 ms/op
     p(99.9990) =     31.219 ms/op
     p(99.9999) =     50.201 ms/op
    p(100.0000) =     50.201 ms/op


# Run complete. Total time: 00:13:12

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.069 ± 4.908  ops/ms
ClientPb.existUser                       thrpt       3   9.478 ± 2.142  ops/ms
ClientPb.getUser                         thrpt       3   9.045 ± 2.659  ops/ms
ClientPb.listUser                        thrpt       3   7.408 ± 2.845  ops/ms
ClientPb.createUser                       avgt       3   3.625 ± 0.904   ms/op
ClientPb.existUser                        avgt       3   3.497 ± 1.265   ms/op
ClientPb.getUser                          avgt       3   3.586 ± 0.491   ms/op
ClientPb.listUser                         avgt       3   4.250 ± 0.655   ms/op
ClientPb.createUser                     sample  265593   3.611 ± 0.007   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.192           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.465           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.026           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.473           ms/op
ClientPb.createUser:createUser·p0.99    sample           7.725           ms/op
ClientPb.createUser:createUser·p0.999   sample          19.923           ms/op
ClientPb.createUser:createUser·p0.9999  sample          25.428           ms/op
ClientPb.createUser:createUser·p1.00    sample          26.345           ms/op
ClientPb.existUser                      sample  275714   3.481 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.470           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.359           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.879           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.260           ms/op
ClientPb.existUser:existUser·p0.99      sample           7.127           ms/op
ClientPb.existUser:existUser·p0.999     sample          19.857           ms/op
ClientPb.existUser:existUser·p0.9999    sample          25.985           ms/op
ClientPb.existUser:existUser·p1.00      sample          27.394           ms/op
ClientPb.getUser                        sample  267051   3.590 ± 0.007   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.087           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.437           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.973           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.358           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.741           ms/op
ClientPb.getUser:getUser·p0.999         sample          19.659           ms/op
ClientPb.getUser:getUser·p0.9999        sample          23.855           ms/op
ClientPb.getUser:getUser·p1.00          sample          29.229           ms/op
ClientPb.listUser                       sample  209079   4.588 ± 0.011   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.589           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.284           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.997           ms/op
ClientPb.listUser:listUser·p0.95        sample           6.185           ms/op
ClientPb.listUser:listUser·p0.99        sample          12.435           ms/op
ClientPb.listUser:listUser·p0.999       sample          21.823           ms/op
ClientPb.listUser:listUser·p0.9999      sample          27.552           ms/op
ClientPb.listUser:listUser·p1.00        sample          50.201           ms/op
