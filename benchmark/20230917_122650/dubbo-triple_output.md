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
# Warmup Iteration   1: 2.100 ops/ms
# Warmup Iteration   2: 5.195 ops/ms
# Warmup Iteration   3: 8.611 ops/ms
Iteration   1: 9.185 ops/ms
Iteration   2: 9.004 ops/ms
Iteration   3: 9.341 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.177 ±(99.9%) 3.074 ops/ms [Average]
  (min, avg, max) = (9.004, 9.177, 9.341), stdev = 0.169
  CI (99.9%): [6.102, 12.251] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:08
# Fork: 1 of 1
# Warmup Iteration   1: 2.851 ops/ms
# Warmup Iteration   2: 8.712 ops/ms
# Warmup Iteration   3: 9.585 ops/ms
Iteration   1: 9.728 ops/ms
Iteration   2: 10.027 ops/ms
Iteration   3: 9.682 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.813 ±(99.9%) 3.417 ops/ms [Average]
  (min, avg, max) = (9.682, 9.813, 10.027), stdev = 0.187
  CI (99.9%): [6.395, 13.230] (assumes normal distribution)


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
# Warmup Iteration   1: 3.153 ops/ms
# Warmup Iteration   2: 8.467 ops/ms
# Warmup Iteration   3: 9.126 ops/ms
Iteration   1: 9.239 ops/ms
Iteration   2: 9.326 ops/ms
Iteration   3: 9.482 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.349 ±(99.9%) 2.245 ops/ms [Average]
  (min, avg, max) = (9.239, 9.349, 9.482), stdev = 0.123
  CI (99.9%): [7.104, 11.595] (assumes normal distribution)


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
# Warmup Iteration   1: 2.693 ops/ms
# Warmup Iteration   2: 7.057 ops/ms
# Warmup Iteration   3: 7.488 ops/ms
Iteration   1: 7.796 ops/ms
Iteration   2: 7.890 ops/ms
Iteration   3: 7.754 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.814 ±(99.9%) 1.272 ops/ms [Average]
  (min, avg, max) = (7.754, 7.814, 7.890), stdev = 0.070
  CI (99.9%): [6.542, 9.085] (assumes normal distribution)


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
# Warmup Iteration   1: 9.952 ±(99.9%) 0.057 ms/op
# Warmup Iteration   2: 3.727 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.578 ±(99.9%) 0.003 ms/op
Iteration   1: 3.472 ±(99.9%) 0.004 ms/op
Iteration   2: 3.616 ±(99.9%) 0.003 ms/op
Iteration   3: 3.414 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.501 ±(99.9%) 1.900 ms/op [Average]
  (min, avg, max) = (3.414, 3.501, 3.616), stdev = 0.104
  CI (99.9%): [1.600, 5.401] (assumes normal distribution)


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
# Warmup Iteration   1: 9.373 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.538 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.338 ±(99.9%) 0.002 ms/op
Iteration   1: 3.301 ±(99.9%) 0.003 ms/op
Iteration   2: 3.244 ±(99.9%) 0.006 ms/op
Iteration   3: 3.273 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.273 ±(99.9%) 0.521 ms/op [Average]
  (min, avg, max) = (3.244, 3.273, 3.301), stdev = 0.029
  CI (99.9%): [2.752, 3.793] (assumes normal distribution)


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
# Warmup Iteration   1: 8.716 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 3.566 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.611 ±(99.9%) 0.003 ms/op
Iteration   1: 3.418 ±(99.9%) 0.003 ms/op
Iteration   2: 3.440 ±(99.9%) 0.004 ms/op
Iteration   3: 3.474 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.444 ±(99.9%) 0.509 ms/op [Average]
  (min, avg, max) = (3.418, 3.444, 3.474), stdev = 0.028
  CI (99.9%): [2.935, 3.954] (assumes normal distribution)


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
# Warmup Iteration   1: 9.635 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 4.300 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.081 ±(99.9%) 0.006 ms/op
Iteration   1: 4.080 ±(99.9%) 0.005 ms/op
Iteration   2: 4.081 ±(99.9%) 0.007 ms/op
Iteration   3: 4.058 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.073 ±(99.9%) 0.229 ms/op [Average]
  (min, avg, max) = (4.058, 4.073, 4.081), stdev = 0.013
  CI (99.9%): [3.844, 4.302] (assumes normal distribution)


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
# Warmup Iteration   1: 8.740 ±(99.9%) 0.107 ms/op
# Warmup Iteration   2: 3.858 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.516 ±(99.9%) 0.010 ms/op
Iteration   1: 3.475 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.569 ms/op
                 createUser·p0.50:   3.387 ms/op
                 createUser·p0.90:   3.977 ms/op
                 createUser·p0.95:   4.301 ms/op
                 createUser·p0.99:   5.612 ms/op
                 createUser·p0.999:  8.942 ms/op
                 createUser·p0.9999: 22.276 ms/op
                 createUser·p1.00:   22.577 ms/op

Iteration   2: 3.415 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.718 ms/op
                 createUser·p0.50:   3.297 ms/op
                 createUser·p0.90:   3.805 ms/op
                 createUser·p0.95:   4.084 ms/op
                 createUser·p0.99:   6.267 ms/op
                 createUser·p0.999:  22.839 ms/op
                 createUser·p0.9999: 27.665 ms/op
                 createUser·p1.00:   32.014 ms/op

Iteration   3: 3.447 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.247 ms/op
                 createUser·p0.50:   3.383 ms/op
                 createUser·p0.90:   3.879 ms/op
                 createUser·p0.95:   4.137 ms/op
                 createUser·p0.99:   5.368 ms/op
                 createUser·p0.999:  18.738 ms/op
                 createUser·p0.9999: 32.464 ms/op
                 createUser·p1.00:   32.932 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 278501
  mean =      3.445 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8761 
    [ 2.500,  5.000) = 265224 
    [ 5.000,  7.500) = 3456 
    [ 7.500, 10.000) = 539 
    [10.000, 12.500) = 165 
    [12.500, 15.000) = 16 
    [15.000, 17.500) = 84 
    [17.500, 20.000) = 22 
    [20.000, 22.500) = 87 
    [22.500, 25.000) = 78 
    [25.000, 27.500) = 27 
    [27.500, 30.000) = 7 
    [30.000, 32.500) = 27 
    [32.500, 35.000) = 8 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.247 ms/op
     p(50.0000) =      3.363 ms/op
     p(90.0000) =      3.891 ms/op
     p(95.0000) =      4.178 ms/op
     p(99.0000) =      5.734 ms/op
     p(99.9000) =     16.163 ms/op
     p(99.9900) =     31.187 ms/op
     p(99.9990) =     32.880 ms/op
     p(99.9999) =     32.932 ms/op
    p(100.0000) =     32.932 ms/op


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
# Warmup Iteration   1: 7.988 ±(99.9%) 0.121 ms/op
# Warmup Iteration   2: 3.594 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.380 ±(99.9%) 0.008 ms/op
Iteration   1: 3.359 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.311 ms/op
                 existUser·p0.50:   3.281 ms/op
                 existUser·p0.90:   3.834 ms/op
                 existUser·p0.95:   4.165 ms/op
                 existUser·p0.99:   5.335 ms/op
                 existUser·p0.999:  11.530 ms/op
                 existUser·p0.9999: 22.214 ms/op
                 existUser·p1.00:   23.986 ms/op

Iteration   2: 3.365 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.965 ms/op
                 existUser·p0.50:   3.273 ms/op
                 existUser·p0.90:   3.695 ms/op
                 existUser·p0.95:   4.059 ms/op
                 existUser·p0.99:   6.136 ms/op
                 existUser·p0.999:  21.335 ms/op
                 existUser·p0.9999: 24.086 ms/op
                 existUser·p1.00:   24.936 ms/op

Iteration   3: 3.405 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.237 ms/op
                 existUser·p0.50:   3.355 ms/op
                 existUser·p0.90:   3.785 ms/op
                 existUser·p0.95:   4.166 ms/op
                 existUser·p0.99:   5.661 ms/op
                 existUser·p0.999:  16.908 ms/op
                 existUser·p0.9999: 27.034 ms/op
                 existUser·p1.00:   27.787 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 284032
  mean =      3.376 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12557 
    [ 2.500,  5.000) = 266275 
    [ 5.000,  7.500) = 4172 
    [ 7.500, 10.000) = 411 
    [10.000, 12.500) = 313 
    [12.500, 15.000) = 41 
    [15.000, 17.500) = 20 
    [17.500, 20.000) = 10 
    [20.000, 22.500) = 97 
    [22.500, 25.000) = 103 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.965 ms/op
     p(50.0000) =      3.310 ms/op
     p(90.0000) =      3.777 ms/op
     p(95.0000) =      4.133 ms/op
     p(99.0000) =      5.661 ms/op
     p(99.9000) =     12.811 ms/op
     p(99.9900) =     26.378 ms/op
     p(99.9990) =     27.329 ms/op
     p(99.9999) =     27.787 ms/op
    p(100.0000) =     27.787 ms/op


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
# Warmup Iteration   1: 8.165 ±(99.9%) 0.105 ms/op
# Warmup Iteration   2: 3.686 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.500 ±(99.9%) 0.012 ms/op
Iteration   1: 3.475 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.698 ms/op
                 getUser·p0.50:   3.351 ms/op
                 getUser·p0.90:   3.924 ms/op
                 getUser·p0.95:   4.268 ms/op
                 getUser·p0.99:   6.128 ms/op
                 getUser·p0.999:  19.857 ms/op
                 getUser·p0.9999: 23.527 ms/op
                 getUser·p1.00:   24.019 ms/op

Iteration   2: 3.485 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.949 ms/op
                 getUser·p0.50:   3.375 ms/op
                 getUser·p0.90:   3.953 ms/op
                 getUser·p0.95:   4.190 ms/op
                 getUser·p0.99:   5.702 ms/op
                 getUser·p0.999:  10.682 ms/op
                 getUser·p0.9999: 25.330 ms/op
                 getUser·p1.00:   26.345 ms/op

Iteration   3: 3.468 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.280 ms/op
                 getUser·p0.50:   3.301 ms/op
                 getUser·p0.90:   3.846 ms/op
                 getUser·p0.95:   4.334 ms/op
                 getUser·p0.99:   6.791 ms/op
                 getUser·p0.999:  22.624 ms/op
                 getUser·p0.9999: 28.206 ms/op
                 getUser·p1.00:   28.705 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 276027
  mean =      3.476 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5751 
    [ 2.500,  5.000) = 263074 
    [ 5.000,  7.500) = 6277 
    [ 7.500, 10.000) = 587 
    [10.000, 12.500) = 72 
    [12.500, 15.000) = 5 
    [15.000, 17.500) = 5 
    [17.500, 20.000) = 5 
    [20.000, 22.500) = 68 
    [22.500, 25.000) = 108 
    [25.000, 27.500) = 60 

  Percentiles, ms/op:
      p(0.0000) =      0.949 ms/op
     p(50.0000) =      3.342 ms/op
     p(90.0000) =      3.916 ms/op
     p(95.0000) =      4.235 ms/op
     p(99.0000) =      6.275 ms/op
     p(99.9000) =     11.122 ms/op
     p(99.9900) =     26.948 ms/op
     p(99.9990) =     28.606 ms/op
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
# Warmup Iteration   1: 10.335 ±(99.9%) 0.147 ms/op
# Warmup Iteration   2: 4.306 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.153 ±(99.9%) 0.012 ms/op
Iteration   1: 4.159 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.677 ms/op
                 listUser·p0.50:   3.990 ms/op
                 listUser·p0.90:   4.661 ms/op
                 listUser·p0.95:   5.005 ms/op
                 listUser·p0.99:   7.217 ms/op
                 listUser·p0.999:  18.776 ms/op
                 listUser·p0.9999: 22.522 ms/op
                 listUser·p1.00:   23.036 ms/op

Iteration   2: 3.999 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.290 ms/op
                 listUser·p0.50:   3.883 ms/op
                 listUser·p0.90:   4.383 ms/op
                 listUser·p0.95:   4.579 ms/op
                 listUser·p0.99:   6.565 ms/op
                 listUser·p0.999:  14.582 ms/op
                 listUser·p0.9999: 18.514 ms/op
                 listUser·p1.00:   18.579 ms/op

Iteration   3: 4.055 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.179 ms/op
                 listUser·p0.50:   4.002 ms/op
                 listUser·p0.90:   4.383 ms/op
                 listUser·p0.95:   4.563 ms/op
                 listUser·p0.99:   6.472 ms/op
                 listUser·p0.999:  14.565 ms/op
                 listUser·p0.9999: 15.980 ms/op
                 listUser·p1.00:   16.548 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 235696
  mean =      4.070 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 36 
    [ 2.500,  5.000) = 228118 
    [ 5.000,  7.500) = 5987 
    [ 7.500, 10.000) = 749 
    [10.000, 12.500) = 262 
    [12.500, 15.000) = 314 
    [15.000, 17.500) = 115 
    [17.500, 20.000) = 70 
    [20.000, 22.500) = 37 
    [22.500, 25.000) = 8 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.677 ms/op
     p(50.0000) =      3.961 ms/op
     p(90.0000) =      4.473 ms/op
     p(95.0000) =      4.727 ms/op
     p(99.0000) =      6.808 ms/op
     p(99.9000) =     14.908 ms/op
     p(99.9900) =     20.972 ms/op
     p(99.9990) =     22.849 ms/op
     p(99.9999) =     23.036 ms/op
    p(100.0000) =     23.036 ms/op


# Run complete. Total time: 00:13:12

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.177 ± 3.074  ops/ms
ClientPb.existUser                       thrpt       3   9.813 ± 3.417  ops/ms
ClientPb.getUser                         thrpt       3   9.349 ± 2.245  ops/ms
ClientPb.listUser                        thrpt       3   7.814 ± 1.272  ops/ms
ClientPb.createUser                       avgt       3   3.501 ± 1.900   ms/op
ClientPb.existUser                        avgt       3   3.273 ± 0.521   ms/op
ClientPb.getUser                          avgt       3   3.444 ± 0.509   ms/op
ClientPb.listUser                         avgt       3   4.073 ± 0.229   ms/op
ClientPb.createUser                     sample  278501   3.445 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.247           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.363           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.891           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.178           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.734           ms/op
ClientPb.createUser:createUser·p0.999   sample          16.163           ms/op
ClientPb.createUser:createUser·p0.9999  sample          31.187           ms/op
ClientPb.createUser:createUser·p1.00    sample          32.932           ms/op
ClientPb.existUser                      sample  284032   3.376 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.965           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.310           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.777           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.133           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.661           ms/op
ClientPb.existUser:existUser·p0.999     sample          12.811           ms/op
ClientPb.existUser:existUser·p0.9999    sample          26.378           ms/op
ClientPb.existUser:existUser·p1.00      sample          27.787           ms/op
ClientPb.getUser                        sample  276027   3.476 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.949           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.342           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.916           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.235           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.275           ms/op
ClientPb.getUser:getUser·p0.999         sample          11.122           ms/op
ClientPb.getUser:getUser·p0.9999        sample          26.948           ms/op
ClientPb.getUser:getUser·p1.00          sample          28.705           ms/op
ClientPb.listUser                       sample  235696   4.070 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.677           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.961           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.473           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.727           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.808           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.908           ms/op
ClientPb.listUser:listUser·p0.9999      sample          20.972           ms/op
ClientPb.listUser:listUser·p1.00        sample          23.036           ms/op
