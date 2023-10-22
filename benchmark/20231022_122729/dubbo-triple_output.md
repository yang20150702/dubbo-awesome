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
# Warmup Iteration   1: 1.393 ops/ms
# Warmup Iteration   2: 3.409 ops/ms
# Warmup Iteration   3: 7.026 ops/ms
Iteration   1: 7.418 ops/ms
Iteration   2: 8.044 ops/ms
Iteration   3: 7.686 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.716 ±(99.9%) 5.736 ops/ms [Average]
  (min, avg, max) = (7.418, 7.716, 8.044), stdev = 0.314
  CI (99.9%): [1.980, 13.452] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:13
# Fork: 1 of 1
# Warmup Iteration   1: 1.983 ops/ms
# Warmup Iteration   2: 5.649 ops/ms
# Warmup Iteration   3: 7.958 ops/ms
Iteration   1: 7.870 ops/ms
Iteration   2: 7.702 ops/ms
Iteration   3: 8.070 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  7.881 ±(99.9%) 3.361 ops/ms [Average]
  (min, avg, max) = (7.702, 7.881, 8.070), stdev = 0.184
  CI (99.9%): [4.520, 11.242] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:06
# Fork: 1 of 1
# Warmup Iteration   1: 2.253 ops/ms
# Warmup Iteration   2: 6.326 ops/ms
# Warmup Iteration   3: 7.674 ops/ms
Iteration   1: 7.322 ops/ms
Iteration   2: 7.575 ops/ms
Iteration   3: 7.793 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  7.564 ±(99.9%) 4.305 ops/ms [Average]
  (min, avg, max) = (7.322, 7.564, 7.793), stdev = 0.236
  CI (99.9%): [3.259, 11.869] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:57
# Fork: 1 of 1
# Warmup Iteration   1: 2.054 ops/ms
# Warmup Iteration   2: 5.291 ops/ms
# Warmup Iteration   3: 6.511 ops/ms
Iteration   1: 6.639 ops/ms
Iteration   2: 6.530 ops/ms
Iteration   3: 6.838 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.669 ±(99.9%) 2.851 ops/ms [Average]
  (min, avg, max) = (6.530, 6.669, 6.838), stdev = 0.156
  CI (99.9%): [3.818, 9.519] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:51
# Fork: 1 of 1
# Warmup Iteration   1: 15.055 ±(99.9%) 0.086 ms/op
# Warmup Iteration   2: 5.032 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.400 ±(99.9%) 0.007 ms/op
Iteration   1: 4.106 ±(99.9%) 0.003 ms/op
Iteration   2: 4.157 ±(99.9%) 0.006 ms/op
Iteration   3: 3.999 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  4.087 ±(99.9%) 1.465 ms/op [Average]
  (min, avg, max) = (3.999, 4.087, 4.157), stdev = 0.080
  CI (99.9%): [2.622, 5.553] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:45
# Fork: 1 of 1
# Warmup Iteration   1: 12.845 ±(99.9%) 0.062 ms/op
# Warmup Iteration   2: 4.262 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.064 ±(99.9%) 0.004 ms/op
Iteration   1: 4.196 ±(99.9%) 0.003 ms/op
Iteration   2: 4.024 ±(99.9%) 0.004 ms/op
Iteration   3: 3.976 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  4.065 ±(99.9%) 2.113 ms/op [Average]
  (min, avg, max) = (3.976, 4.065, 4.196), stdev = 0.116
  CI (99.9%): [1.952, 6.178] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:37
# Fork: 1 of 1
# Warmup Iteration   1: 14.251 ±(99.9%) 0.064 ms/op
# Warmup Iteration   2: 4.464 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.150 ±(99.9%) 0.005 ms/op
Iteration   1: 4.082 ±(99.9%) 0.005 ms/op
Iteration   2: 4.084 ±(99.9%) 0.006 ms/op
Iteration   3: 4.024 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  4.064 ±(99.9%) 0.619 ms/op [Average]
  (min, avg, max) = (4.024, 4.064, 4.084), stdev = 0.034
  CI (99.9%): [3.444, 4.683] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:31
# Fork: 1 of 1
# Warmup Iteration   1: 16.101 ±(99.9%) 0.068 ms/op
# Warmup Iteration   2: 5.789 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.894 ±(99.9%) 0.006 ms/op
Iteration   1: 4.891 ±(99.9%) 0.006 ms/op
Iteration   2: 4.680 ±(99.9%) 0.010 ms/op
Iteration   3: 4.699 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.757 ±(99.9%) 2.123 ms/op [Average]
  (min, avg, max) = (4.680, 4.757, 4.891), stdev = 0.116
  CI (99.9%): [2.633, 6.880] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:25
# Fork: 1 of 1
# Warmup Iteration   1: 13.635 ±(99.9%) 0.191 ms/op
# Warmup Iteration   2: 5.544 ±(99.9%) 0.034 ms/op
# Warmup Iteration   3: 4.455 ±(99.9%) 0.019 ms/op
Iteration   1: 4.192 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.827 ms/op
                 createUser·p0.50:   3.985 ms/op
                 createUser·p0.90:   4.899 ms/op
                 createUser·p0.95:   5.718 ms/op
                 createUser·p0.99:   8.069 ms/op
                 createUser·p0.999:  24.379 ms/op
                 createUser·p0.9999: 27.230 ms/op
                 createUser·p1.00:   28.475 ms/op

Iteration   2: 4.052 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.200 ms/op
                 createUser·p0.50:   3.908 ms/op
                 createUser·p0.90:   4.424 ms/op
                 createUser·p0.95:   4.891 ms/op
                 createUser·p0.99:   8.602 ms/op
                 createUser·p0.999:  19.696 ms/op
                 createUser·p0.9999: 27.929 ms/op
                 createUser·p1.00:   28.934 ms/op

Iteration   3: 4.100 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.886 ms/op
                 createUser·p0.50:   3.940 ms/op
                 createUser·p0.90:   4.628 ms/op
                 createUser·p0.95:   5.104 ms/op
                 createUser·p0.99:   7.160 ms/op
                 createUser·p0.999:  28.180 ms/op
                 createUser·p0.9999: 30.775 ms/op
                 createUser·p1.00:   31.556 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 233420
  mean =      4.114 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 262 
    [ 2.500,  5.000) = 218471 
    [ 5.000,  7.500) = 11502 
    [ 7.500, 10.000) = 2243 
    [10.000, 12.500) = 521 
    [12.500, 15.000) = 85 
    [15.000, 17.500) = 28 
    [17.500, 20.000) = 42 
    [20.000, 22.500) = 7 
    [22.500, 25.000) = 39 
    [25.000, 27.500) = 111 
    [27.500, 30.000) = 76 
    [30.000, 32.500) = 33 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.200 ms/op
     p(50.0000) =      3.944 ms/op
     p(90.0000) =      4.661 ms/op
     p(95.0000) =      5.267 ms/op
     p(99.0000) =      8.012 ms/op
     p(99.9000) =     24.445 ms/op
     p(99.9900) =     30.365 ms/op
     p(99.9990) =     31.512 ms/op
     p(99.9999) =     31.556 ms/op
    p(100.0000) =     31.556 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:19
# Fork: 1 of 1
# Warmup Iteration   1: 12.813 ±(99.9%) 0.197 ms/op
# Warmup Iteration   2: 4.725 ±(99.9%) 0.025 ms/op
# Warmup Iteration   3: 4.061 ±(99.9%) 0.014 ms/op
Iteration   1: 3.987 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   2.097 ms/op
                 existUser·p0.50:   3.809 ms/op
                 existUser·p0.90:   4.497 ms/op
                 existUser·p0.95:   5.276 ms/op
                 existUser·p0.99:   8.028 ms/op
                 existUser·p0.999:  15.303 ms/op
                 existUser·p0.9999: 27.916 ms/op
                 existUser·p1.00:   29.131 ms/op

Iteration   2: 3.875 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.657 ms/op
                 existUser·p0.50:   3.777 ms/op
                 existUser·p0.90:   4.276 ms/op
                 existUser·p0.95:   4.710 ms/op
                 existUser·p0.99:   7.478 ms/op
                 existUser·p0.999:  15.909 ms/op
                 existUser·p0.9999: 26.894 ms/op
                 existUser·p1.00:   28.803 ms/op

Iteration   3: 3.889 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   1.528 ms/op
                 existUser·p0.50:   3.690 ms/op
                 existUser·p0.90:   4.334 ms/op
                 existUser·p0.95:   4.809 ms/op
                 existUser·p0.99:   7.725 ms/op
                 existUser·p0.999:  27.516 ms/op
                 existUser·p0.9999: 33.817 ms/op
                 existUser·p1.00:   34.931 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 244991
  mean =      3.916 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 311 
    [ 2.500,  5.000) = 233275 
    [ 5.000,  7.500) = 8425 
    [ 7.500, 10.000) = 2357 
    [10.000, 12.500) = 210 
    [12.500, 15.000) = 132 
    [15.000, 17.500) = 57 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 11 
    [25.000, 27.500) = 119 
    [27.500, 30.000) = 31 
    [30.000, 32.500) = 33 
    [32.500, 35.000) = 30 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.528 ms/op
     p(50.0000) =      3.764 ms/op
     p(90.0000) =      4.366 ms/op
     p(95.0000) =      4.923 ms/op
     p(99.0000) =      7.774 ms/op
     p(99.9000) =     15.958 ms/op
     p(99.9900) =     32.899 ms/op
     p(99.9990) =     34.390 ms/op
     p(99.9999) =     34.931 ms/op
    p(100.0000) =     34.931 ms/op


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
# Warmup Iteration   1: 13.794 ±(99.9%) 0.214 ms/op
# Warmup Iteration   2: 4.737 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 4.108 ±(99.9%) 0.012 ms/op
Iteration   1: 4.181 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.356 ms/op
                 getUser·p0.50:   4.006 ms/op
                 getUser·p0.90:   4.776 ms/op
                 getUser·p0.95:   5.497 ms/op
                 getUser·p0.99:   7.767 ms/op
                 getUser·p0.999:  21.611 ms/op
                 getUser·p0.9999: 24.030 ms/op
                 getUser·p1.00:   24.281 ms/op

Iteration   2: 4.060 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   2.114 ms/op
                 getUser·p0.50:   3.932 ms/op
                 getUser·p0.90:   4.440 ms/op
                 getUser·p0.95:   4.702 ms/op
                 getUser·p0.99:   7.591 ms/op
                 getUser·p0.999:  21.463 ms/op
                 getUser·p0.9999: 25.313 ms/op
                 getUser·p1.00:   26.575 ms/op

Iteration   3: 3.998 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.671 ms/op
                 getUser·p0.50:   3.854 ms/op
                 getUser·p0.90:   4.399 ms/op
                 getUser·p0.95:   4.686 ms/op
                 getUser·p0.99:   6.930 ms/op
                 getUser·p0.999:  25.168 ms/op
                 getUser·p0.9999: 27.853 ms/op
                 getUser·p1.00:   28.705 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 235170
  mean =      4.078 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 62 
    [ 2.500,  5.000) = 223987 
    [ 5.000,  7.500) = 8815 
    [ 7.500, 10.000) = 1448 
    [10.000, 12.500) = 400 
    [12.500, 15.000) = 122 
    [15.000, 17.500) = 44 
    [17.500, 20.000) = 6 
    [20.000, 22.500) = 79 
    [22.500, 25.000) = 102 
    [25.000, 27.500) = 92 

  Percentiles, ms/op:
      p(0.0000) =      1.356 ms/op
     p(50.0000) =      3.936 ms/op
     p(90.0000) =      4.530 ms/op
     p(95.0000) =      4.940 ms/op
     p(99.0000) =      7.463 ms/op
     p(99.9000) =     21.916 ms/op
     p(99.9900) =     26.870 ms/op
     p(99.9990) =     28.387 ms/op
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

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 14.398 ±(99.9%) 0.231 ms/op
# Warmup Iteration   2: 5.813 ±(99.9%) 0.030 ms/op
# Warmup Iteration   3: 5.185 ±(99.9%) 0.021 ms/op
Iteration   1: 5.022 ±(99.9%) 0.019 ms/op
                 listUser·p0.00:   1.554 ms/op
                 listUser·p0.50:   4.833 ms/op
                 listUser·p0.90:   5.521 ms/op
                 listUser·p0.95:   6.201 ms/op
                 listUser·p0.99:   9.732 ms/op
                 listUser·p0.999:  28.856 ms/op
                 listUser·p0.9999: 32.064 ms/op
                 listUser·p1.00:   33.063 ms/op

Iteration   2: 4.960 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   2.372 ms/op
                 listUser·p0.50:   4.751 ms/op
                 listUser·p0.90:   5.587 ms/op
                 listUser·p0.95:   6.480 ms/op
                 listUser·p0.99:   8.760 ms/op
                 listUser·p0.999:  18.724 ms/op
                 listUser·p0.9999: 26.265 ms/op
                 listUser·p1.00:   27.492 ms/op

Iteration   3: 4.841 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   2.826 ms/op
                 listUser·p0.50:   4.637 ms/op
                 listUser·p0.90:   5.300 ms/op
                 listUser·p0.95:   5.759 ms/op
                 listUser·p0.99:   9.098 ms/op
                 listUser·p0.999:  18.022 ms/op
                 listUser·p0.9999: 21.627 ms/op
                 listUser·p1.00:   21.791 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 194165
  mean =      4.940 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5 
    [ 2.500,  5.000) = 135314 
    [ 5.000,  7.500) = 53581 
    [ 7.500, 10.000) = 3911 
    [10.000, 12.500) = 640 
    [12.500, 15.000) = 208 
    [15.000, 17.500) = 189 
    [17.500, 20.000) = 122 
    [20.000, 22.500) = 35 
    [22.500, 25.000) = 39 
    [25.000, 27.500) = 43 
    [27.500, 30.000) = 34 
    [30.000, 32.500) = 42 
    [32.500, 35.000) = 2 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.554 ms/op
     p(50.0000) =      4.727 ms/op
     p(90.0000) =      5.464 ms/op
     p(95.0000) =      6.185 ms/op
     p(99.0000) =      9.191 ms/op
     p(99.9000) =     20.021 ms/op
     p(99.9900) =     31.280 ms/op
     p(99.9990) =     32.631 ms/op
     p(99.9999) =     33.063 ms/op
    p(100.0000) =     33.063 ms/op


# Run complete. Total time: 00:13:17

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   7.716 ± 5.736  ops/ms
ClientPb.existUser                       thrpt       3   7.881 ± 3.361  ops/ms
ClientPb.getUser                         thrpt       3   7.564 ± 4.305  ops/ms
ClientPb.listUser                        thrpt       3   6.669 ± 2.851  ops/ms
ClientPb.createUser                       avgt       3   4.087 ± 1.465   ms/op
ClientPb.existUser                        avgt       3   4.065 ± 2.113   ms/op
ClientPb.getUser                          avgt       3   4.064 ± 0.619   ms/op
ClientPb.listUser                         avgt       3   4.757 ± 2.123   ms/op
ClientPb.createUser                     sample  233420   4.114 ± 0.008   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.200           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.944           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.661           ms/op
ClientPb.createUser:createUser·p0.95    sample           5.267           ms/op
ClientPb.createUser:createUser·p0.99    sample           8.012           ms/op
ClientPb.createUser:createUser·p0.999   sample          24.445           ms/op
ClientPb.createUser:createUser·p0.9999  sample          30.365           ms/op
ClientPb.createUser:createUser·p1.00    sample          31.556           ms/op
ClientPb.existUser                      sample  244991   3.916 ± 0.007   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.528           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.764           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.366           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.923           ms/op
ClientPb.existUser:existUser·p0.99      sample           7.774           ms/op
ClientPb.existUser:existUser·p0.999     sample          15.958           ms/op
ClientPb.existUser:existUser·p0.9999    sample          32.899           ms/op
ClientPb.existUser:existUser·p1.00      sample          34.931           ms/op
ClientPb.getUser                        sample  235170   4.078 ± 0.007   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.356           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.936           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.530           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.940           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.463           ms/op
ClientPb.getUser:getUser·p0.999         sample          21.916           ms/op
ClientPb.getUser:getUser·p0.9999        sample          26.870           ms/op
ClientPb.getUser:getUser·p1.00          sample          28.705           ms/op
ClientPb.listUser                       sample  194165   4.940 ± 0.009   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.554           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.727           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.464           ms/op
ClientPb.listUser:listUser·p0.95        sample           6.185           ms/op
ClientPb.listUser:listUser·p0.99        sample           9.191           ms/op
ClientPb.listUser:listUser·p0.999       sample          20.021           ms/op
ClientPb.listUser:listUser·p0.9999      sample          31.280           ms/op
ClientPb.listUser:listUser·p1.00        sample          33.063           ms/op
