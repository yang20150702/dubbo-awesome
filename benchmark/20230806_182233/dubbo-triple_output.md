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
# Warmup Iteration   1: 2.734 ops/ms
# Warmup Iteration   2: 6.681 ops/ms
# Warmup Iteration   3: 9.195 ops/ms
Iteration   1: 9.568 ops/ms
Iteration   2: 10.034 ops/ms
Iteration   3: 10.168 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.924 ±(99.9%) 5.745 ops/ms [Average]
  (min, avg, max) = (9.568, 9.924, 10.168), stdev = 0.315
  CI (99.9%): [4.179, 15.668] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.347 ops/ms
# Warmup Iteration   2: 9.672 ops/ms
# Warmup Iteration   3: 10.538 ops/ms
Iteration   1: 10.356 ops/ms
Iteration   2: 10.279 ops/ms
Iteration   3: 10.029 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.221 ±(99.9%) 3.122 ops/ms [Average]
  (min, avg, max) = (10.029, 10.221, 10.356), stdev = 0.171
  CI (99.9%): [7.099, 13.344] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:50
# Fork: 1 of 1
# Warmup Iteration   1: 3.591 ops/ms
# Warmup Iteration   2: 9.160 ops/ms
# Warmup Iteration   3: 9.894 ops/ms
Iteration   1: 9.839 ops/ms
Iteration   2: 10.037 ops/ms
Iteration   3: 9.650 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.842 ±(99.9%) 3.537 ops/ms [Average]
  (min, avg, max) = (9.650, 9.842, 10.037), stdev = 0.194
  CI (99.9%): [6.305, 13.379] (assumes normal distribution)


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
# Warmup Iteration   1: 3.336 ops/ms
# Warmup Iteration   2: 7.743 ops/ms
# Warmup Iteration   3: 8.408 ops/ms
Iteration   1: 8.699 ops/ms
Iteration   2: 8.397 ops/ms
Iteration   3: 8.285 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.460 ±(99.9%) 3.901 ops/ms [Average]
  (min, avg, max) = (8.285, 8.460, 8.699), stdev = 0.214
  CI (99.9%): [4.560, 12.361] (assumes normal distribution)


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
# Warmup Iteration   1: 8.094 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 3.553 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.331 ±(99.9%) 0.002 ms/op
Iteration   1: 3.306 ±(99.9%) 0.006 ms/op
Iteration   2: 3.165 ±(99.9%) 0.006 ms/op
Iteration   3: 3.143 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.205 ±(99.9%) 1.617 ms/op [Average]
  (min, avg, max) = (3.143, 3.205, 3.306), stdev = 0.089
  CI (99.9%): [1.588, 4.821] (assumes normal distribution)


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
# Warmup Iteration   1: 6.519 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 3.493 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.200 ±(99.9%) 0.004 ms/op
Iteration   1: 3.119 ±(99.9%) 0.003 ms/op
Iteration   2: 3.153 ±(99.9%) 0.004 ms/op
Iteration   3: 3.097 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.123 ±(99.9%) 0.516 ms/op [Average]
  (min, avg, max) = (3.097, 3.123, 3.153), stdev = 0.028
  CI (99.9%): [2.607, 3.639] (assumes normal distribution)


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
# Warmup Iteration   1: 7.484 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 3.388 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.277 ±(99.9%) 0.002 ms/op
Iteration   1: 3.187 ±(99.9%) 0.003 ms/op
Iteration   2: 3.184 ±(99.9%) 0.004 ms/op
Iteration   3: 3.227 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.199 ±(99.9%) 0.438 ms/op [Average]
  (min, avg, max) = (3.184, 3.199, 3.227), stdev = 0.024
  CI (99.9%): [2.761, 3.638] (assumes normal distribution)


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
# Warmup Iteration   1: 7.783 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 4.039 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.908 ±(99.9%) 0.004 ms/op
Iteration   1: 3.717 ±(99.9%) 0.010 ms/op
Iteration   2: 3.814 ±(99.9%) 0.004 ms/op
Iteration   3: 3.787 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.773 ±(99.9%) 0.914 ms/op [Average]
  (min, avg, max) = (3.717, 3.773, 3.814), stdev = 0.050
  CI (99.9%): [2.859, 4.687] (assumes normal distribution)


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
# Warmup Iteration   1: 7.838 ±(99.9%) 0.091 ms/op
# Warmup Iteration   2: 3.668 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.269 ±(99.9%) 0.009 ms/op
Iteration   1: 3.208 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.040 ms/op
                 createUser·p0.50:   3.043 ms/op
                 createUser·p0.90:   3.600 ms/op
                 createUser·p0.95:   3.928 ms/op
                 createUser·p0.99:   5.841 ms/op
                 createUser·p0.999:  15.849 ms/op
                 createUser·p0.9999: 19.596 ms/op
                 createUser·p1.00:   20.480 ms/op

Iteration   2: 3.165 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.458 ms/op
                 createUser·p0.50:   3.043 ms/op
                 createUser·p0.90:   3.473 ms/op
                 createUser·p0.95:   3.752 ms/op
                 createUser·p0.99:   5.825 ms/op
                 createUser·p0.999:  17.695 ms/op
                 createUser·p0.9999: 23.334 ms/op
                 createUser·p1.00:   23.986 ms/op

Iteration   3: 3.252 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.128 ms/op
                 createUser·p0.50:   3.199 ms/op
                 createUser·p0.90:   3.723 ms/op
                 createUser·p0.95:   4.211 ms/op
                 createUser·p0.99:   5.333 ms/op
                 createUser·p0.999:  15.147 ms/op
                 createUser·p0.9999: 22.621 ms/op
                 createUser·p1.00:   23.462 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 298891
  mean =      3.208 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14195 
    [ 2.500,  5.000) = 279429 
    [ 5.000,  7.500) = 3832 
    [ 7.500, 10.000) = 836 
    [10.000, 12.500) = 177 
    [12.500, 15.000) = 96 
    [15.000, 17.500) = 95 
    [17.500, 20.000) = 135 
    [20.000, 22.500) = 68 
    [22.500, 25.000) = 28 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.040 ms/op
     p(50.0000) =      3.101 ms/op
     p(90.0000) =      3.588 ms/op
     p(95.0000) =      3.981 ms/op
     p(99.0000) =      5.652 ms/op
     p(99.9000) =     15.978 ms/op
     p(99.9900) =     22.450 ms/op
     p(99.9990) =     23.921 ms/op
     p(99.9999) =     23.986 ms/op
    p(100.0000) =     23.986 ms/op


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
# Warmup Iteration   1: 6.951 ±(99.9%) 0.083 ms/op
# Warmup Iteration   2: 3.283 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.165 ±(99.9%) 0.009 ms/op
Iteration   1: 3.210 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.522 ms/op
                 existUser·p0.50:   3.105 ms/op
                 existUser·p0.90:   3.633 ms/op
                 existUser·p0.95:   4.227 ms/op
                 existUser·p0.99:   6.111 ms/op
                 existUser·p0.999:  15.916 ms/op
                 existUser·p0.9999: 18.877 ms/op
                 existUser·p1.00:   19.399 ms/op

Iteration   2: 3.163 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.380 ms/op
                 existUser·p0.50:   3.138 ms/op
                 existUser·p0.90:   3.482 ms/op
                 existUser·p0.95:   3.781 ms/op
                 existUser·p0.99:   5.448 ms/op
                 existUser·p0.999:  9.486 ms/op
                 existUser·p0.9999: 21.820 ms/op
                 existUser·p1.00:   22.970 ms/op

Iteration   3: 3.169 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.503 ms/op
                 existUser·p0.50:   3.150 ms/op
                 existUser·p0.90:   3.359 ms/op
                 existUser·p0.95:   3.756 ms/op
                 existUser·p0.99:   6.013 ms/op
                 existUser·p0.999:  12.847 ms/op
                 existUser·p0.9999: 24.526 ms/op
                 existUser·p1.00:   27.460 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 301629
  mean =      3.181 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 26387 
    [ 2.500,  5.000) = 268231 
    [ 5.000,  7.500) = 5838 
    [ 7.500, 10.000) = 870 
    [10.000, 12.500) = 27 
    [12.500, 15.000) = 8 
    [15.000, 17.500) = 35 
    [17.500, 20.000) = 111 
    [20.000, 22.500) = 103 
    [22.500, 25.000) = 13 
    [25.000, 27.500) = 6 

  Percentiles, ms/op:
      p(0.0000) =      1.380 ms/op
     p(50.0000) =      3.133 ms/op
     p(90.0000) =      3.510 ms/op
     p(95.0000) =      3.932 ms/op
     p(99.0000) =      5.898 ms/op
     p(99.9000) =     10.011 ms/op
     p(99.9900) =     21.884 ms/op
     p(99.9990) =     27.290 ms/op
     p(99.9999) =     27.460 ms/op
    p(100.0000) =     27.460 ms/op


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
# Warmup Iteration   1: 7.308 ±(99.9%) 0.085 ms/op
# Warmup Iteration   2: 3.497 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.427 ±(99.9%) 0.012 ms/op
Iteration   1: 3.172 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.081 ms/op
                 getUser·p0.50:   3.101 ms/op
                 getUser·p0.90:   3.564 ms/op
                 getUser·p0.95:   3.928 ms/op
                 getUser·p0.99:   5.865 ms/op
                 getUser·p0.999:  11.718 ms/op
                 getUser·p0.9999: 20.739 ms/op
                 getUser·p1.00:   21.135 ms/op

Iteration   2: 3.296 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.044 ms/op
                 getUser·p0.50:   3.170 ms/op
                 getUser·p0.90:   3.752 ms/op
                 getUser·p0.95:   4.432 ms/op
                 getUser·p0.99:   6.218 ms/op
                 getUser·p0.999:  10.530 ms/op
                 getUser·p0.9999: 22.606 ms/op
                 getUser·p1.00:   23.855 ms/op

Iteration   3: 3.164 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.098 ms/op
                 getUser·p0.50:   3.031 ms/op
                 getUser·p0.90:   3.424 ms/op
                 getUser·p0.95:   3.637 ms/op
                 getUser·p0.99:   5.775 ms/op
                 getUser·p0.999:  14.543 ms/op
                 getUser·p0.9999: 27.260 ms/op
                 getUser·p1.00:   28.672 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 299009
  mean =      3.209 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13661 
    [ 2.500,  5.000) = 277562 
    [ 5.000,  7.500) = 6418 
    [ 7.500, 10.000) = 929 
    [10.000, 12.500) = 122 
    [12.500, 15.000) = 28 
    [15.000, 17.500) = 25 
    [17.500, 20.000) = 72 
    [20.000, 22.500) = 149 
    [22.500, 25.000) = 11 
    [25.000, 27.500) = 29 

  Percentiles, ms/op:
      p(0.0000) =      1.044 ms/op
     p(50.0000) =      3.088 ms/op
     p(90.0000) =      3.584 ms/op
     p(95.0000) =      3.990 ms/op
     p(99.0000) =      5.947 ms/op
     p(99.9000) =     14.204 ms/op
     p(99.9900) =     25.759 ms/op
     p(99.9990) =     27.591 ms/op
     p(99.9999) =     28.672 ms/op
    p(100.0000) =     28.672 ms/op


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
# Warmup Iteration   1: 9.582 ±(99.9%) 0.115 ms/op
# Warmup Iteration   2: 4.132 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.803 ±(99.9%) 0.012 ms/op
Iteration   1: 3.793 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.085 ms/op
                 listUser·p0.50:   3.621 ms/op
                 listUser·p0.90:   4.076 ms/op
                 listUser·p0.95:   4.342 ms/op
                 listUser·p0.99:   7.791 ms/op
                 listUser·p0.999:  14.025 ms/op
                 listUser·p0.9999: 18.406 ms/op
                 listUser·p1.00:   19.071 ms/op

Iteration   2: 3.843 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.134 ms/op
                 listUser·p0.50:   3.695 ms/op
                 listUser·p0.90:   4.141 ms/op
                 listUser·p0.95:   4.940 ms/op
                 listUser·p0.99:   8.173 ms/op
                 listUser·p0.999:  14.660 ms/op
                 listUser·p0.9999: 17.400 ms/op
                 listUser·p1.00:   17.433 ms/op

Iteration   3: 3.801 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.171 ms/op
                 listUser·p0.50:   3.625 ms/op
                 listUser·p0.90:   4.162 ms/op
                 listUser·p0.95:   4.415 ms/op
                 listUser·p0.99:   7.553 ms/op
                 listUser·p0.999:  13.418 ms/op
                 listUser·p0.9999: 18.842 ms/op
                 listUser·p1.00:   21.135 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 251647
  mean =      3.812 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 79 
    [ 2.500,  5.000) = 241614 
    [ 5.000,  7.500) = 6811 
    [ 7.500, 10.000) = 2354 
    [10.000, 12.500) = 341 
    [12.500, 15.000) = 274 
    [15.000, 17.500) = 137 
    [17.500, 20.000) = 36 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.085 ms/op
     p(50.0000) =      3.670 ms/op
     p(90.0000) =      4.125 ms/op
     p(95.0000) =      4.489 ms/op
     p(99.0000) =      7.860 ms/op
     p(99.9000) =     14.238 ms/op
     p(99.9900) =     18.350 ms/op
     p(99.9990) =     19.037 ms/op
     p(99.9999) =     21.135 ms/op
    p(100.0000) =     21.135 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.924 ± 5.745  ops/ms
ClientPb.existUser                       thrpt       3  10.221 ± 3.122  ops/ms
ClientPb.getUser                         thrpt       3   9.842 ± 3.537  ops/ms
ClientPb.listUser                        thrpt       3   8.460 ± 3.901  ops/ms
ClientPb.createUser                       avgt       3   3.205 ± 1.617   ms/op
ClientPb.existUser                        avgt       3   3.123 ± 0.516   ms/op
ClientPb.getUser                          avgt       3   3.199 ± 0.438   ms/op
ClientPb.listUser                         avgt       3   3.773 ± 0.914   ms/op
ClientPb.createUser                     sample  298891   3.208 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.040           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.101           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.588           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.981           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.652           ms/op
ClientPb.createUser:createUser·p0.999   sample          15.978           ms/op
ClientPb.createUser:createUser·p0.9999  sample          22.450           ms/op
ClientPb.createUser:createUser·p1.00    sample          23.986           ms/op
ClientPb.existUser                      sample  301629   3.181 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.380           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.133           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.510           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.932           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.898           ms/op
ClientPb.existUser:existUser·p0.999     sample          10.011           ms/op
ClientPb.existUser:existUser·p0.9999    sample          21.884           ms/op
ClientPb.existUser:existUser·p1.00      sample          27.460           ms/op
ClientPb.getUser                        sample  299009   3.209 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.044           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.088           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.584           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.990           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.947           ms/op
ClientPb.getUser:getUser·p0.999         sample          14.204           ms/op
ClientPb.getUser:getUser·p0.9999        sample          25.759           ms/op
ClientPb.getUser:getUser·p1.00          sample          28.672           ms/op
ClientPb.listUser                       sample  251647   3.812 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.085           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.670           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.125           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.489           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.860           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.238           ms/op
ClientPb.listUser:listUser·p0.9999      sample          18.350           ms/op
ClientPb.listUser:listUser·p1.00        sample          21.135           ms/op
