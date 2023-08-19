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
# Warmup Iteration   1: 2.169 ops/ms
# Warmup Iteration   2: 5.316 ops/ms
# Warmup Iteration   3: 8.431 ops/ms
Iteration   1: 9.007 ops/ms
Iteration   2: 9.165 ops/ms
Iteration   3: 9.420 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.197 ±(99.9%) 3.799 ops/ms [Average]
  (min, avg, max) = (9.007, 9.197, 9.420), stdev = 0.208
  CI (99.9%): [5.398, 12.997] (assumes normal distribution)


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
# Warmup Iteration   1: 3.093 ops/ms
# Warmup Iteration   2: 8.840 ops/ms
# Warmup Iteration   3: 9.402 ops/ms
Iteration   1: 9.735 ops/ms
Iteration   2: 9.378 ops/ms
Iteration   3: 9.655 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.589 ±(99.9%) 3.421 ops/ms [Average]
  (min, avg, max) = (9.378, 9.589, 9.735), stdev = 0.187
  CI (99.9%): [6.169, 13.010] (assumes normal distribution)


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
# Warmup Iteration   1: 3.061 ops/ms
# Warmup Iteration   2: 7.939 ops/ms
# Warmup Iteration   3: 9.125 ops/ms
Iteration   1: 9.196 ops/ms
Iteration   2: 9.424 ops/ms
Iteration   3: 9.389 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.336 ±(99.9%) 2.239 ops/ms [Average]
  (min, avg, max) = (9.196, 9.336, 9.424), stdev = 0.123
  CI (99.9%): [7.098, 11.575] (assumes normal distribution)


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
# Warmup Iteration   1: 3.008 ops/ms
# Warmup Iteration   2: 7.511 ops/ms
# Warmup Iteration   3: 7.821 ops/ms
Iteration   1: 7.915 ops/ms
Iteration   2: 7.941 ops/ms
Iteration   3: 7.910 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.922 ±(99.9%) 0.302 ops/ms [Average]
  (min, avg, max) = (7.910, 7.922, 7.941), stdev = 0.017
  CI (99.9%): [7.620, 8.224] (assumes normal distribution)


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
# Warmup Iteration   1: 10.738 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 3.869 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.653 ±(99.9%) 0.007 ms/op
Iteration   1: 3.540 ±(99.9%) 0.007 ms/op
Iteration   2: 3.439 ±(99.9%) 0.007 ms/op
Iteration   3: 3.609 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.529 ±(99.9%) 1.553 ms/op [Average]
  (min, avg, max) = (3.439, 3.529, 3.609), stdev = 0.085
  CI (99.9%): [1.977, 5.082] (assumes normal distribution)


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
# Warmup Iteration   1: 7.790 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 3.607 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.308 ±(99.9%) 0.002 ms/op
Iteration   1: 3.354 ±(99.9%) 0.002 ms/op
Iteration   2: 3.283 ±(99.9%) 0.002 ms/op
Iteration   3: 3.346 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.328 ±(99.9%) 0.711 ms/op [Average]
  (min, avg, max) = (3.283, 3.328, 3.354), stdev = 0.039
  CI (99.9%): [2.617, 4.038] (assumes normal distribution)


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
# Warmup Iteration   1: 9.247 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.736 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.586 ±(99.9%) 0.003 ms/op
Iteration   1: 3.453 ±(99.9%) 0.008 ms/op
Iteration   2: 3.389 ±(99.9%) 0.004 ms/op
Iteration   3: 3.417 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.420 ±(99.9%) 0.586 ms/op [Average]
  (min, avg, max) = (3.389, 3.420, 3.453), stdev = 0.032
  CI (99.9%): [2.834, 4.006] (assumes normal distribution)


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
# Warmup Iteration   1: 10.307 ±(99.9%) 0.055 ms/op
# Warmup Iteration   2: 4.683 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.079 ±(99.9%) 0.008 ms/op
Iteration   1: 4.182 ±(99.9%) 0.008 ms/op
Iteration   2: 4.073 ±(99.9%) 0.008 ms/op
Iteration   3: 4.030 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.095 ±(99.9%) 1.435 ms/op [Average]
  (min, avg, max) = (4.030, 4.095, 4.182), stdev = 0.079
  CI (99.9%): [2.660, 5.530] (assumes normal distribution)


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
# Warmup Iteration   1: 9.776 ±(99.9%) 0.125 ms/op
# Warmup Iteration   2: 4.326 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 3.498 ±(99.9%) 0.010 ms/op
Iteration   1: 3.544 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   0.364 ms/op
                 createUser·p0.50:   3.310 ms/op
                 createUser·p0.90:   4.375 ms/op
                 createUser·p0.95:   4.776 ms/op
                 createUser·p0.99:   6.514 ms/op
                 createUser·p0.999:  20.462 ms/op
                 createUser·p0.9999: 38.863 ms/op
                 createUser·p1.00:   40.042 ms/op

Iteration   2: 3.492 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.593 ms/op
                 createUser·p0.50:   3.330 ms/op
                 createUser·p0.90:   4.084 ms/op
                 createUser·p0.95:   4.415 ms/op
                 createUser·p0.99:   6.636 ms/op
                 createUser·p0.999:  22.442 ms/op
                 createUser·p0.9999: 25.685 ms/op
                 createUser·p1.00:   26.608 ms/op

Iteration   3: 3.523 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.503 ms/op
                 createUser·p0.50:   3.367 ms/op
                 createUser·p0.90:   4.071 ms/op
                 createUser·p0.95:   4.596 ms/op
                 createUser·p0.99:   6.267 ms/op
                 createUser·p0.999:  21.433 ms/op
                 createUser·p0.9999: 29.911 ms/op
                 createUser·p1.00:   31.359 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 272861
  mean =      3.519 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 262975 
    [ 5.000, 10.000) = 9389 
    [10.000, 15.000) = 179 
    [15.000, 20.000) = 16 
    [20.000, 25.000) = 174 
    [25.000, 30.000) = 88 
    [30.000, 35.000) = 8 
    [35.000, 40.000) = 31 
    [40.000, 45.000) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.364 ms/op
     p(50.0000) =      3.338 ms/op
     p(90.0000) =      4.162 ms/op
     p(95.0000) =      4.628 ms/op
     p(99.0000) =      6.463 ms/op
     p(99.9000) =     21.234 ms/op
     p(99.9900) =     36.045 ms/op
     p(99.9990) =     38.994 ms/op
     p(99.9999) =     40.042 ms/op
    p(100.0000) =     40.042 ms/op


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
# Warmup Iteration   1: 8.263 ±(99.9%) 0.113 ms/op
# Warmup Iteration   2: 3.645 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.365 ±(99.9%) 0.009 ms/op
Iteration   1: 3.328 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.352 ms/op
                 existUser·p0.50:   3.133 ms/op
                 existUser·p0.90:   3.805 ms/op
                 existUser·p0.95:   4.751 ms/op
                 existUser·p0.99:   5.988 ms/op
                 existUser·p0.999:  18.576 ms/op
                 existUser·p0.9999: 22.295 ms/op
                 existUser·p1.00:   22.610 ms/op

Iteration   2: 3.317 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.208 ms/op
                 existUser·p0.50:   3.244 ms/op
                 existUser·p0.90:   3.666 ms/op
                 existUser·p0.95:   4.076 ms/op
                 existUser·p0.99:   5.841 ms/op
                 existUser·p0.999:  10.207 ms/op
                 existUser·p0.9999: 25.210 ms/op
                 existUser·p1.00:   25.690 ms/op

Iteration   3: 3.304 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.731 ms/op
                 existUser·p0.50:   3.183 ms/op
                 existUser·p0.90:   3.613 ms/op
                 existUser·p0.95:   3.977 ms/op
                 existUser·p0.99:   6.067 ms/op
                 existUser·p0.999:  14.437 ms/op
                 existUser·p0.9999: 25.253 ms/op
                 existUser·p1.00:   26.837 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 289200
  mean =      3.317 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11394 
    [ 2.500,  5.000) = 270818 
    [ 5.000,  7.500) = 5651 
    [ 7.500, 10.000) = 986 
    [10.000, 12.500) = 91 
    [12.500, 15.000) = 4 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 31 
    [20.000, 22.500) = 98 
    [22.500, 25.000) = 93 
    [25.000, 27.500) = 34 

  Percentiles, ms/op:
      p(0.0000) =      0.731 ms/op
     p(50.0000) =      3.199 ms/op
     p(90.0000) =      3.682 ms/op
     p(95.0000) =      4.227 ms/op
     p(99.0000) =      5.906 ms/op
     p(99.9000) =     10.712 ms/op
     p(99.9900) =     25.068 ms/op
     p(99.9990) =     25.907 ms/op
     p(99.9999) =     26.837 ms/op
    p(100.0000) =     26.837 ms/op


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
# Warmup Iteration   1: 9.106 ±(99.9%) 0.115 ms/op
# Warmup Iteration   2: 3.826 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.545 ±(99.9%) 0.012 ms/op
Iteration   1: 3.509 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.956 ms/op
                 getUser·p0.50:   3.310 ms/op
                 getUser·p0.90:   3.797 ms/op
                 getUser·p0.95:   5.243 ms/op
                 getUser·p0.99:   7.274 ms/op
                 getUser·p0.999:  19.853 ms/op
                 getUser·p0.9999: 22.049 ms/op
                 getUser·p1.00:   23.167 ms/op

Iteration   2: 3.643 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.753 ms/op
                 getUser·p0.50:   3.453 ms/op
                 getUser·p0.90:   4.190 ms/op
                 getUser·p0.95:   5.161 ms/op
                 getUser·p0.99:   7.138 ms/op
                 getUser·p0.999:  22.053 ms/op
                 getUser·p0.9999: 24.813 ms/op
                 getUser·p1.00:   26.345 ms/op

Iteration   3: 3.502 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   0.985 ms/op
                 getUser·p0.50:   3.338 ms/op
                 getUser·p0.90:   3.813 ms/op
                 getUser·p0.95:   4.915 ms/op
                 getUser·p0.99:   6.808 ms/op
                 getUser·p0.999:  20.403 ms/op
                 getUser·p0.9999: 26.706 ms/op
                 getUser·p1.00:   27.263 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 270118
  mean =      3.550 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5482 
    [ 2.500,  5.000) = 250884 
    [ 5.000,  7.500) = 11563 
    [ 7.500, 10.000) = 1575 
    [10.000, 12.500) = 225 
    [12.500, 15.000) = 68 
    [15.000, 17.500) = 11 
    [17.500, 20.000) = 41 
    [20.000, 22.500) = 123 
    [22.500, 25.000) = 97 
    [25.000, 27.500) = 49 

  Percentiles, ms/op:
      p(0.0000) =      0.985 ms/op
     p(50.0000) =      3.367 ms/op
     p(90.0000) =      3.969 ms/op
     p(95.0000) =      5.038 ms/op
     p(99.0000) =      7.111 ms/op
     p(99.9000) =     19.988 ms/op
     p(99.9900) =     25.886 ms/op
     p(99.9990) =     26.974 ms/op
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
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 10.799 ±(99.9%) 0.138 ms/op
# Warmup Iteration   2: 4.453 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.207 ±(99.9%) 0.014 ms/op
Iteration   1: 4.117 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.649 ms/op
                 listUser·p0.50:   3.895 ms/op
                 listUser·p0.90:   4.514 ms/op
                 listUser·p0.95:   5.120 ms/op
                 listUser·p0.99:   8.387 ms/op
                 listUser·p0.999:  22.989 ms/op
                 listUser·p0.9999: 33.174 ms/op
                 listUser·p1.00:   33.817 ms/op

Iteration   2: 4.022 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.944 ms/op
                 listUser·p0.50:   3.891 ms/op
                 listUser·p0.90:   4.350 ms/op
                 listUser·p0.95:   4.571 ms/op
                 listUser·p0.99:   7.242 ms/op
                 listUser·p0.999:  15.611 ms/op
                 listUser·p0.9999: 17.958 ms/op
                 listUser·p1.00:   18.383 ms/op

Iteration   3: 4.078 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.261 ms/op
                 listUser·p0.50:   3.973 ms/op
                 listUser·p0.90:   4.383 ms/op
                 listUser·p0.95:   4.620 ms/op
                 listUser·p0.99:   7.512 ms/op
                 listUser·p0.999:  15.057 ms/op
                 listUser·p0.9999: 18.416 ms/op
                 listUser·p1.00:   19.366 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 235784
  mean =      4.072 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 41 
    [ 2.500,  5.000) = 226711 
    [ 5.000,  7.500) = 6339 
    [ 7.500, 10.000) = 1753 
    [10.000, 12.500) = 367 
    [12.500, 15.000) = 229 
    [15.000, 17.500) = 170 
    [17.500, 20.000) = 57 
    [20.000, 22.500) = 27 
    [22.500, 25.000) = 49 
    [25.000, 27.500) = 9 
    [27.500, 30.000) = 2 
    [30.000, 32.500) = 18 
    [32.500, 35.000) = 12 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.649 ms/op
     p(50.0000) =      3.920 ms/op
     p(90.0000) =      4.407 ms/op
     p(95.0000) =      4.702 ms/op
     p(99.0000) =      7.792 ms/op
     p(99.9000) =     16.286 ms/op
     p(99.9900) =     30.685 ms/op
     p(99.9990) =     33.817 ms/op
     p(99.9999) =     33.817 ms/op
    p(100.0000) =     33.817 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.197 ± 3.799  ops/ms
ClientPb.existUser                       thrpt       3   9.589 ± 3.421  ops/ms
ClientPb.getUser                         thrpt       3   9.336 ± 2.239  ops/ms
ClientPb.listUser                        thrpt       3   7.922 ± 0.302  ops/ms
ClientPb.createUser                       avgt       3   3.529 ± 1.553   ms/op
ClientPb.existUser                        avgt       3   3.328 ± 0.711   ms/op
ClientPb.getUser                          avgt       3   3.420 ± 0.586   ms/op
ClientPb.listUser                         avgt       3   4.095 ± 1.435   ms/op
ClientPb.createUser                     sample  272861   3.519 ± 0.007   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.364           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.338           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.162           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.628           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.463           ms/op
ClientPb.createUser:createUser·p0.999   sample          21.234           ms/op
ClientPb.createUser:createUser·p0.9999  sample          36.045           ms/op
ClientPb.createUser:createUser·p1.00    sample          40.042           ms/op
ClientPb.existUser                      sample  289200   3.317 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.731           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.199           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.682           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.227           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.906           ms/op
ClientPb.existUser:existUser·p0.999     sample          10.712           ms/op
ClientPb.existUser:existUser·p0.9999    sample          25.068           ms/op
ClientPb.existUser:existUser·p1.00      sample          26.837           ms/op
ClientPb.getUser                        sample  270118   3.550 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.985           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.367           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.969           ms/op
ClientPb.getUser:getUser·p0.95          sample           5.038           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.111           ms/op
ClientPb.getUser:getUser·p0.999         sample          19.988           ms/op
ClientPb.getUser:getUser·p0.9999        sample          25.886           ms/op
ClientPb.getUser:getUser·p1.00          sample          27.263           ms/op
ClientPb.listUser                       sample  235784   4.072 ± 0.007   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.649           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.920           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.407           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.702           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.792           ms/op
ClientPb.listUser:listUser·p0.999       sample          16.286           ms/op
ClientPb.listUser:listUser·p0.9999      sample          30.685           ms/op
ClientPb.listUser:listUser·p1.00        sample          33.817           ms/op
