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
# Warmup Iteration   1: 2.125 ops/ms
# Warmup Iteration   2: 4.973 ops/ms
# Warmup Iteration   3: 8.625 ops/ms
Iteration   1: 9.221 ops/ms
Iteration   2: 9.292 ops/ms
Iteration   3: 9.090 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.201 ±(99.9%) 1.876 ops/ms [Average]
  (min, avg, max) = (9.090, 9.201, 9.292), stdev = 0.103
  CI (99.9%): [7.325, 11.077] (assumes normal distribution)


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
# Warmup Iteration   1: 2.824 ops/ms
# Warmup Iteration   2: 8.824 ops/ms
# Warmup Iteration   3: 9.582 ops/ms
Iteration   1: 9.680 ops/ms
Iteration   2: 9.550 ops/ms
Iteration   3: 9.781 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.670 ±(99.9%) 2.121 ops/ms [Average]
  (min, avg, max) = (9.550, 9.670, 9.781), stdev = 0.116
  CI (99.9%): [7.550, 11.791] (assumes normal distribution)


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
# Warmup Iteration   1: 2.783 ops/ms
# Warmup Iteration   2: 7.672 ops/ms
# Warmup Iteration   3: 9.072 ops/ms
Iteration   1: 8.964 ops/ms
Iteration   2: 9.564 ops/ms
Iteration   3: 9.602 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.377 ±(99.9%) 6.530 ops/ms [Average]
  (min, avg, max) = (8.964, 9.377, 9.602), stdev = 0.358
  CI (99.9%): [2.847, 15.907] (assumes normal distribution)


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
# Warmup Iteration   1: 2.516 ops/ms
# Warmup Iteration   2: 6.886 ops/ms
# Warmup Iteration   3: 7.748 ops/ms
Iteration   1: 8.092 ops/ms
Iteration   2: 8.066 ops/ms
Iteration   3: 8.225 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.128 ±(99.9%) 1.560 ops/ms [Average]
  (min, avg, max) = (8.066, 8.128, 8.225), stdev = 0.086
  CI (99.9%): [6.568, 9.688] (assumes normal distribution)


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
# Warmup Iteration   1: 10.677 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 3.846 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.584 ±(99.9%) 0.005 ms/op
Iteration   1: 3.448 ±(99.9%) 0.006 ms/op
Iteration   2: 3.480 ±(99.9%) 0.012 ms/op
Iteration   3: 3.377 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.435 ±(99.9%) 0.967 ms/op [Average]
  (min, avg, max) = (3.377, 3.435, 3.480), stdev = 0.053
  CI (99.9%): [2.468, 4.403] (assumes normal distribution)


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
# Warmup Iteration   1: 8.896 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 3.620 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.349 ±(99.9%) 0.008 ms/op
Iteration   1: 3.249 ±(99.9%) 0.010 ms/op
Iteration   2: 3.187 ±(99.9%) 0.009 ms/op
Iteration   3: 3.324 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.253 ±(99.9%) 1.251 ms/op [Average]
  (min, avg, max) = (3.187, 3.253, 3.324), stdev = 0.069
  CI (99.9%): [2.002, 4.504] (assumes normal distribution)


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
# Warmup Iteration   1: 9.198 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 3.668 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.613 ±(99.9%) 0.007 ms/op
Iteration   1: 3.397 ±(99.9%) 0.008 ms/op
Iteration   2: 3.392 ±(99.9%) 0.010 ms/op
Iteration   3: 3.373 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.387 ±(99.9%) 0.235 ms/op [Average]
  (min, avg, max) = (3.373, 3.387, 3.397), stdev = 0.013
  CI (99.9%): [3.152, 3.623] (assumes normal distribution)


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
# Warmup Iteration   1: 10.842 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 4.479 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.027 ±(99.9%) 0.011 ms/op
Iteration   1: 3.956 ±(99.9%) 0.014 ms/op
Iteration   2: 3.971 ±(99.9%) 0.013 ms/op
Iteration   3: 3.894 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.940 ±(99.9%) 0.738 ms/op [Average]
  (min, avg, max) = (3.894, 3.940, 3.971), stdev = 0.040
  CI (99.9%): [3.202, 4.678] (assumes normal distribution)


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
# Warmup Iteration   1: 9.154 ±(99.9%) 0.125 ms/op
# Warmup Iteration   2: 3.894 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.475 ±(99.9%) 0.011 ms/op
Iteration   1: 3.438 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.069 ms/op
                 createUser·p0.50:   3.244 ms/op
                 createUser·p0.90:   3.912 ms/op
                 createUser·p0.95:   4.538 ms/op
                 createUser·p0.99:   6.734 ms/op
                 createUser·p0.999:  20.307 ms/op
                 createUser·p0.9999: 22.501 ms/op
                 createUser·p1.00:   23.265 ms/op

Iteration   2: 3.409 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.092 ms/op
                 createUser·p0.50:   3.387 ms/op
                 createUser·p0.90:   3.543 ms/op
                 createUser·p0.95:   4.108 ms/op
                 createUser·p0.99:   5.767 ms/op
                 createUser·p0.999:  21.699 ms/op
                 createUser·p0.9999: 27.316 ms/op
                 createUser·p1.00:   27.591 ms/op

Iteration   3: 3.431 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.718 ms/op
                 createUser·p0.50:   3.400 ms/op
                 createUser·p0.90:   3.809 ms/op
                 createUser·p0.95:   4.157 ms/op
                 createUser·p0.99:   5.923 ms/op
                 createUser·p0.999:  17.004 ms/op
                 createUser·p0.9999: 25.090 ms/op
                 createUser·p1.00:   26.411 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 280290
  mean =      3.426 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11865 
    [ 2.500,  5.000) = 260368 
    [ 5.000,  7.500) = 7298 
    [ 7.500, 10.000) = 412 
    [10.000, 12.500) = 59 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 14 
    [17.500, 20.000) = 19 
    [20.000, 22.500) = 128 
    [22.500, 25.000) = 80 
    [25.000, 27.500) = 46 

  Percentiles, ms/op:
      p(0.0000) =      1.069 ms/op
     p(50.0000) =      3.367 ms/op
     p(90.0000) =      3.781 ms/op
     p(95.0000) =      4.243 ms/op
     p(99.0000) =      6.227 ms/op
     p(99.9000) =     17.226 ms/op
     p(99.9900) =     26.212 ms/op
     p(99.9990) =     27.492 ms/op
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
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 9.914 ±(99.9%) 0.116 ms/op
# Warmup Iteration   2: 3.847 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.538 ±(99.9%) 0.009 ms/op
Iteration   1: 3.377 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.694 ms/op
                 existUser·p0.50:   3.265 ms/op
                 existUser·p0.90:   3.867 ms/op
                 existUser·p0.95:   4.293 ms/op
                 existUser·p0.99:   5.915 ms/op
                 existUser·p0.999:  19.600 ms/op
                 existUser·p0.9999: 22.843 ms/op
                 existUser·p1.00:   25.199 ms/op

Iteration   2: 3.346 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.165 ms/op
                 existUser·p0.50:   3.310 ms/op
                 existUser·p0.90:   3.682 ms/op
                 existUser·p0.95:   3.977 ms/op
                 existUser·p0.99:   5.014 ms/op
                 existUser·p0.999:  21.201 ms/op
                 existUser·p0.9999: 28.803 ms/op
                 existUser·p1.00:   30.278 ms/op

Iteration   3: 3.449 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.831 ms/op
                 existUser·p0.50:   3.322 ms/op
                 existUser·p0.90:   4.067 ms/op
                 existUser·p0.95:   4.661 ms/op
                 existUser·p0.99:   6.021 ms/op
                 existUser·p0.999:  23.085 ms/op
                 existUser·p0.9999: 26.585 ms/op
                 existUser·p1.00:   27.361 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 283143
  mean =      3.390 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14205 
    [ 2.500,  5.000) = 262930 
    [ 5.000,  7.500) = 5156 
    [ 7.500, 10.000) = 487 
    [10.000, 12.500) = 51 
    [12.500, 15.000) = 17 
    [15.000, 17.500) = 9 
    [17.500, 20.000) = 7 
    [20.000, 22.500) = 97 
    [22.500, 25.000) = 115 
    [25.000, 27.500) = 46 
    [27.500, 30.000) = 21 
    [30.000, 32.500) = 2 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.694 ms/op
     p(50.0000) =      3.301 ms/op
     p(90.0000) =      3.863 ms/op
     p(95.0000) =      4.276 ms/op
     p(99.0000) =      5.755 ms/op
     p(99.9000) =     19.787 ms/op
     p(99.9900) =     27.296 ms/op
     p(99.9990) =     29.999 ms/op
     p(99.9999) =     30.278 ms/op
    p(100.0000) =     30.278 ms/op


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
# Warmup Iteration   1: 8.761 ±(99.9%) 0.118 ms/op
# Warmup Iteration   2: 3.584 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.473 ±(99.9%) 0.010 ms/op
Iteration   1: 3.459 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.610 ms/op
                 getUser·p0.50:   3.240 ms/op
                 getUser·p0.90:   3.871 ms/op
                 getUser·p0.95:   4.550 ms/op
                 getUser·p0.99:   6.898 ms/op
                 getUser·p0.999:  20.203 ms/op
                 getUser·p0.9999: 23.782 ms/op
                 getUser·p1.00:   24.150 ms/op

Iteration   2: 3.390 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.266 ms/op
                 getUser·p0.50:   3.256 ms/op
                 getUser·p0.90:   3.690 ms/op
                 getUser·p0.95:   3.936 ms/op
                 getUser·p0.99:   6.013 ms/op
                 getUser·p0.999:  21.287 ms/op
                 getUser·p0.9999: 24.996 ms/op
                 getUser·p1.00:   25.821 ms/op

Iteration   3: 3.408 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.112 ms/op
                 getUser·p0.50:   3.318 ms/op
                 getUser·p0.90:   3.858 ms/op
                 getUser·p0.95:   4.252 ms/op
                 getUser·p0.99:   5.979 ms/op
                 getUser·p0.999:  20.546 ms/op
                 getUser·p0.9999: 24.899 ms/op
                 getUser·p1.00:   25.526 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 280599
  mean =      3.419 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7393 
    [ 2.500,  5.000) = 263957 
    [ 5.000,  7.500) = 7997 
    [ 7.500, 10.000) = 859 
    [10.000, 12.500) = 98 
    [12.500, 15.000) = 7 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 128 
    [22.500, 25.000) = 143 
    [25.000, 27.500) = 17 

  Percentiles, ms/op:
      p(0.0000) =      1.112 ms/op
     p(50.0000) =      3.281 ms/op
     p(90.0000) =      3.809 ms/op
     p(95.0000) =      4.211 ms/op
     p(99.0000) =      6.341 ms/op
     p(99.9000) =     20.447 ms/op
     p(99.9900) =     24.738 ms/op
     p(99.9990) =     25.605 ms/op
     p(99.9999) =     25.821 ms/op
    p(100.0000) =     25.821 ms/op


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
# Warmup Iteration   1: 11.565 ±(99.9%) 0.153 ms/op
# Warmup Iteration   2: 4.564 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.107 ±(99.9%) 0.014 ms/op
Iteration   1: 4.064 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.104 ms/op
                 listUser·p0.50:   3.850 ms/op
                 listUser·p0.90:   4.514 ms/op
                 listUser·p0.95:   4.899 ms/op
                 listUser·p0.99:   7.741 ms/op
                 listUser·p0.999:  20.578 ms/op
                 listUser·p0.9999: 25.211 ms/op
                 listUser·p1.00:   26.378 ms/op

Iteration   2: 4.069 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.314 ms/op
                 listUser·p0.50:   3.908 ms/op
                 listUser·p0.90:   4.456 ms/op
                 listUser·p0.95:   5.169 ms/op
                 listUser·p0.99:   7.922 ms/op
                 listUser·p0.999:  15.900 ms/op
                 listUser·p0.9999: 18.243 ms/op
                 listUser·p1.00:   19.333 ms/op

Iteration   3: 4.041 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.417 ms/op
                 listUser·p0.50:   3.908 ms/op
                 listUser·p0.90:   4.686 ms/op
                 listUser·p0.95:   4.940 ms/op
                 listUser·p0.99:   6.889 ms/op
                 listUser·p0.999:  16.084 ms/op
                 listUser·p0.9999: 23.069 ms/op
                 listUser·p1.00:   23.134 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 236418
  mean =      4.058 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 21 
    [ 2.500,  5.000) = 225214 
    [ 5.000,  7.500) = 8740 
    [ 7.500, 10.000) = 1580 
    [10.000, 12.500) = 294 
    [12.500, 15.000) = 179 
    [15.000, 17.500) = 169 
    [17.500, 20.000) = 79 
    [20.000, 22.500) = 81 
    [22.500, 25.000) = 53 
    [25.000, 27.500) = 8 

  Percentiles, ms/op:
      p(0.0000) =      1.104 ms/op
     p(50.0000) =      3.891 ms/op
     p(90.0000) =      4.555 ms/op
     p(95.0000) =      4.956 ms/op
     p(99.0000) =      7.561 ms/op
     p(99.9000) =     17.157 ms/op
     p(99.9900) =     24.424 ms/op
     p(99.9990) =     26.056 ms/op
     p(99.9999) =     26.378 ms/op
    p(100.0000) =     26.378 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.201 ± 1.876  ops/ms
ClientPb.existUser                       thrpt       3   9.670 ± 2.121  ops/ms
ClientPb.getUser                         thrpt       3   9.377 ± 6.530  ops/ms
ClientPb.listUser                        thrpt       3   8.128 ± 1.560  ops/ms
ClientPb.createUser                       avgt       3   3.435 ± 0.967   ms/op
ClientPb.existUser                        avgt       3   3.253 ± 1.251   ms/op
ClientPb.getUser                          avgt       3   3.387 ± 0.235   ms/op
ClientPb.listUser                         avgt       3   3.940 ± 0.738   ms/op
ClientPb.createUser                     sample  280290   3.426 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.069           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.367           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.781           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.243           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.227           ms/op
ClientPb.createUser:createUser·p0.999   sample          17.226           ms/op
ClientPb.createUser:createUser·p0.9999  sample          26.212           ms/op
ClientPb.createUser:createUser·p1.00    sample          27.591           ms/op
ClientPb.existUser                      sample  283143   3.390 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.694           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.301           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.863           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.276           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.755           ms/op
ClientPb.existUser:existUser·p0.999     sample          19.787           ms/op
ClientPb.existUser:existUser·p0.9999    sample          27.296           ms/op
ClientPb.existUser:existUser·p1.00      sample          30.278           ms/op
ClientPb.getUser                        sample  280599   3.419 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.112           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.281           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.809           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.211           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.341           ms/op
ClientPb.getUser:getUser·p0.999         sample          20.447           ms/op
ClientPb.getUser:getUser·p0.9999        sample          24.738           ms/op
ClientPb.getUser:getUser·p1.00          sample          25.821           ms/op
ClientPb.listUser                       sample  236418   4.058 ± 0.007   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.104           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.891           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.555           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.956           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.561           ms/op
ClientPb.listUser:listUser·p0.999       sample          17.157           ms/op
ClientPb.listUser:listUser·p0.9999      sample          24.424           ms/op
ClientPb.listUser:listUser·p1.00        sample          26.378           ms/op
