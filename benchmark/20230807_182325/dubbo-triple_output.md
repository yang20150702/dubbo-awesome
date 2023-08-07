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
# Warmup Iteration   1: 2.152 ops/ms
# Warmup Iteration   2: 5.659 ops/ms
# Warmup Iteration   3: 8.346 ops/ms
Iteration   1: 8.950 ops/ms
Iteration   2: 9.196 ops/ms
Iteration   3: 9.393 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.180 ±(99.9%) 4.053 ops/ms [Average]
  (min, avg, max) = (8.950, 9.180, 9.393), stdev = 0.222
  CI (99.9%): [5.127, 13.232] (assumes normal distribution)


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
# Warmup Iteration   1: 2.879 ops/ms
# Warmup Iteration   2: 8.781 ops/ms
# Warmup Iteration   3: 9.819 ops/ms
Iteration   1: 9.473 ops/ms
Iteration   2: 9.807 ops/ms
Iteration   3: 9.109 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.463 ±(99.9%) 6.370 ops/ms [Average]
  (min, avg, max) = (9.109, 9.463, 9.807), stdev = 0.349
  CI (99.9%): [3.092, 15.833] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 3.259 ops/ms
# Warmup Iteration   2: 8.259 ops/ms
# Warmup Iteration   3: 8.791 ops/ms
Iteration   1: 8.889 ops/ms
Iteration   2: 9.197 ops/ms
Iteration   3: 9.185 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.090 ±(99.9%) 3.187 ops/ms [Average]
  (min, avg, max) = (8.889, 9.090, 9.197), stdev = 0.175
  CI (99.9%): [5.904, 12.277] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:48
# Fork: 1 of 1
# Warmup Iteration   1: 3.067 ops/ms
# Warmup Iteration   2: 7.176 ops/ms
# Warmup Iteration   3: 7.749 ops/ms
Iteration   1: 7.957 ops/ms
Iteration   2: 7.780 ops/ms
Iteration   3: 7.958 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.898 ±(99.9%) 1.864 ops/ms [Average]
  (min, avg, max) = (7.780, 7.898, 7.958), stdev = 0.102
  CI (99.9%): [6.034, 9.763] (assumes normal distribution)


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
# Warmup Iteration   1: 10.587 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 3.814 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.582 ±(99.9%) 0.007 ms/op
Iteration   1: 3.585 ±(99.9%) 0.007 ms/op
Iteration   2: 3.726 ±(99.9%) 0.005 ms/op
Iteration   3: 3.462 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.591 ±(99.9%) 2.407 ms/op [Average]
  (min, avg, max) = (3.462, 3.591, 3.726), stdev = 0.132
  CI (99.9%): [1.184, 5.998] (assumes normal distribution)


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
# Warmup Iteration   1: 7.751 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.597 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.277 ±(99.9%) 0.010 ms/op
Iteration   1: 3.396 ±(99.9%) 0.007 ms/op
Iteration   2: 3.418 ±(99.9%) 0.006 ms/op
Iteration   3: 3.342 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.385 ±(99.9%) 0.718 ms/op [Average]
  (min, avg, max) = (3.342, 3.385, 3.418), stdev = 0.039
  CI (99.9%): [2.667, 4.104] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 10.064 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.789 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.606 ±(99.9%) 0.006 ms/op
Iteration   1: 3.492 ±(99.9%) 0.007 ms/op
Iteration   2: 3.406 ±(99.9%) 0.006 ms/op
Iteration   3: 3.598 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.499 ±(99.9%) 1.754 ms/op [Average]
  (min, avg, max) = (3.406, 3.499, 3.598), stdev = 0.096
  CI (99.9%): [1.745, 5.253] (assumes normal distribution)


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
# Warmup Iteration   1: 11.269 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 4.599 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.115 ±(99.9%) 0.007 ms/op
Iteration   1: 4.065 ±(99.9%) 0.006 ms/op
Iteration   2: 4.051 ±(99.9%) 0.011 ms/op
Iteration   3: 4.139 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.085 ±(99.9%) 0.870 ms/op [Average]
  (min, avg, max) = (4.051, 4.085, 4.139), stdev = 0.048
  CI (99.9%): [3.214, 4.955] (assumes normal distribution)


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
# Warmup Iteration   1: 8.973 ±(99.9%) 0.115 ms/op
# Warmup Iteration   2: 4.021 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.643 ±(99.9%) 0.011 ms/op
Iteration   1: 3.382 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.202 ms/op
                 createUser·p0.50:   3.232 ms/op
                 createUser·p0.90:   3.801 ms/op
                 createUser·p0.95:   4.190 ms/op
                 createUser·p0.99:   6.070 ms/op
                 createUser·p0.999:  20.640 ms/op
                 createUser·p0.9999: 22.500 ms/op
                 createUser·p1.00:   23.855 ms/op

Iteration   2: 3.443 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.634 ms/op
                 createUser·p0.50:   3.338 ms/op
                 createUser·p0.90:   3.842 ms/op
                 createUser·p0.95:   4.432 ms/op
                 createUser·p0.99:   6.210 ms/op
                 createUser·p0.999:  21.991 ms/op
                 createUser·p0.9999: 26.172 ms/op
                 createUser·p1.00:   28.246 ms/op

Iteration   3: 3.585 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.210 ms/op
                 createUser·p0.50:   3.445 ms/op
                 createUser·p0.90:   4.133 ms/op
                 createUser·p0.95:   4.522 ms/op
                 createUser·p0.99:   6.676 ms/op
                 createUser·p0.999:  20.312 ms/op
                 createUser·p0.9999: 24.709 ms/op
                 createUser·p1.00:   25.395 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 276735
  mean =      3.468 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10936 
    [ 2.500,  5.000) = 256520 
    [ 5.000,  7.500) = 7700 
    [ 7.500, 10.000) = 979 
    [10.000, 12.500) = 244 
    [12.500, 15.000) = 40 
    [15.000, 17.500) = 3 
    [17.500, 20.000) = 27 
    [20.000, 22.500) = 155 
    [22.500, 25.000) = 95 
    [25.000, 27.500) = 31 

  Percentiles, ms/op:
      p(0.0000) =      1.202 ms/op
     p(50.0000) =      3.342 ms/op
     p(90.0000) =      3.953 ms/op
     p(95.0000) =      4.391 ms/op
     p(99.0000) =      6.316 ms/op
     p(99.9000) =     20.480 ms/op
     p(99.9900) =     25.417 ms/op
     p(99.9990) =     28.188 ms/op
     p(99.9999) =     28.246 ms/op
    p(100.0000) =     28.246 ms/op


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
# Warmup Iteration   1: 7.938 ±(99.9%) 0.114 ms/op
# Warmup Iteration   2: 3.540 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.377 ±(99.9%) 0.009 ms/op
Iteration   1: 3.296 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.606 ms/op
                 existUser·p0.50:   3.170 ms/op
                 existUser·p0.90:   3.576 ms/op
                 existUser·p0.95:   3.809 ms/op
                 existUser·p0.99:   6.054 ms/op
                 existUser·p0.999:  10.758 ms/op
                 existUser·p0.9999: 28.153 ms/op
                 existUser·p1.00:   29.098 ms/op

Iteration   2: 3.336 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.065 ms/op
                 existUser·p0.50:   3.260 ms/op
                 existUser·p0.90:   3.727 ms/op
                 existUser·p0.95:   4.104 ms/op
                 existUser·p0.99:   5.554 ms/op
                 existUser·p0.999:  21.603 ms/op
                 existUser·p0.9999: 26.884 ms/op
                 existUser·p1.00:   27.787 ms/op

Iteration   3: 3.391 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.430 ms/op
                 existUser·p0.50:   3.346 ms/op
                 existUser·p0.90:   3.686 ms/op
                 existUser·p0.95:   4.252 ms/op
                 existUser·p0.99:   5.800 ms/op
                 existUser·p0.999:  17.957 ms/op
                 existUser·p0.9999: 25.282 ms/op
                 existUser·p1.00:   26.608 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 287130
  mean =      3.341 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10384 
    [ 2.500,  5.000) = 269639 
    [ 5.000,  7.500) = 5972 
    [ 7.500, 10.000) = 806 
    [10.000, 12.500) = 40 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 35 
    [20.000, 22.500) = 87 
    [22.500, 25.000) = 110 
    [25.000, 27.500) = 33 

  Percentiles, ms/op:
      p(0.0000) =      1.065 ms/op
     p(50.0000) =      3.256 ms/op
     p(90.0000) =      3.654 ms/op
     p(95.0000) =      4.071 ms/op
     p(99.0000) =      5.800 ms/op
     p(99.9000) =     17.944 ms/op
     p(99.9900) =     27.460 ms/op
     p(99.9990) =     28.971 ms/op
     p(99.9999) =     29.098 ms/op
    p(100.0000) =     29.098 ms/op


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
# Warmup Iteration   1: 9.587 ±(99.9%) 0.123 ms/op
# Warmup Iteration   2: 3.785 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.545 ±(99.9%) 0.010 ms/op
Iteration   1: 3.608 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.176 ms/op
                 getUser·p0.50:   3.277 ms/op
                 getUser·p0.90:   4.366 ms/op
                 getUser·p0.95:   5.538 ms/op
                 getUser·p0.99:   7.660 ms/op
                 getUser·p0.999:  21.285 ms/op
                 getUser·p0.9999: 26.771 ms/op
                 getUser·p1.00:   27.918 ms/op

Iteration   2: 3.529 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.096 ms/op
                 getUser·p0.50:   3.359 ms/op
                 getUser·p0.90:   4.030 ms/op
                 getUser·p0.95:   4.430 ms/op
                 getUser·p0.99:   6.873 ms/op
                 getUser·p0.999:  21.727 ms/op
                 getUser·p0.9999: 25.821 ms/op
                 getUser·p1.00:   26.771 ms/op

Iteration   3: 3.477 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.432 ms/op
                 getUser·p0.50:   3.322 ms/op
                 getUser·p0.90:   3.805 ms/op
                 getUser·p0.95:   4.620 ms/op
                 getUser·p0.99:   6.840 ms/op
                 getUser·p0.999:  16.924 ms/op
                 getUser·p0.9999: 28.213 ms/op
                 getUser·p1.00:   29.032 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 271375
  mean =      3.537 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5747 
    [ 2.500,  5.000) = 253016 
    [ 5.000,  7.500) = 10516 
    [ 7.500, 10.000) = 1410 
    [10.000, 12.500) = 215 
    [12.500, 15.000) = 117 
    [15.000, 17.500) = 40 
    [17.500, 20.000) = 24 
    [20.000, 22.500) = 90 
    [22.500, 25.000) = 118 
    [25.000, 27.500) = 65 

  Percentiles, ms/op:
      p(0.0000) =      1.096 ms/op
     p(50.0000) =      3.326 ms/op
     p(90.0000) =      4.010 ms/op
     p(95.0000) =      4.899 ms/op
     p(99.0000) =      7.070 ms/op
     p(99.9000) =     20.730 ms/op
     p(99.9900) =     26.992 ms/op
     p(99.9990) =     28.742 ms/op
     p(99.9999) =     29.032 ms/op
    p(100.0000) =     29.032 ms/op


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
# Warmup Iteration   1: 9.464 ±(99.9%) 0.138 ms/op
# Warmup Iteration   2: 4.384 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.162 ±(99.9%) 0.012 ms/op
Iteration   1: 4.155 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.071 ms/op
                 listUser·p0.50:   4.010 ms/op
                 listUser·p0.90:   4.669 ms/op
                 listUser·p0.95:   5.112 ms/op
                 listUser·p0.99:   8.208 ms/op
                 listUser·p0.999:  17.596 ms/op
                 listUser·p0.9999: 23.953 ms/op
                 listUser·p1.00:   24.117 ms/op

Iteration   2: 4.212 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   2.515 ms/op
                 listUser·p0.50:   4.006 ms/op
                 listUser·p0.90:   4.669 ms/op
                 listUser·p0.95:   5.374 ms/op
                 listUser·p0.99:   8.405 ms/op
                 listUser·p0.999:  15.500 ms/op
                 listUser·p0.9999: 20.736 ms/op
                 listUser·p1.00:   21.266 ms/op

Iteration   3: 4.026 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.835 ms/op
                 listUser·p0.50:   3.863 ms/op
                 listUser·p0.90:   4.399 ms/op
                 listUser·p0.95:   4.637 ms/op
                 listUser·p0.99:   7.813 ms/op
                 listUser·p0.999:  14.451 ms/op
                 listUser·p0.9999: 17.024 ms/op
                 listUser·p1.00:   17.564 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 232403
  mean =      4.129 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 19 
    [ 2.500,  5.000) = 220793 
    [ 5.000,  7.500) = 8296 
    [ 7.500, 10.000) = 2423 
    [10.000, 12.500) = 334 
    [12.500, 15.000) = 271 
    [15.000, 17.500) = 134 
    [17.500, 20.000) = 85 
    [20.000, 22.500) = 31 
    [22.500, 25.000) = 17 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.071 ms/op
     p(50.0000) =      3.969 ms/op
     p(90.0000) =      4.579 ms/op
     p(95.0000) =      4.997 ms/op
     p(99.0000) =      8.208 ms/op
     p(99.9000) =     15.231 ms/op
     p(99.9900) =     21.972 ms/op
     p(99.9990) =     24.107 ms/op
     p(99.9999) =     24.117 ms/op
    p(100.0000) =     24.117 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.180 ± 4.053  ops/ms
ClientPb.existUser                       thrpt       3   9.463 ± 6.370  ops/ms
ClientPb.getUser                         thrpt       3   9.090 ± 3.187  ops/ms
ClientPb.listUser                        thrpt       3   7.898 ± 1.864  ops/ms
ClientPb.createUser                       avgt       3   3.591 ± 2.407   ms/op
ClientPb.existUser                        avgt       3   3.385 ± 0.718   ms/op
ClientPb.getUser                          avgt       3   3.499 ± 1.754   ms/op
ClientPb.listUser                         avgt       3   4.085 ± 0.870   ms/op
ClientPb.createUser                     sample  276735   3.468 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.202           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.342           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.953           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.391           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.316           ms/op
ClientPb.createUser:createUser·p0.999   sample          20.480           ms/op
ClientPb.createUser:createUser·p0.9999  sample          25.417           ms/op
ClientPb.createUser:createUser·p1.00    sample          28.246           ms/op
ClientPb.existUser                      sample  287130   3.341 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.065           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.256           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.654           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.071           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.800           ms/op
ClientPb.existUser:existUser·p0.999     sample          17.944           ms/op
ClientPb.existUser:existUser·p0.9999    sample          27.460           ms/op
ClientPb.existUser:existUser·p1.00      sample          29.098           ms/op
ClientPb.getUser                        sample  271375   3.537 ± 0.007   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.096           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.326           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.010           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.899           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.070           ms/op
ClientPb.getUser:getUser·p0.999         sample          20.730           ms/op
ClientPb.getUser:getUser·p0.9999        sample          26.992           ms/op
ClientPb.getUser:getUser·p1.00          sample          29.032           ms/op
ClientPb.listUser                       sample  232403   4.129 ± 0.007   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.071           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.969           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.579           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.997           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.208           ms/op
ClientPb.listUser:listUser·p0.999       sample          15.231           ms/op
ClientPb.listUser:listUser·p0.9999      sample          21.972           ms/op
ClientPb.listUser:listUser·p1.00        sample          24.117           ms/op
