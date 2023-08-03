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
# Warmup Iteration   1: 2.287 ops/ms
# Warmup Iteration   2: 5.860 ops/ms
# Warmup Iteration   3: 8.777 ops/ms
Iteration   1: 9.200 ops/ms
Iteration   2: 9.602 ops/ms
Iteration   3: 8.984 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.262 ±(99.9%) 5.721 ops/ms [Average]
  (min, avg, max) = (8.984, 9.262, 9.602), stdev = 0.314
  CI (99.9%): [3.541, 14.983] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 3.040 ops/ms
# Warmup Iteration   2: 8.674 ops/ms
# Warmup Iteration   3: 8.876 ops/ms
Iteration   1: 9.315 ops/ms
Iteration   2: 8.998 ops/ms
Iteration   3: 9.472 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.262 ±(99.9%) 4.406 ops/ms [Average]
  (min, avg, max) = (8.998, 9.262, 9.472), stdev = 0.241
  CI (99.9%): [4.856, 13.667] (assumes normal distribution)


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
# Warmup Iteration   1: 3.305 ops/ms
# Warmup Iteration   2: 8.397 ops/ms
# Warmup Iteration   3: 9.055 ops/ms
Iteration   1: 9.381 ops/ms
Iteration   2: 9.444 ops/ms
Iteration   3: 9.386 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.403 ±(99.9%) 0.642 ops/ms [Average]
  (min, avg, max) = (9.381, 9.403, 9.444), stdev = 0.035
  CI (99.9%): [8.761, 10.046] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:49
# Fork: 1 of 1
# Warmup Iteration   1: 2.796 ops/ms
# Warmup Iteration   2: 6.999 ops/ms
# Warmup Iteration   3: 7.982 ops/ms
Iteration   1: 7.874 ops/ms
Iteration   2: 8.143 ops/ms
Iteration   3: 8.273 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.097 ±(99.9%) 3.718 ops/ms [Average]
  (min, avg, max) = (7.874, 8.097, 8.273), stdev = 0.204
  CI (99.9%): [4.378, 11.815] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 9.296 ±(99.9%) 0.063 ms/op
# Warmup Iteration   2: 3.695 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.713 ±(99.9%) 0.006 ms/op
Iteration   1: 3.528 ±(99.9%) 0.002 ms/op
Iteration   2: 3.453 ±(99.9%) 0.010 ms/op
Iteration   3: 3.492 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.491 ±(99.9%) 0.691 ms/op [Average]
  (min, avg, max) = (3.453, 3.491, 3.528), stdev = 0.038
  CI (99.9%): [2.800, 4.182] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:38
# Fork: 1 of 1
# Warmup Iteration   1: 8.775 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 3.515 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.462 ±(99.9%) 0.004 ms/op
Iteration   1: 3.398 ±(99.9%) 0.005 ms/op
Iteration   2: 3.328 ±(99.9%) 0.003 ms/op
Iteration   3: 3.344 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.357 ±(99.9%) 0.673 ms/op [Average]
  (min, avg, max) = (3.328, 3.357, 3.398), stdev = 0.037
  CI (99.9%): [2.684, 4.030] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:32
# Fork: 1 of 1
# Warmup Iteration   1: 9.368 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 3.730 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.578 ±(99.9%) 0.005 ms/op
Iteration   1: 3.578 ±(99.9%) 0.008 ms/op
Iteration   2: 3.505 ±(99.9%) 0.002 ms/op
Iteration   3: 3.536 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.540 ±(99.9%) 0.669 ms/op [Average]
  (min, avg, max) = (3.505, 3.540, 3.578), stdev = 0.037
  CI (99.9%): [2.871, 4.209] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 10.185 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 4.398 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.055 ±(99.9%) 0.007 ms/op
Iteration   1: 4.133 ±(99.9%) 0.006 ms/op
Iteration   2: 3.973 ±(99.9%) 0.010 ms/op
Iteration   3: 4.031 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.046 ±(99.9%) 1.480 ms/op [Average]
  (min, avg, max) = (3.973, 4.046, 4.133), stdev = 0.081
  CI (99.9%): [2.565, 5.526] (assumes normal distribution)


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
# Warmup Iteration   1: 9.063 ±(99.9%) 0.129 ms/op
# Warmup Iteration   2: 3.892 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.513 ±(99.9%) 0.012 ms/op
Iteration   1: 3.435 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.048 ms/op
                 createUser·p0.50:   3.310 ms/op
                 createUser·p0.90:   4.010 ms/op
                 createUser·p0.95:   4.440 ms/op
                 createUser·p0.99:   6.218 ms/op
                 createUser·p0.999:  21.355 ms/op
                 createUser·p0.9999: 28.039 ms/op
                 createUser·p1.00:   28.738 ms/op

Iteration   2: 3.507 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.456 ms/op
                 createUser·p0.50:   3.367 ms/op
                 createUser·p0.90:   4.067 ms/op
                 createUser·p0.95:   4.456 ms/op
                 createUser·p0.99:   6.603 ms/op
                 createUser·p0.999:  23.705 ms/op
                 createUser·p0.9999: 27.488 ms/op
                 createUser·p1.00:   28.017 ms/op

Iteration   3: 3.329 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.229 ms/op
                 createUser·p0.50:   3.207 ms/op
                 createUser·p0.90:   3.703 ms/op
                 createUser·p0.95:   3.908 ms/op
                 createUser·p0.99:   5.538 ms/op
                 createUser·p0.999:  19.472 ms/op
                 createUser·p0.9999: 27.800 ms/op
                 createUser·p1.00:   29.000 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 280405
  mean =      3.422 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11224 
    [ 2.500,  5.000) = 261062 
    [ 5.000,  7.500) = 6789 
    [ 7.500, 10.000) = 877 
    [10.000, 12.500) = 139 
    [12.500, 15.000) = 26 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 75 
    [22.500, 25.000) = 106 
    [25.000, 27.500) = 70 

  Percentiles, ms/op:
      p(0.0000) =      1.048 ms/op
     p(50.0000) =      3.301 ms/op
     p(90.0000) =      3.912 ms/op
     p(95.0000) =      4.284 ms/op
     p(99.0000) =      6.332 ms/op
     p(99.9000) =     20.958 ms/op
     p(99.9900) =     27.752 ms/op
     p(99.9990) =     28.744 ms/op
     p(99.9999) =     29.000 ms/op
    p(100.0000) =     29.000 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 8.102 ±(99.9%) 0.104 ms/op
# Warmup Iteration   2: 3.534 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.332 ±(99.9%) 0.009 ms/op
Iteration   1: 3.264 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.961 ms/op
                 existUser·p0.50:   3.138 ms/op
                 existUser·p0.90:   3.592 ms/op
                 existUser·p0.95:   3.809 ms/op
                 existUser·p0.99:   5.595 ms/op
                 existUser·p0.999:  11.567 ms/op
                 existUser·p0.9999: 23.239 ms/op
                 existUser·p1.00:   23.593 ms/op

Iteration   2: 3.427 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.581 ms/op
                 existUser·p0.50:   3.260 ms/op
                 existUser·p0.90:   3.949 ms/op
                 existUser·p0.95:   4.358 ms/op
                 existUser·p0.99:   6.799 ms/op
                 existUser·p0.999:  9.033 ms/op
                 existUser·p0.9999: 24.598 ms/op
                 existUser·p1.00:   26.051 ms/op

Iteration   3: 3.358 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.362 ms/op
                 existUser·p0.50:   3.265 ms/op
                 existUser·p0.90:   3.772 ms/op
                 existUser·p0.95:   4.317 ms/op
                 existUser·p0.99:   6.308 ms/op
                 existUser·p0.999:  21.254 ms/op
                 existUser·p0.9999: 27.591 ms/op
                 existUser·p1.00:   29.360 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 286714
  mean =      3.348 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10646 
    [ 2.500,  5.000) = 268759 
    [ 5.000,  7.500) = 6026 
    [ 7.500, 10.000) = 977 
    [10.000, 12.500) = 50 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 2 
    [20.000, 22.500) = 115 
    [22.500, 25.000) = 98 
    [25.000, 27.500) = 31 

  Percentiles, ms/op:
      p(0.0000) =      0.961 ms/op
     p(50.0000) =      3.232 ms/op
     p(90.0000) =      3.760 ms/op
     p(95.0000) =      4.182 ms/op
     p(99.0000) =      6.431 ms/op
     p(99.9000) =     11.427 ms/op
     p(99.9900) =     26.007 ms/op
     p(99.9990) =     29.135 ms/op
     p(99.9999) =     29.360 ms/op
    p(100.0000) =     29.360 ms/op


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
# Warmup Iteration   1: 9.767 ±(99.9%) 0.110 ms/op
# Warmup Iteration   2: 3.790 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.566 ±(99.9%) 0.012 ms/op
Iteration   1: 3.532 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.112 ms/op
                 getUser·p0.50:   3.371 ms/op
                 getUser·p0.90:   4.063 ms/op
                 getUser·p0.95:   4.633 ms/op
                 getUser·p0.99:   7.012 ms/op
                 getUser·p0.999:  13.999 ms/op
                 getUser·p0.9999: 20.574 ms/op
                 getUser·p1.00:   21.398 ms/op

Iteration   2: 3.566 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.729 ms/op
                 getUser·p0.50:   3.391 ms/op
                 getUser·p0.90:   4.194 ms/op
                 getUser·p0.95:   4.776 ms/op
                 getUser·p0.99:   6.668 ms/op
                 getUser·p0.999:  20.107 ms/op
                 getUser·p0.9999: 22.938 ms/op
                 getUser·p1.00:   23.233 ms/op

Iteration   3: 3.438 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.255 ms/op
                 getUser·p0.50:   3.330 ms/op
                 getUser·p0.90:   3.838 ms/op
                 getUser·p0.95:   4.342 ms/op
                 getUser·p0.99:   6.963 ms/op
                 getUser·p0.999:  19.005 ms/op
                 getUser·p0.9999: 25.854 ms/op
                 getUser·p1.00:   26.509 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 273281
  mean =      3.511 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14126 
    [ 2.500,  5.000) = 248692 
    [ 5.000,  7.500) = 8408 
    [ 7.500, 10.000) = 1526 
    [10.000, 12.500) = 160 
    [12.500, 15.000) = 88 
    [15.000, 17.500) = 24 
    [17.500, 20.000) = 67 
    [20.000, 22.500) = 107 
    [22.500, 25.000) = 60 
    [25.000, 27.500) = 23 

  Percentiles, ms/op:
      p(0.0000) =      1.112 ms/op
     p(50.0000) =      3.363 ms/op
     p(90.0000) =      4.035 ms/op
     p(95.0000) =      4.653 ms/op
     p(99.0000) =      6.906 ms/op
     p(99.9000) =     15.806 ms/op
     p(99.9900) =     24.631 ms/op
     p(99.9990) =     26.201 ms/op
     p(99.9999) =     26.509 ms/op
    p(100.0000) =     26.509 ms/op


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
# Warmup Iteration   1: 10.988 ±(99.9%) 0.144 ms/op
# Warmup Iteration   2: 4.661 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 4.067 ±(99.9%) 0.012 ms/op
Iteration   1: 4.086 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.843 ms/op
                 listUser·p0.50:   3.850 ms/op
                 listUser·p0.90:   4.588 ms/op
                 listUser·p0.95:   5.046 ms/op
                 listUser·p0.99:   8.196 ms/op
                 listUser·p0.999:  19.268 ms/op
                 listUser·p0.9999: 27.209 ms/op
                 listUser·p1.00:   29.098 ms/op

Iteration   2: 4.094 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.245 ms/op
                 listUser·p0.50:   3.875 ms/op
                 listUser·p0.90:   4.604 ms/op
                 listUser·p0.95:   4.956 ms/op
                 listUser·p0.99:   7.733 ms/op
                 listUser·p0.999:  15.958 ms/op
                 listUser·p0.9999: 21.758 ms/op
                 listUser·p1.00:   21.791 ms/op

Iteration   3: 4.212 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.412 ms/op
                 listUser·p0.50:   4.026 ms/op
                 listUser·p0.90:   4.751 ms/op
                 listUser·p0.95:   5.546 ms/op
                 listUser·p0.99:   8.307 ms/op
                 listUser·p0.999:  14.270 ms/op
                 listUser·p0.9999: 15.211 ms/op
                 listUser·p1.00:   15.319 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 232536
  mean =      4.130 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 67 
    [ 2.500,  5.000) = 219353 
    [ 5.000,  7.500) = 9889 
    [ 7.500, 10.000) = 2292 
    [10.000, 12.500) = 447 
    [12.500, 15.000) = 206 
    [15.000, 17.500) = 117 
    [17.500, 20.000) = 83 
    [20.000, 22.500) = 18 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 61 

  Percentiles, ms/op:
      p(0.0000) =      0.412 ms/op
     p(50.0000) =      3.912 ms/op
     p(90.0000) =      4.637 ms/op
     p(95.0000) =      5.136 ms/op
     p(99.0000) =      8.151 ms/op
     p(99.9000) =     15.540 ms/op
     p(99.9900) =     26.534 ms/op
     p(99.9990) =     28.451 ms/op
     p(99.9999) =     29.098 ms/op
    p(100.0000) =     29.098 ms/op


# Run complete. Total time: 00:13:08

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.262 ± 5.721  ops/ms
ClientPb.existUser                       thrpt       3   9.262 ± 4.406  ops/ms
ClientPb.getUser                         thrpt       3   9.403 ± 0.642  ops/ms
ClientPb.listUser                        thrpt       3   8.097 ± 3.718  ops/ms
ClientPb.createUser                       avgt       3   3.491 ± 0.691   ms/op
ClientPb.existUser                        avgt       3   3.357 ± 0.673   ms/op
ClientPb.getUser                          avgt       3   3.540 ± 0.669   ms/op
ClientPb.listUser                         avgt       3   4.046 ± 1.480   ms/op
ClientPb.createUser                     sample  280405   3.422 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.048           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.301           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.912           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.284           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.332           ms/op
ClientPb.createUser:createUser·p0.999   sample          20.958           ms/op
ClientPb.createUser:createUser·p0.9999  sample          27.752           ms/op
ClientPb.createUser:createUser·p1.00    sample          29.000           ms/op
ClientPb.existUser                      sample  286714   3.348 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.961           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.232           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.760           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.182           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.431           ms/op
ClientPb.existUser:existUser·p0.999     sample          11.427           ms/op
ClientPb.existUser:existUser·p0.9999    sample          26.007           ms/op
ClientPb.existUser:existUser·p1.00      sample          29.360           ms/op
ClientPb.getUser                        sample  273281   3.511 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.112           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.363           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.035           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.653           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.906           ms/op
ClientPb.getUser:getUser·p0.999         sample          15.806           ms/op
ClientPb.getUser:getUser·p0.9999        sample          24.631           ms/op
ClientPb.getUser:getUser·p1.00          sample          26.509           ms/op
ClientPb.listUser                       sample  232536   4.130 ± 0.007   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.412           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.912           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.637           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.136           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.151           ms/op
ClientPb.listUser:listUser·p0.999       sample          15.540           ms/op
ClientPb.listUser:listUser·p0.9999      sample          26.534           ms/op
ClientPb.listUser:listUser·p1.00        sample          29.098           ms/op
