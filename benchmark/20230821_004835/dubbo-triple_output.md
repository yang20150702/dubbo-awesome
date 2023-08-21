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
# Warmup Iteration   1: 2.605 ops/ms
# Warmup Iteration   2: 6.208 ops/ms
# Warmup Iteration   3: 9.154 ops/ms
Iteration   1: 9.830 ops/ms
Iteration   2: 9.583 ops/ms
Iteration   3: 10.119 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.844 ±(99.9%) 4.895 ops/ms [Average]
  (min, avg, max) = (9.583, 9.844, 10.119), stdev = 0.268
  CI (99.9%): [4.949, 14.739] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:06
# Fork: 1 of 1
# Warmup Iteration   1: 3.605 ops/ms
# Warmup Iteration   2: 9.192 ops/ms
# Warmup Iteration   3: 10.102 ops/ms
Iteration   1: 10.199 ops/ms
Iteration   2: 10.207 ops/ms
Iteration   3: 10.373 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.259 ±(99.9%) 1.799 ops/ms [Average]
  (min, avg, max) = (10.199, 10.259, 10.373), stdev = 0.099
  CI (99.9%): [8.461, 12.058] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:01
# Fork: 1 of 1
# Warmup Iteration   1: 3.313 ops/ms
# Warmup Iteration   2: 8.498 ops/ms
# Warmup Iteration   3: 9.787 ops/ms
Iteration   1: 9.740 ops/ms
Iteration   2: 10.075 ops/ms
Iteration   3: 10.004 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.940 ±(99.9%) 3.218 ops/ms [Average]
  (min, avg, max) = (9.740, 9.940, 10.075), stdev = 0.176
  CI (99.9%): [6.722, 13.157] (assumes normal distribution)


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
# Warmup Iteration   1: 3.377 ops/ms
# Warmup Iteration   2: 7.838 ops/ms
# Warmup Iteration   3: 8.203 ops/ms
Iteration   1: 8.299 ops/ms
Iteration   2: 8.315 ops/ms
Iteration   3: 8.165 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.260 ±(99.9%) 1.507 ops/ms [Average]
  (min, avg, max) = (8.165, 8.260, 8.315), stdev = 0.083
  CI (99.9%): [6.752, 9.767] (assumes normal distribution)


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
# Warmup Iteration   1: 9.063 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.687 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.328 ±(99.9%) 0.003 ms/op
Iteration   1: 3.198 ±(99.9%) 0.007 ms/op
Iteration   2: 3.211 ±(99.9%) 0.004 ms/op
Iteration   3: 3.176 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.195 ±(99.9%) 0.315 ms/op [Average]
  (min, avg, max) = (3.176, 3.195, 3.211), stdev = 0.017
  CI (99.9%): [2.880, 3.510] (assumes normal distribution)


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
# Warmup Iteration   1: 7.688 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 3.392 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.203 ±(99.9%) 0.003 ms/op
Iteration   1: 3.190 ±(99.9%) 0.006 ms/op
Iteration   2: 3.047 ±(99.9%) 0.002 ms/op
Iteration   3: 3.117 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.118 ±(99.9%) 1.309 ms/op [Average]
  (min, avg, max) = (3.047, 3.118, 3.190), stdev = 0.072
  CI (99.9%): [1.809, 4.427] (assumes normal distribution)


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
# Warmup Iteration   1: 7.642 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 3.409 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.406 ±(99.9%) 0.005 ms/op
Iteration   1: 3.334 ±(99.9%) 0.006 ms/op
Iteration   2: 3.194 ±(99.9%) 0.005 ms/op
Iteration   3: 3.138 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.222 ±(99.9%) 1.847 ms/op [Average]
  (min, avg, max) = (3.138, 3.222, 3.334), stdev = 0.101
  CI (99.9%): [1.375, 5.069] (assumes normal distribution)


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
# Warmup Iteration   1: 8.300 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 4.118 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.856 ±(99.9%) 0.007 ms/op
Iteration   1: 3.809 ±(99.9%) 0.006 ms/op
Iteration   2: 3.812 ±(99.9%) 0.007 ms/op
Iteration   3: 3.853 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.825 ±(99.9%) 0.445 ms/op [Average]
  (min, avg, max) = (3.809, 3.825, 3.853), stdev = 0.024
  CI (99.9%): [3.380, 4.269] (assumes normal distribution)


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
# Warmup Iteration   1: 8.006 ±(99.9%) 0.094 ms/op
# Warmup Iteration   2: 3.658 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.312 ±(99.9%) 0.011 ms/op
Iteration   1: 3.251 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.069 ms/op
                 createUser·p0.50:   3.064 ms/op
                 createUser·p0.90:   3.658 ms/op
                 createUser·p0.95:   4.022 ms/op
                 createUser·p0.99:   6.652 ms/op
                 createUser·p0.999:  18.874 ms/op
                 createUser·p0.9999: 21.070 ms/op
                 createUser·p1.00:   21.922 ms/op

Iteration   2: 3.234 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.686 ms/op
                 createUser·p0.50:   3.191 ms/op
                 createUser·p0.90:   3.547 ms/op
                 createUser·p0.95:   3.928 ms/op
                 createUser·p0.99:   6.045 ms/op
                 createUser·p0.999:  10.901 ms/op
                 createUser·p0.9999: 23.203 ms/op
                 createUser·p1.00:   23.888 ms/op

Iteration   3: 3.219 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.264 ms/op
                 createUser·p0.50:   3.195 ms/op
                 createUser·p0.90:   3.510 ms/op
                 createUser·p0.95:   3.777 ms/op
                 createUser·p0.99:   5.784 ms/op
                 createUser·p0.999:  15.935 ms/op
                 createUser·p0.9999: 23.396 ms/op
                 createUser·p1.00:   23.527 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 296710
  mean =      3.235 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 19191 
    [ 2.500,  5.000) = 269674 
    [ 5.000,  7.500) = 6204 
    [ 7.500, 10.000) = 1054 
    [10.000, 12.500) = 211 
    [12.500, 15.000) = 27 
    [15.000, 17.500) = 83 
    [17.500, 20.000) = 101 
    [20.000, 22.500) = 127 
    [22.500, 25.000) = 38 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.069 ms/op
     p(50.0000) =      3.170 ms/op
     p(90.0000) =      3.580 ms/op
     p(95.0000) =      3.903 ms/op
     p(99.0000) =      6.185 ms/op
     p(99.9000) =     16.531 ms/op
     p(99.9900) =     22.774 ms/op
     p(99.9990) =     23.725 ms/op
     p(99.9999) =     23.888 ms/op
    p(100.0000) =     23.888 ms/op


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
# Warmup Iteration   1: 7.547 ±(99.9%) 0.083 ms/op
# Warmup Iteration   2: 3.308 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.146 ±(99.9%) 0.008 ms/op
Iteration   1: 3.173 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.016 ms/op
                 existUser·p0.50:   3.117 ms/op
                 existUser·p0.90:   3.535 ms/op
                 existUser·p0.95:   3.899 ms/op
                 existUser·p0.99:   5.556 ms/op
                 existUser·p0.999:  11.030 ms/op
                 existUser·p0.9999: 20.412 ms/op
                 existUser·p1.00:   21.430 ms/op

Iteration   2: 3.173 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.081 ms/op
                 existUser·p0.50:   3.117 ms/op
                 existUser·p0.90:   3.473 ms/op
                 existUser·p0.95:   3.797 ms/op
                 existUser·p0.99:   6.218 ms/op
                 existUser·p0.999:  13.609 ms/op
                 existUser·p0.9999: 22.673 ms/op
                 existUser·p1.00:   23.462 ms/op

Iteration   3: 3.268 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.411 ms/op
                 existUser·p0.50:   3.203 ms/op
                 existUser·p0.90:   3.637 ms/op
                 existUser·p0.95:   3.986 ms/op
                 existUser·p0.99:   6.160 ms/op
                 existUser·p0.999:  13.730 ms/op
                 existUser·p0.9999: 20.520 ms/op
                 existUser·p1.00:   21.463 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 299334
  mean =      3.204 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 22421 
    [ 2.500,  5.000) = 270423 
    [ 5.000,  7.500) = 4964 
    [ 7.500, 10.000) = 952 
    [10.000, 12.500) = 204 
    [12.500, 15.000) = 109 
    [15.000, 17.500) = 38 
    [17.500, 20.000) = 99 
    [20.000, 22.500) = 110 
    [22.500, 25.000) = 14 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.016 ms/op
     p(50.0000) =      3.146 ms/op
     p(90.0000) =      3.559 ms/op
     p(95.0000) =      3.899 ms/op
     p(99.0000) =      5.988 ms/op
     p(99.9000) =     13.675 ms/op
     p(99.9900) =     21.760 ms/op
     p(99.9990) =     23.167 ms/op
     p(99.9999) =     23.462 ms/op
    p(100.0000) =     23.462 ms/op


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
# Warmup Iteration   1: 8.253 ±(99.9%) 0.099 ms/op
# Warmup Iteration   2: 3.499 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.235 ±(99.9%) 0.009 ms/op
Iteration   1: 3.280 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.020 ms/op
                 getUser·p0.50:   3.097 ms/op
                 getUser·p0.90:   3.527 ms/op
                 getUser·p0.95:   4.727 ms/op
                 getUser·p0.99:   6.914 ms/op
                 getUser·p0.999:  18.907 ms/op
                 getUser·p0.9999: 28.320 ms/op
                 getUser·p1.00:   28.901 ms/op

Iteration   2: 3.293 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.182 ms/op
                 getUser·p0.50:   3.150 ms/op
                 getUser·p0.90:   3.826 ms/op
                 getUser·p0.95:   4.276 ms/op
                 getUser·p0.99:   5.743 ms/op
                 getUser·p0.999:  12.837 ms/op
                 getUser·p0.9999: 24.540 ms/op
                 getUser·p1.00:   25.756 ms/op

Iteration   3: 3.235 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.031 ms/op
                 getUser·p0.50:   3.142 ms/op
                 getUser·p0.90:   3.617 ms/op
                 getUser·p0.95:   3.891 ms/op
                 getUser·p0.99:   5.816 ms/op
                 getUser·p0.999:  11.465 ms/op
                 getUser·p0.9999: 23.061 ms/op
                 getUser·p1.00:   23.658 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 293523
  mean =      3.269 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10449 
    [ 2.500,  5.000) = 274110 
    [ 5.000,  7.500) = 7395 
    [ 7.500, 10.000) = 1086 
    [10.000, 12.500) = 130 
    [12.500, 15.000) = 33 
    [15.000, 17.500) = 45 
    [17.500, 20.000) = 90 
    [20.000, 22.500) = 93 
    [22.500, 25.000) = 55 
    [25.000, 27.500) = 16 

  Percentiles, ms/op:
      p(0.0000) =      1.020 ms/op
     p(50.0000) =      3.125 ms/op
     p(90.0000) =      3.682 ms/op
     p(95.0000) =      4.153 ms/op
     p(99.0000) =      6.636 ms/op
     p(99.9000) =     16.793 ms/op
     p(99.9900) =     26.669 ms/op
     p(99.9990) =     28.646 ms/op
     p(99.9999) =     28.901 ms/op
    p(100.0000) =     28.901 ms/op


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
# Warmup Iteration   1: 8.980 ±(99.9%) 0.111 ms/op
# Warmup Iteration   2: 4.147 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.910 ±(99.9%) 0.012 ms/op
Iteration   1: 3.808 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.632 ms/op
                 listUser·p0.50:   3.658 ms/op
                 listUser·p0.90:   4.080 ms/op
                 listUser·p0.95:   4.309 ms/op
                 listUser·p0.99:   7.348 ms/op
                 listUser·p0.999:  18.480 ms/op
                 listUser·p0.9999: 24.536 ms/op
                 listUser·p1.00:   25.231 ms/op

Iteration   2: 3.800 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.154 ms/op
                 listUser·p0.50:   3.674 ms/op
                 listUser·p0.90:   4.047 ms/op
                 listUser·p0.95:   4.538 ms/op
                 listUser·p0.99:   7.774 ms/op
                 listUser·p0.999:  13.844 ms/op
                 listUser·p0.9999: 15.230 ms/op
                 listUser·p1.00:   16.138 ms/op

Iteration   3: 3.776 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.997 ms/op
                 listUser·p0.50:   3.670 ms/op
                 listUser·p0.90:   4.133 ms/op
                 listUser·p0.95:   4.325 ms/op
                 listUser·p0.99:   6.849 ms/op
                 listUser·p0.999:  14.151 ms/op
                 listUser·p0.9999: 18.400 ms/op
                 listUser·p1.00:   19.169 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 252858
  mean =      3.795 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 72 
    [ 2.500,  5.000) = 244520 
    [ 5.000,  7.500) = 5968 
    [ 7.500, 10.000) = 1583 
    [10.000, 12.500) = 248 
    [12.500, 15.000) = 264 
    [15.000, 17.500) = 70 
    [17.500, 20.000) = 87 
    [20.000, 22.500) = 16 
    [22.500, 25.000) = 28 
    [25.000, 27.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      1.632 ms/op
     p(50.0000) =      3.670 ms/op
     p(90.0000) =      4.096 ms/op
     p(95.0000) =      4.358 ms/op
     p(99.0000) =      7.397 ms/op
     p(99.9000) =     14.533 ms/op
     p(99.9900) =     22.942 ms/op
     p(99.9990) =     24.931 ms/op
     p(99.9999) =     25.231 ms/op
    p(100.0000) =     25.231 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.844 ± 4.895  ops/ms
ClientPb.existUser                       thrpt       3  10.259 ± 1.799  ops/ms
ClientPb.getUser                         thrpt       3   9.940 ± 3.218  ops/ms
ClientPb.listUser                        thrpt       3   8.260 ± 1.507  ops/ms
ClientPb.createUser                       avgt       3   3.195 ± 0.315   ms/op
ClientPb.existUser                        avgt       3   3.118 ± 1.309   ms/op
ClientPb.getUser                          avgt       3   3.222 ± 1.847   ms/op
ClientPb.listUser                         avgt       3   3.825 ± 0.445   ms/op
ClientPb.createUser                     sample  296710   3.235 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.069           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.170           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.580           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.903           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.185           ms/op
ClientPb.createUser:createUser·p0.999   sample          16.531           ms/op
ClientPb.createUser:createUser·p0.9999  sample          22.774           ms/op
ClientPb.createUser:createUser·p1.00    sample          23.888           ms/op
ClientPb.existUser                      sample  299334   3.204 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.016           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.146           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.559           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.899           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.988           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.675           ms/op
ClientPb.existUser:existUser·p0.9999    sample          21.760           ms/op
ClientPb.existUser:existUser·p1.00      sample          23.462           ms/op
ClientPb.getUser                        sample  293523   3.269 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.020           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.125           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.682           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.153           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.636           ms/op
ClientPb.getUser:getUser·p0.999         sample          16.793           ms/op
ClientPb.getUser:getUser·p0.9999        sample          26.669           ms/op
ClientPb.getUser:getUser·p1.00          sample          28.901           ms/op
ClientPb.listUser                       sample  252858   3.795 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.632           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.670           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.096           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.358           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.397           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.533           ms/op
ClientPb.listUser:listUser·p0.9999      sample          22.942           ms/op
ClientPb.listUser:listUser·p1.00        sample          25.231           ms/op
