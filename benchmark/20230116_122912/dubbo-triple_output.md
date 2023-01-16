# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.485 ops/ms
# Warmup Iteration   2: 5.823 ops/ms
# Warmup Iteration   3: 8.899 ops/ms
Iteration   1: 9.996 ops/ms
Iteration   2: 9.843 ops/ms
Iteration   3: 9.972 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.937 ±(99.9%) 1.496 ops/ms [Average]
  (min, avg, max) = (9.843, 9.937, 9.996), stdev = 0.082
  CI (99.9%): [8.441, 11.433] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:08
# Fork: 1 of 1
# Warmup Iteration   1: 3.617 ops/ms
# Warmup Iteration   2: 9.525 ops/ms
# Warmup Iteration   3: 10.055 ops/ms
Iteration   1: 9.988 ops/ms
Iteration   2: 10.203 ops/ms
Iteration   3: 10.254 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.148 ±(99.9%) 2.575 ops/ms [Average]
  (min, avg, max) = (9.988, 10.148, 10.254), stdev = 0.141
  CI (99.9%): [7.573, 12.723] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.355 ops/ms
# Warmup Iteration   2: 9.116 ops/ms
# Warmup Iteration   3: 10.001 ops/ms
Iteration   1: 9.804 ops/ms
Iteration   2: 10.287 ops/ms
Iteration   3: 10.106 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  10.065 ±(99.9%) 4.446 ops/ms [Average]
  (min, avg, max) = (9.804, 10.065, 10.287), stdev = 0.244
  CI (99.9%): [5.620, 14.511] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:49
# Fork: 1 of 1
# Warmup Iteration   1: 3.015 ops/ms
# Warmup Iteration   2: 7.738 ops/ms
# Warmup Iteration   3: 8.404 ops/ms
Iteration   1: 8.395 ops/ms
Iteration   2: 8.401 ops/ms
Iteration   3: 8.637 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.478 ±(99.9%) 2.513 ops/ms [Average]
  (min, avg, max) = (8.395, 8.478, 8.637), stdev = 0.138
  CI (99.9%): [5.965, 10.990] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 9.061 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 3.467 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.264 ±(99.9%) 0.004 ms/op
Iteration   1: 3.247 ±(99.9%) 0.003 ms/op
Iteration   2: 3.159 ±(99.9%) 0.006 ms/op
Iteration   3: 3.141 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.182 ±(99.9%) 1.039 ms/op [Average]
  (min, avg, max) = (3.141, 3.182, 3.247), stdev = 0.057
  CI (99.9%): [2.143, 4.221] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:38
# Fork: 1 of 1
# Warmup Iteration   1: 7.746 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 3.382 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.107 ±(99.9%) 0.007 ms/op
Iteration   1: 3.095 ±(99.9%) 0.008 ms/op
Iteration   2: 3.058 ±(99.9%) 0.009 ms/op
Iteration   3: 3.123 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.092 ±(99.9%) 0.595 ms/op [Average]
  (min, avg, max) = (3.058, 3.092, 3.123), stdev = 0.033
  CI (99.9%): [2.497, 3.687] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:32
# Fork: 1 of 1
# Warmup Iteration   1: 9.114 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 3.636 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.326 ±(99.9%) 0.003 ms/op
Iteration   1: 3.239 ±(99.9%) 0.006 ms/op
Iteration   2: 3.125 ±(99.9%) 0.005 ms/op
Iteration   3: 3.118 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.161 ±(99.9%) 1.239 ms/op [Average]
  (min, avg, max) = (3.118, 3.161, 3.239), stdev = 0.068
  CI (99.9%): [1.921, 4.400] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 9.043 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 4.007 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.870 ±(99.9%) 0.006 ms/op
Iteration   1: 3.829 ±(99.9%) 0.006 ms/op
Iteration   2: 3.648 ±(99.9%) 0.011 ms/op
Iteration   3: 3.615 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.698 ±(99.9%) 2.104 ms/op [Average]
  (min, avg, max) = (3.615, 3.698, 3.829), stdev = 0.115
  CI (99.9%): [1.594, 5.801] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 8.249 ±(99.9%) 0.091 ms/op
# Warmup Iteration   2: 3.807 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.161 ±(99.9%) 0.008 ms/op
Iteration   1: 3.060 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   1.489 ms/op
                 createUser·p0.50:   3.043 ms/op
                 createUser·p0.90:   3.207 ms/op
                 createUser·p0.95:   3.301 ms/op
                 createUser·p0.99:   4.817 ms/op
                 createUser·p0.999:  9.790 ms/op
                 createUser·p0.9999: 20.283 ms/op
                 createUser·p1.00:   20.939 ms/op

Iteration   2: 3.198 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.157 ms/op
                 createUser·p0.50:   3.133 ms/op
                 createUser·p0.90:   3.478 ms/op
                 createUser·p0.95:   3.944 ms/op
                 createUser·p0.99:   5.759 ms/op
                 createUser·p0.999:  18.383 ms/op
                 createUser·p0.9999: 21.463 ms/op
                 createUser·p1.00:   21.660 ms/op

Iteration   3: 3.121 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   1.642 ms/op
                 createUser·p0.50:   3.002 ms/op
                 createUser·p0.90:   3.527 ms/op
                 createUser·p0.95:   3.756 ms/op
                 createUser·p0.99:   4.768 ms/op
                 createUser·p0.999:  13.140 ms/op
                 createUser·p0.9999: 15.675 ms/op
                 createUser·p1.00:   15.876 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 306878
  mean =      3.125 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17915 
    [ 2.500,  5.000) = 284460 
    [ 5.000,  7.500) = 3490 
    [ 7.500, 10.000) = 597 
    [10.000, 12.500) = 42 
    [12.500, 15.000) = 107 
    [15.000, 17.500) = 64 
    [17.500, 20.000) = 129 
    [20.000, 22.500) = 74 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.157 ms/op
     p(50.0000) =      3.052 ms/op
     p(90.0000) =      3.408 ms/op
     p(95.0000) =      3.699 ms/op
     p(99.0000) =      5.292 ms/op
     p(99.9000) =     13.996 ms/op
     p(99.9900) =     20.939 ms/op
     p(99.9990) =     21.592 ms/op
     p(99.9999) =     21.660 ms/op
    p(100.0000) =     21.660 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 7.443 ±(99.9%) 0.097 ms/op
# Warmup Iteration   2: 3.474 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.176 ±(99.9%) 0.008 ms/op
Iteration   1: 3.036 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   1.124 ms/op
                 existUser·p0.50:   2.953 ms/op
                 existUser·p0.90:   3.289 ms/op
                 existUser·p0.95:   3.465 ms/op
                 existUser·p0.99:   5.147 ms/op
                 existUser·p0.999:  11.053 ms/op
                 existUser·p0.9999: 20.680 ms/op
                 existUser·p1.00:   21.365 ms/op

Iteration   2: 3.239 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.341 ms/op
                 existUser·p0.50:   3.191 ms/op
                 existUser·p0.90:   3.625 ms/op
                 existUser·p0.95:   3.916 ms/op
                 existUser·p0.99:   5.623 ms/op
                 existUser·p0.999:  9.683 ms/op
                 existUser·p0.9999: 21.762 ms/op
                 existUser·p1.00:   22.938 ms/op

Iteration   3: 3.133 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.475 ms/op
                 existUser·p0.50:   3.060 ms/op
                 existUser·p0.90:   3.351 ms/op
                 existUser·p0.95:   3.813 ms/op
                 existUser·p0.99:   6.160 ms/op
                 existUser·p0.999:  12.348 ms/op
                 existUser·p0.9999: 19.786 ms/op
                 existUser·p1.00:   20.611 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 306189
  mean =      3.134 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18777 
    [ 2.500,  5.000) = 282021 
    [ 5.000,  7.500) = 4758 
    [ 7.500, 10.000) = 279 
    [10.000, 12.500) = 61 
    [12.500, 15.000) = 43 
    [15.000, 17.500) = 33 
    [17.500, 20.000) = 133 
    [20.000, 22.500) = 81 
    [22.500, 25.000) = 3 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.124 ms/op
     p(50.0000) =      3.080 ms/op
     p(90.0000) =      3.437 ms/op
     p(95.0000) =      3.723 ms/op
     p(99.0000) =      5.472 ms/op
     p(99.9000) =     11.339 ms/op
     p(99.9900) =     21.365 ms/op
     p(99.9990) =     22.627 ms/op
     p(99.9999) =     22.938 ms/op
    p(100.0000) =     22.938 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 8.593 ±(99.9%) 0.115 ms/op
# Warmup Iteration   2: 3.482 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.231 ±(99.9%) 0.009 ms/op
Iteration   1: 3.277 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.442 ms/op
                 getUser·p0.50:   3.174 ms/op
                 getUser·p0.90:   3.777 ms/op
                 getUser·p0.95:   4.506 ms/op
                 getUser·p0.99:   6.488 ms/op
                 getUser·p0.999:  19.900 ms/op
                 getUser·p0.9999: 28.180 ms/op
                 getUser·p1.00:   29.065 ms/op

Iteration   2: 3.148 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.155 ms/op
                 getUser·p0.50:   3.097 ms/op
                 getUser·p0.90:   3.490 ms/op
                 getUser·p0.95:   3.883 ms/op
                 getUser·p0.99:   5.562 ms/op
                 getUser·p0.999:  9.988 ms/op
                 getUser·p0.9999: 27.965 ms/op
                 getUser·p1.00:   29.393 ms/op

Iteration   3: 3.264 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.503 ms/op
                 getUser·p0.50:   3.183 ms/op
                 getUser·p0.90:   3.809 ms/op
                 getUser·p0.95:   4.276 ms/op
                 getUser·p0.99:   5.710 ms/op
                 getUser·p0.999:  14.189 ms/op
                 getUser·p0.9999: 23.646 ms/op
                 getUser·p1.00:   24.576 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 297128
  mean =      3.228 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 25955 
    [ 2.500,  5.000) = 263548 
    [ 5.000,  7.500) = 6541 
    [ 7.500, 10.000) = 671 
    [10.000, 12.500) = 82 
    [12.500, 15.000) = 22 
    [15.000, 17.500) = 43 
    [17.500, 20.000) = 44 
    [20.000, 22.500) = 106 
    [22.500, 25.000) = 52 
    [25.000, 27.500) = 23 

  Percentiles, ms/op:
      p(0.0000) =      1.155 ms/op
     p(50.0000) =      3.158 ms/op
     p(90.0000) =      3.686 ms/op
     p(95.0000) =      4.211 ms/op
     p(99.0000) =      5.808 ms/op
     p(99.9000) =     15.788 ms/op
     p(99.9900) =     27.853 ms/op
     p(99.9990) =     29.133 ms/op
     p(99.9999) =     29.393 ms/op
    p(100.0000) =     29.393 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 9.738 ±(99.9%) 0.129 ms/op
# Warmup Iteration   2: 4.081 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.811 ±(99.9%) 0.011 ms/op
Iteration   1: 3.742 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.438 ms/op
                 listUser·p0.50:   3.621 ms/op
                 listUser·p0.90:   4.080 ms/op
                 listUser·p0.95:   4.301 ms/op
                 listUser·p0.99:   7.403 ms/op
                 listUser·p0.999:  15.534 ms/op
                 listUser·p0.9999: 18.889 ms/op
                 listUser·p1.00:   19.431 ms/op

Iteration   2: 3.806 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.179 ms/op
                 listUser·p0.50:   3.695 ms/op
                 listUser·p0.90:   4.202 ms/op
                 listUser·p0.95:   4.451 ms/op
                 listUser·p0.99:   7.010 ms/op
                 listUser·p0.999:  12.712 ms/op
                 listUser·p0.9999: 15.291 ms/op
                 listUser·p1.00:   15.696 ms/op

Iteration   3: 3.672 ±(99.9%) 0.007 ms/op
                 listUser·p0.00:   2.150 ms/op
                 listUser·p0.50:   3.658 ms/op
                 listUser·p0.90:   3.805 ms/op
                 listUser·p0.95:   4.006 ms/op
                 listUser·p0.99:   6.595 ms/op
                 listUser·p0.999:  12.449 ms/op
                 listUser·p0.9999: 16.400 ms/op
                 listUser·p1.00:   16.548 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 256667
  mean =      3.739 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 0 
    [ 1.250,  2.500) = 52 
    [ 2.500,  3.750) = 190044 
    [ 3.750,  5.000) = 60275 
    [ 5.000,  6.250) = 1715 
    [ 6.250,  7.500) = 2653 
    [ 7.500,  8.750) = 927 
    [ 8.750, 10.000) = 329 
    [10.000, 11.250) = 70 
    [11.250, 12.500) = 223 
    [12.500, 13.750) = 221 
    [13.750, 15.000) = 25 
    [15.000, 16.250) = 60 
    [16.250, 17.500) = 39 
    [17.500, 18.750) = 23 

  Percentiles, ms/op:
      p(0.0000) =      1.438 ms/op
     p(50.0000) =      3.658 ms/op
     p(90.0000) =      4.051 ms/op
     p(95.0000) =      4.293 ms/op
     p(99.0000) =      6.955 ms/op
     p(99.9000) =     13.074 ms/op
     p(99.9900) =     17.760 ms/op
     p(99.9990) =     19.263 ms/op
     p(99.9999) =     19.431 ms/op
    p(100.0000) =     19.431 ms/op


# Run complete. Total time: 00:13:08

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.937 ± 1.496  ops/ms
ClientPb.existUser                       thrpt       3  10.148 ± 2.575  ops/ms
ClientPb.getUser                         thrpt       3  10.065 ± 4.446  ops/ms
ClientPb.listUser                        thrpt       3   8.478 ± 2.513  ops/ms
ClientPb.createUser                       avgt       3   3.182 ± 1.039   ms/op
ClientPb.existUser                        avgt       3   3.092 ± 0.595   ms/op
ClientPb.getUser                          avgt       3   3.161 ± 1.239   ms/op
ClientPb.listUser                         avgt       3   3.698 ± 2.104   ms/op
ClientPb.createUser                     sample  306878   3.125 ± 0.004   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.157           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.052           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.408           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.699           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.292           ms/op
ClientPb.createUser:createUser·p0.999   sample          13.996           ms/op
ClientPb.createUser:createUser·p0.9999  sample          20.939           ms/op
ClientPb.createUser:createUser·p1.00    sample          21.660           ms/op
ClientPb.existUser                      sample  306189   3.134 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.124           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.080           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.437           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.723           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.472           ms/op
ClientPb.existUser:existUser·p0.999     sample          11.339           ms/op
ClientPb.existUser:existUser·p0.9999    sample          21.365           ms/op
ClientPb.existUser:existUser·p1.00      sample          22.938           ms/op
ClientPb.getUser                        sample  297128   3.228 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.155           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.158           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.686           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.211           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.808           ms/op
ClientPb.getUser:getUser·p0.999         sample          15.788           ms/op
ClientPb.getUser:getUser·p0.9999        sample          27.853           ms/op
ClientPb.getUser:getUser·p1.00          sample          29.393           ms/op
ClientPb.listUser                       sample  256667   3.739 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.438           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.658           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.051           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.293           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.955           ms/op
ClientPb.listUser:listUser·p0.999       sample          13.074           ms/op
ClientPb.listUser:listUser·p0.9999      sample          17.760           ms/op
ClientPb.listUser:listUser·p1.00        sample          19.431           ms/op
