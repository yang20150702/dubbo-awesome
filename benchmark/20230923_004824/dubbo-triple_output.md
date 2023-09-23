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
# Warmup Iteration   1: 2.191 ops/ms
# Warmup Iteration   2: 5.742 ops/ms
# Warmup Iteration   3: 8.451 ops/ms
Iteration   1: 9.083 ops/ms
Iteration   2: 9.189 ops/ms
Iteration   3: 9.167 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.147 ±(99.9%) 1.018 ops/ms [Average]
  (min, avg, max) = (9.083, 9.147, 9.189), stdev = 0.056
  CI (99.9%): [8.129, 10.165] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 3.100 ops/ms
# Warmup Iteration   2: 8.761 ops/ms
# Warmup Iteration   3: 9.409 ops/ms
Iteration   1: 9.584 ops/ms
Iteration   2: 9.361 ops/ms
Iteration   3: 9.249 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.398 ±(99.9%) 3.115 ops/ms [Average]
  (min, avg, max) = (9.249, 9.398, 9.584), stdev = 0.171
  CI (99.9%): [6.283, 12.513] (assumes normal distribution)


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
# Warmup Iteration   1: 3.096 ops/ms
# Warmup Iteration   2: 8.555 ops/ms
# Warmup Iteration   3: 9.161 ops/ms
Iteration   1: 9.181 ops/ms
Iteration   2: 9.311 ops/ms
Iteration   3: 9.298 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.263 ±(99.9%) 1.306 ops/ms [Average]
  (min, avg, max) = (9.181, 9.263, 9.311), stdev = 0.072
  CI (99.9%): [7.957, 10.569] (assumes normal distribution)


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
# Warmup Iteration   1: 2.980 ops/ms
# Warmup Iteration   2: 7.170 ops/ms
# Warmup Iteration   3: 7.736 ops/ms
Iteration   1: 7.859 ops/ms
Iteration   2: 7.980 ops/ms
Iteration   3: 7.840 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.893 ±(99.9%) 1.384 ops/ms [Average]
  (min, avg, max) = (7.840, 7.893, 7.980), stdev = 0.076
  CI (99.9%): [6.509, 9.277] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:47
# Fork: 1 of 1
# Warmup Iteration   1: 9.983 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.696 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.525 ±(99.9%) 0.006 ms/op
Iteration   1: 3.518 ±(99.9%) 0.005 ms/op
Iteration   2: 3.368 ±(99.9%) 0.004 ms/op
Iteration   3: 3.376 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.421 ±(99.9%) 1.542 ms/op [Average]
  (min, avg, max) = (3.368, 3.421, 3.518), stdev = 0.085
  CI (99.9%): [1.878, 4.963] (assumes normal distribution)


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
# Warmup Iteration   1: 9.058 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 3.527 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.359 ±(99.9%) 0.005 ms/op
Iteration   1: 3.289 ±(99.9%) 0.005 ms/op
Iteration   2: 3.292 ±(99.9%) 0.003 ms/op
Iteration   3: 3.338 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.306 ±(99.9%) 0.497 ms/op [Average]
  (min, avg, max) = (3.289, 3.306, 3.338), stdev = 0.027
  CI (99.9%): [2.809, 3.803] (assumes normal distribution)


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
# Warmup Iteration   1: 8.902 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 3.466 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.502 ±(99.9%) 0.004 ms/op
Iteration   1: 3.408 ±(99.9%) 0.004 ms/op
Iteration   2: 3.452 ±(99.9%) 0.005 ms/op
Iteration   3: 3.369 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.410 ±(99.9%) 0.756 ms/op [Average]
  (min, avg, max) = (3.369, 3.410, 3.452), stdev = 0.041
  CI (99.9%): [2.654, 4.166] (assumes normal distribution)


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
# Warmup Iteration   1: 10.122 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 4.240 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.145 ±(99.9%) 0.005 ms/op
Iteration   1: 4.031 ±(99.9%) 0.006 ms/op
Iteration   2: 4.029 ±(99.9%) 0.006 ms/op
Iteration   3: 4.144 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.068 ±(99.9%) 1.204 ms/op [Average]
  (min, avg, max) = (4.029, 4.068, 4.144), stdev = 0.066
  CI (99.9%): [2.864, 5.272] (assumes normal distribution)


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
# Warmup Iteration   1: 8.711 ±(99.9%) 0.110 ms/op
# Warmup Iteration   2: 3.844 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.612 ±(99.9%) 0.010 ms/op
Iteration   1: 3.323 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.618 ms/op
                 createUser·p0.50:   3.244 ms/op
                 createUser·p0.90:   3.625 ms/op
                 createUser·p0.95:   3.895 ms/op
                 createUser·p0.99:   5.885 ms/op
                 createUser·p0.999:  15.386 ms/op
                 createUser·p0.9999: 22.405 ms/op
                 createUser·p1.00:   23.527 ms/op

Iteration   2: 3.468 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.049 ms/op
                 createUser·p0.50:   3.367 ms/op
                 createUser·p0.90:   3.916 ms/op
                 createUser·p0.95:   4.284 ms/op
                 createUser·p0.99:   6.816 ms/op
                 createUser·p0.999:  18.411 ms/op
                 createUser·p0.9999: 20.539 ms/op
                 createUser·p1.00:   20.939 ms/op

Iteration   3: 3.436 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.499 ms/op
                 createUser·p0.50:   3.379 ms/op
                 createUser·p0.90:   3.879 ms/op
                 createUser·p0.95:   4.133 ms/op
                 createUser·p0.99:   5.898 ms/op
                 createUser·p0.999:  16.594 ms/op
                 createUser·p0.9999: 22.741 ms/op
                 createUser·p1.00:   23.724 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 281464
  mean =      3.408 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9318 
    [ 2.500,  5.000) = 266180 
    [ 5.000,  7.500) = 4930 
    [ 7.500, 10.000) = 592 
    [10.000, 12.500) = 112 
    [12.500, 15.000) = 6 
    [15.000, 17.500) = 38 
    [17.500, 20.000) = 178 
    [20.000, 22.500) = 84 
    [22.500, 25.000) = 26 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.049 ms/op
     p(50.0000) =      3.326 ms/op
     p(90.0000) =      3.813 ms/op
     p(95.0000) =      4.125 ms/op
     p(99.0000) =      6.439 ms/op
     p(99.9000) =     17.581 ms/op
     p(99.9900) =     22.479 ms/op
     p(99.9990) =     23.527 ms/op
     p(99.9999) =     23.724 ms/op
    p(100.0000) =     23.724 ms/op


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
# Warmup Iteration   1: 8.730 ±(99.9%) 0.103 ms/op
# Warmup Iteration   2: 3.598 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.361 ±(99.9%) 0.009 ms/op
Iteration   1: 3.302 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.534 ms/op
                 existUser·p0.50:   3.248 ms/op
                 existUser·p0.90:   3.547 ms/op
                 existUser·p0.95:   3.797 ms/op
                 existUser·p0.99:   6.021 ms/op
                 existUser·p0.999:  17.831 ms/op
                 existUser·p0.9999: 20.611 ms/op
                 existUser·p1.00:   21.627 ms/op

Iteration   2: 3.294 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.350 ms/op
                 existUser·p0.50:   3.256 ms/op
                 existUser·p0.90:   3.559 ms/op
                 existUser·p0.95:   3.781 ms/op
                 existUser·p0.99:   5.497 ms/op
                 existUser·p0.999:  15.983 ms/op
                 existUser·p0.9999: 21.580 ms/op
                 existUser·p1.00:   22.938 ms/op

Iteration   3: 3.410 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.450 ms/op
                 existUser·p0.50:   3.285 ms/op
                 existUser·p0.90:   3.805 ms/op
                 existUser·p0.95:   4.211 ms/op
                 existUser·p0.99:   6.922 ms/op
                 existUser·p0.999:  12.927 ms/op
                 existUser·p0.9999: 22.884 ms/op
                 existUser·p1.00:   24.084 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 287893
  mean =      3.334 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10625 
    [ 2.500,  5.000) = 271467 
    [ 5.000,  7.500) = 4706 
    [ 7.500, 10.000) = 498 
    [10.000, 12.500) = 232 
    [12.500, 15.000) = 97 
    [15.000, 17.500) = 11 
    [17.500, 20.000) = 104 
    [20.000, 22.500) = 136 
    [22.500, 25.000) = 17 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.350 ms/op
     p(50.0000) =      3.265 ms/op
     p(90.0000) =      3.633 ms/op
     p(95.0000) =      3.944 ms/op
     p(99.0000) =      6.226 ms/op
     p(99.9000) =     13.097 ms/op
     p(99.9900) =     22.315 ms/op
     p(99.9990) =     23.994 ms/op
     p(99.9999) =     24.084 ms/op
    p(100.0000) =     24.084 ms/op


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
# Warmup Iteration   1: 10.428 ±(99.9%) 0.132 ms/op
# Warmup Iteration   2: 3.636 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.544 ±(99.9%) 0.009 ms/op
Iteration   1: 3.488 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.221 ms/op
                 getUser·p0.50:   3.314 ms/op
                 getUser·p0.90:   3.838 ms/op
                 getUser·p0.95:   4.596 ms/op
                 getUser·p0.99:   7.086 ms/op
                 getUser·p0.999:  15.227 ms/op
                 getUser·p0.9999: 20.245 ms/op
                 getUser·p1.00:   20.677 ms/op

Iteration   2: 3.459 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.040 ms/op
                 getUser·p0.50:   3.342 ms/op
                 getUser·p0.90:   3.830 ms/op
                 getUser·p0.95:   4.018 ms/op
                 getUser·p0.99:   6.169 ms/op
                 getUser·p0.999:  20.316 ms/op
                 getUser·p0.9999: 23.265 ms/op
                 getUser·p1.00:   23.757 ms/op

Iteration   3: 3.344 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.102 ms/op
                 getUser·p0.50:   3.244 ms/op
                 getUser·p0.90:   3.662 ms/op
                 getUser·p0.95:   3.850 ms/op
                 getUser·p0.99:   5.767 ms/op
                 getUser·p0.999:  16.475 ms/op
                 getUser·p0.9999: 23.804 ms/op
                 getUser·p1.00:   24.216 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 279858
  mean =      3.429 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3556 
    [ 2.500,  5.000) = 268759 
    [ 5.000,  7.500) = 6318 
    [ 7.500, 10.000) = 557 
    [10.000, 12.500) = 296 
    [12.500, 15.000) = 40 
    [15.000, 17.500) = 43 
    [17.500, 20.000) = 105 
    [20.000, 22.500) = 142 
    [22.500, 25.000) = 42 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.040 ms/op
     p(50.0000) =      3.293 ms/op
     p(90.0000) =      3.777 ms/op
     p(95.0000) =      4.043 ms/op
     p(99.0000) =      6.636 ms/op
     p(99.9000) =     17.863 ms/op
     p(99.9900) =     23.101 ms/op
     p(99.9990) =     24.098 ms/op
     p(99.9999) =     24.216 ms/op
    p(100.0000) =     24.216 ms/op


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
# Warmup Iteration   1: 10.723 ±(99.9%) 0.156 ms/op
# Warmup Iteration   2: 4.385 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.149 ±(99.9%) 0.013 ms/op
Iteration   1: 4.040 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.571 ms/op
                 listUser·p0.50:   3.908 ms/op
                 listUser·p0.90:   4.399 ms/op
                 listUser·p0.95:   4.615 ms/op
                 listUser·p0.99:   6.832 ms/op
                 listUser·p0.999:  17.259 ms/op
                 listUser·p0.9999: 21.933 ms/op
                 listUser·p1.00:   22.577 ms/op

Iteration   2: 4.059 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.392 ms/op
                 listUser·p0.50:   3.912 ms/op
                 listUser·p0.90:   4.407 ms/op
                 listUser·p0.95:   4.694 ms/op
                 listUser·p0.99:   7.295 ms/op
                 listUser·p0.999:  14.483 ms/op
                 listUser·p0.9999: 18.092 ms/op
                 listUser·p1.00:   18.481 ms/op

Iteration   3: 4.075 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.535 ms/op
                 listUser·p0.50:   3.949 ms/op
                 listUser·p0.90:   4.547 ms/op
                 listUser·p0.95:   4.833 ms/op
                 listUser·p0.99:   7.234 ms/op
                 listUser·p0.999:  15.221 ms/op
                 listUser·p0.9999: 19.268 ms/op
                 listUser·p1.00:   19.333 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 236720
  mean =      4.058 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 42 
    [ 2.500,  5.000) = 228705 
    [ 5.000,  7.500) = 6294 
    [ 7.500, 10.000) = 867 
    [10.000, 12.500) = 208 
    [12.500, 15.000) = 347 
    [15.000, 17.500) = 140 
    [17.500, 20.000) = 64 
    [20.000, 22.500) = 52 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.571 ms/op
     p(50.0000) =      3.932 ms/op
     p(90.0000) =      4.440 ms/op
     p(95.0000) =      4.727 ms/op
     p(99.0000) =      7.102 ms/op
     p(99.9000) =     15.127 ms/op
     p(99.9900) =     20.687 ms/op
     p(99.9990) =     22.344 ms/op
     p(99.9999) =     22.577 ms/op
    p(100.0000) =     22.577 ms/op


# Run complete. Total time: 00:13:13

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.147 ± 1.018  ops/ms
ClientPb.existUser                       thrpt       3   9.398 ± 3.115  ops/ms
ClientPb.getUser                         thrpt       3   9.263 ± 1.306  ops/ms
ClientPb.listUser                        thrpt       3   7.893 ± 1.384  ops/ms
ClientPb.createUser                       avgt       3   3.421 ± 1.542   ms/op
ClientPb.existUser                        avgt       3   3.306 ± 0.497   ms/op
ClientPb.getUser                          avgt       3   3.410 ± 0.756   ms/op
ClientPb.listUser                         avgt       3   4.068 ± 1.204   ms/op
ClientPb.createUser                     sample  281464   3.408 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.049           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.326           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.813           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.125           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.439           ms/op
ClientPb.createUser:createUser·p0.999   sample          17.581           ms/op
ClientPb.createUser:createUser·p0.9999  sample          22.479           ms/op
ClientPb.createUser:createUser·p1.00    sample          23.724           ms/op
ClientPb.existUser                      sample  287893   3.334 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.350           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.265           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.633           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.944           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.226           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.097           ms/op
ClientPb.existUser:existUser·p0.9999    sample          22.315           ms/op
ClientPb.existUser:existUser·p1.00      sample          24.084           ms/op
ClientPb.getUser                        sample  279858   3.429 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.040           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.293           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.777           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.043           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.636           ms/op
ClientPb.getUser:getUser·p0.999         sample          17.863           ms/op
ClientPb.getUser:getUser·p0.9999        sample          23.101           ms/op
ClientPb.getUser:getUser·p1.00          sample          24.216           ms/op
ClientPb.listUser                       sample  236720   4.058 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.571           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.932           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.440           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.727           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.102           ms/op
ClientPb.listUser:listUser·p0.999       sample          15.127           ms/op
ClientPb.listUser:listUser·p0.9999      sample          20.687           ms/op
ClientPb.listUser:listUser·p1.00        sample          22.577           ms/op
