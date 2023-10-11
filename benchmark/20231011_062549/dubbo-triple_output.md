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
# Warmup Iteration   1: 2.225 ops/ms
# Warmup Iteration   2: 5.371 ops/ms
# Warmup Iteration   3: 8.412 ops/ms
Iteration   1: 9.294 ops/ms
Iteration   2: 9.236 ops/ms
Iteration   3: 9.379 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.303 ±(99.9%) 1.309 ops/ms [Average]
  (min, avg, max) = (9.236, 9.303, 9.379), stdev = 0.072
  CI (99.9%): [7.994, 10.612] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:07
# Fork: 1 of 1
# Warmup Iteration   1: 3.132 ops/ms
# Warmup Iteration   2: 8.806 ops/ms
# Warmup Iteration   3: 9.199 ops/ms
Iteration   1: 9.552 ops/ms
Iteration   2: 9.477 ops/ms
Iteration   3: 9.639 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.556 ±(99.9%) 1.480 ops/ms [Average]
  (min, avg, max) = (9.477, 9.556, 9.639), stdev = 0.081
  CI (99.9%): [8.075, 11.036] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.124 ops/ms
# Warmup Iteration   2: 8.004 ops/ms
# Warmup Iteration   3: 9.027 ops/ms
Iteration   1: 9.221 ops/ms
Iteration   2: 9.335 ops/ms
Iteration   3: 9.408 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.322 ±(99.9%) 1.719 ops/ms [Average]
  (min, avg, max) = (9.221, 9.322, 9.408), stdev = 0.094
  CI (99.9%): [7.603, 11.041] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 2.878 ops/ms
# Warmup Iteration   2: 7.115 ops/ms
# Warmup Iteration   3: 7.616 ops/ms
Iteration   1: 7.913 ops/ms
Iteration   2: 7.685 ops/ms
Iteration   3: 7.726 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.775 ±(99.9%) 2.216 ops/ms [Average]
  (min, avg, max) = (7.685, 7.775, 7.913), stdev = 0.121
  CI (99.9%): [5.559, 9.991] (assumes normal distribution)


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
# Warmup Iteration   1: 9.394 ±(99.9%) 0.055 ms/op
# Warmup Iteration   2: 3.764 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.547 ±(99.9%) 0.004 ms/op
Iteration   1: 3.497 ±(99.9%) 0.003 ms/op
Iteration   2: 3.349 ±(99.9%) 0.009 ms/op
Iteration   3: 3.470 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.439 ±(99.9%) 1.434 ms/op [Average]
  (min, avg, max) = (3.349, 3.439, 3.497), stdev = 0.079
  CI (99.9%): [2.005, 4.873] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 8.881 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 3.561 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.400 ±(99.9%) 0.004 ms/op
Iteration   1: 3.386 ±(99.9%) 0.003 ms/op
Iteration   2: 3.284 ±(99.9%) 0.007 ms/op
Iteration   3: 3.316 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.329 ±(99.9%) 0.953 ms/op [Average]
  (min, avg, max) = (3.284, 3.329, 3.386), stdev = 0.052
  CI (99.9%): [2.375, 4.282] (assumes normal distribution)


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
# Warmup Iteration   1: 9.424 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 3.754 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.585 ±(99.9%) 0.003 ms/op
Iteration   1: 3.472 ±(99.9%) 0.005 ms/op
Iteration   2: 3.449 ±(99.9%) 0.005 ms/op
Iteration   3: 3.484 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.468 ±(99.9%) 0.319 ms/op [Average]
  (min, avg, max) = (3.449, 3.468, 3.484), stdev = 0.017
  CI (99.9%): [3.149, 3.787] (assumes normal distribution)


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
# Warmup Iteration   1: 11.874 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 4.647 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.291 ±(99.9%) 0.006 ms/op
Iteration   1: 4.161 ±(99.9%) 0.005 ms/op
Iteration   2: 4.084 ±(99.9%) 0.006 ms/op
Iteration   3: 4.079 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.108 ±(99.9%) 0.833 ms/op [Average]
  (min, avg, max) = (4.079, 4.108, 4.161), stdev = 0.046
  CI (99.9%): [3.275, 4.942] (assumes normal distribution)


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
# Warmup Iteration   1: 9.177 ±(99.9%) 0.113 ms/op
# Warmup Iteration   2: 3.970 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.559 ±(99.9%) 0.010 ms/op
Iteration   1: 3.472 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.778 ms/op
                 createUser·p0.50:   3.330 ms/op
                 createUser·p0.90:   3.985 ms/op
                 createUser·p0.95:   4.268 ms/op
                 createUser·p0.99:   6.513 ms/op
                 createUser·p0.999:  17.947 ms/op
                 createUser·p0.9999: 21.489 ms/op
                 createUser·p1.00:   23.855 ms/op

Iteration   2: 3.469 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.382 ms/op
                 createUser·p0.50:   3.355 ms/op
                 createUser·p0.90:   4.018 ms/op
                 createUser·p0.95:   4.243 ms/op
                 createUser·p0.99:   5.571 ms/op
                 createUser·p0.999:  20.374 ms/op
                 createUser·p0.9999: 22.537 ms/op
                 createUser·p1.00:   23.593 ms/op

Iteration   3: 3.462 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.188 ms/op
                 createUser·p0.50:   3.346 ms/op
                 createUser·p0.90:   4.002 ms/op
                 createUser·p0.95:   4.227 ms/op
                 createUser·p0.99:   5.366 ms/op
                 createUser·p0.999:  17.023 ms/op
                 createUser·p0.9999: 25.944 ms/op
                 createUser·p1.00:   27.034 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 276887
  mean =      3.468 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7679 
    [ 2.500,  5.000) = 264476 
    [ 5.000,  7.500) = 3776 
    [ 7.500, 10.000) = 401 
    [10.000, 12.500) = 260 
    [12.500, 15.000) = 3 
    [15.000, 17.500) = 27 
    [17.500, 20.000) = 63 
    [20.000, 22.500) = 128 
    [22.500, 25.000) = 46 
    [25.000, 27.500) = 28 

  Percentiles, ms/op:
      p(0.0000) =      0.778 ms/op
     p(50.0000) =      3.346 ms/op
     p(90.0000) =      4.002 ms/op
     p(95.0000) =      4.243 ms/op
     p(99.0000) =      5.816 ms/op
     p(99.9000) =     17.269 ms/op
     p(99.9900) =     25.194 ms/op
     p(99.9990) =     26.910 ms/op
     p(99.9999) =     27.034 ms/op
    p(100.0000) =     27.034 ms/op


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
# Warmup Iteration   1: 9.329 ±(99.9%) 0.124 ms/op
# Warmup Iteration   2: 3.618 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.521 ±(99.9%) 0.009 ms/op
Iteration   1: 3.379 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.608 ms/op
                 existUser·p0.50:   3.269 ms/op
                 existUser·p0.90:   3.781 ms/op
                 existUser·p0.95:   4.116 ms/op
                 existUser·p0.99:   5.743 ms/op
                 existUser·p0.999:  17.924 ms/op
                 existUser·p0.9999: 20.270 ms/op
                 existUser·p1.00:   21.234 ms/op

Iteration   2: 3.345 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.163 ms/op
                 existUser·p0.50:   3.293 ms/op
                 existUser·p0.90:   3.666 ms/op
                 existUser·p0.95:   3.908 ms/op
                 existUser·p0.99:   5.362 ms/op
                 existUser·p0.999:  18.448 ms/op
                 existUser·p0.9999: 22.708 ms/op
                 existUser·p1.00:   23.265 ms/op

Iteration   3: 3.462 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.047 ms/op
                 existUser·p0.50:   3.375 ms/op
                 existUser·p0.90:   3.924 ms/op
                 existUser·p0.95:   4.235 ms/op
                 existUser·p0.99:   5.612 ms/op
                 existUser·p0.999:  17.088 ms/op
                 existUser·p0.9999: 23.658 ms/op
                 existUser·p1.00:   24.019 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 282575
  mean =      3.395 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9573 
    [ 2.500,  5.000) = 268304 
    [ 5.000,  7.500) = 3720 
    [ 7.500, 10.000) = 448 
    [10.000, 12.500) = 189 
    [12.500, 15.000) = 47 
    [15.000, 17.500) = 18 
    [17.500, 20.000) = 131 
    [20.000, 22.500) = 82 
    [22.500, 25.000) = 63 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.047 ms/op
     p(50.0000) =      3.314 ms/op
     p(90.0000) =      3.793 ms/op
     p(95.0000) =      4.108 ms/op
     p(99.0000) =      5.661 ms/op
     p(99.9000) =     17.152 ms/op
     p(99.9900) =     23.396 ms/op
     p(99.9990) =     23.959 ms/op
     p(99.9999) =     24.019 ms/op
    p(100.0000) =     24.019 ms/op


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
# Warmup Iteration   1: 8.667 ±(99.9%) 0.124 ms/op
# Warmup Iteration   2: 3.796 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.639 ±(99.9%) 0.012 ms/op
Iteration   1: 3.447 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.894 ms/op
                 getUser·p0.50:   3.334 ms/op
                 getUser·p0.90:   3.903 ms/op
                 getUser·p0.95:   4.149 ms/op
                 getUser·p0.99:   5.743 ms/op
                 getUser·p0.999:  17.957 ms/op
                 getUser·p0.9999: 20.953 ms/op
                 getUser·p1.00:   22.053 ms/op

Iteration   2: 3.578 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.083 ms/op
                 getUser·p0.50:   3.494 ms/op
                 getUser·p0.90:   4.039 ms/op
                 getUser·p0.95:   4.235 ms/op
                 getUser·p0.99:   5.759 ms/op
                 getUser·p0.999:  19.595 ms/op
                 getUser·p0.9999: 22.677 ms/op
                 getUser·p1.00:   22.938 ms/op

Iteration   3: 3.529 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.636 ms/op
                 getUser·p0.50:   3.408 ms/op
                 getUser·p0.90:   3.981 ms/op
                 getUser·p0.95:   4.301 ms/op
                 getUser·p0.99:   6.210 ms/op
                 getUser·p0.999:  16.274 ms/op
                 getUser·p0.9999: 26.507 ms/op
                 getUser·p1.00:   27.361 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 272798
  mean =      3.517 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5333 
    [ 2.500,  5.000) = 262208 
    [ 5.000,  7.500) = 4388 
    [ 7.500, 10.000) = 476 
    [10.000, 12.500) = 48 
    [12.500, 15.000) = 51 
    [15.000, 17.500) = 31 
    [17.500, 20.000) = 79 
    [20.000, 22.500) = 108 
    [22.500, 25.000) = 38 
    [25.000, 27.500) = 38 

  Percentiles, ms/op:
      p(0.0000) =      0.894 ms/op
     p(50.0000) =      3.404 ms/op
     p(90.0000) =      3.985 ms/op
     p(95.0000) =      4.219 ms/op
     p(99.0000) =      5.865 ms/op
     p(99.9000) =     16.633 ms/op
     p(99.9900) =     25.714 ms/op
     p(99.9990) =     27.248 ms/op
     p(99.9999) =     27.361 ms/op
    p(100.0000) =     27.361 ms/op


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
# Warmup Iteration   1: 10.514 ±(99.9%) 0.137 ms/op
# Warmup Iteration   2: 4.441 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.272 ±(99.9%) 0.013 ms/op
Iteration   1: 4.247 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.470 ms/op
                 listUser·p0.50:   4.100 ms/op
                 listUser·p0.90:   4.760 ms/op
                 listUser·p0.95:   5.128 ms/op
                 listUser·p0.99:   7.348 ms/op
                 listUser·p0.999:  20.578 ms/op
                 listUser·p0.9999: 27.868 ms/op
                 listUser·p1.00:   28.148 ms/op

Iteration   2: 4.152 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.101 ms/op
                 listUser·p0.50:   4.071 ms/op
                 listUser·p0.90:   4.497 ms/op
                 listUser·p0.95:   4.710 ms/op
                 listUser·p0.99:   6.865 ms/op
                 listUser·p0.999:  15.807 ms/op
                 listUser·p0.9999: 18.088 ms/op
                 listUser·p1.00:   18.186 ms/op

Iteration   3: 4.201 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.195 ms/op
                 listUser·p0.50:   3.985 ms/op
                 listUser·p0.90:   4.727 ms/op
                 listUser·p0.95:   4.981 ms/op
                 listUser·p0.99:   7.447 ms/op
                 listUser·p0.999:  15.516 ms/op
                 listUser·p0.9999: 20.218 ms/op
                 listUser·p1.00:   20.283 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 228523
  mean =      4.200 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 39 
    [ 2.500,  5.000) = 217893 
    [ 5.000,  7.500) = 8584 
    [ 7.500, 10.000) = 1087 
    [10.000, 12.500) = 338 
    [12.500, 15.000) = 228 
    [15.000, 17.500) = 179 
    [17.500, 20.000) = 75 
    [20.000, 22.500) = 60 
    [22.500, 25.000) = 9 
    [25.000, 27.500) = 23 

  Percentiles, ms/op:
      p(0.0000) =      1.470 ms/op
     p(50.0000) =      4.059 ms/op
     p(90.0000) =      4.669 ms/op
     p(95.0000) =      4.956 ms/op
     p(99.0000) =      7.283 ms/op
     p(99.9000) =     16.195 ms/op
     p(99.9900) =     25.986 ms/op
     p(99.9990) =     28.106 ms/op
     p(99.9999) =     28.148 ms/op
    p(100.0000) =     28.148 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.303 ± 1.309  ops/ms
ClientPb.existUser                       thrpt       3   9.556 ± 1.480  ops/ms
ClientPb.getUser                         thrpt       3   9.322 ± 1.719  ops/ms
ClientPb.listUser                        thrpt       3   7.775 ± 2.216  ops/ms
ClientPb.createUser                       avgt       3   3.439 ± 1.434   ms/op
ClientPb.existUser                        avgt       3   3.329 ± 0.953   ms/op
ClientPb.getUser                          avgt       3   3.468 ± 0.319   ms/op
ClientPb.listUser                         avgt       3   4.108 ± 0.833   ms/op
ClientPb.createUser                     sample  276887   3.468 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.778           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.346           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.002           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.243           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.816           ms/op
ClientPb.createUser:createUser·p0.999   sample          17.269           ms/op
ClientPb.createUser:createUser·p0.9999  sample          25.194           ms/op
ClientPb.createUser:createUser·p1.00    sample          27.034           ms/op
ClientPb.existUser                      sample  282575   3.395 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.047           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.314           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.793           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.108           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.661           ms/op
ClientPb.existUser:existUser·p0.999     sample          17.152           ms/op
ClientPb.existUser:existUser·p0.9999    sample          23.396           ms/op
ClientPb.existUser:existUser·p1.00      sample          24.019           ms/op
ClientPb.getUser                        sample  272798   3.517 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.894           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.404           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.985           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.219           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.865           ms/op
ClientPb.getUser:getUser·p0.999         sample          16.633           ms/op
ClientPb.getUser:getUser·p0.9999        sample          25.714           ms/op
ClientPb.getUser:getUser·p1.00          sample          27.361           ms/op
ClientPb.listUser                       sample  228523   4.200 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.470           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.059           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.669           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.956           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.283           ms/op
ClientPb.listUser:listUser·p0.999       sample          16.195           ms/op
ClientPb.listUser:listUser·p0.9999      sample          25.986           ms/op
ClientPb.listUser:listUser·p1.00        sample          28.148           ms/op
