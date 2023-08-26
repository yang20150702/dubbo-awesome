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
# Warmup Iteration   1: 2.325 ops/ms
# Warmup Iteration   2: 6.333 ops/ms
# Warmup Iteration   3: 8.826 ops/ms
Iteration   1: 9.433 ops/ms
Iteration   2: 9.479 ops/ms
Iteration   3: 9.550 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.487 ±(99.9%) 1.072 ops/ms [Average]
  (min, avg, max) = (9.433, 9.487, 9.550), stdev = 0.059
  CI (99.9%): [8.415, 10.559] (assumes normal distribution)


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
# Warmup Iteration   1: 3.281 ops/ms
# Warmup Iteration   2: 9.052 ops/ms
# Warmup Iteration   3: 9.977 ops/ms
Iteration   1: 9.983 ops/ms
Iteration   2: 9.921 ops/ms
Iteration   3: 9.982 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.962 ±(99.9%) 0.649 ops/ms [Average]
  (min, avg, max) = (9.921, 9.962, 9.983), stdev = 0.036
  CI (99.9%): [9.313, 10.611] (assumes normal distribution)


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
# Warmup Iteration   1: 3.539 ops/ms
# Warmup Iteration   2: 9.070 ops/ms
# Warmup Iteration   3: 9.834 ops/ms
Iteration   1: 9.981 ops/ms
Iteration   2: 9.994 ops/ms
Iteration   3: 9.857 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.944 ±(99.9%) 1.385 ops/ms [Average]
  (min, avg, max) = (9.857, 9.944, 9.994), stdev = 0.076
  CI (99.9%): [8.558, 11.329] (assumes normal distribution)


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
# Warmup Iteration   1: 3.205 ops/ms
# Warmup Iteration   2: 7.532 ops/ms
# Warmup Iteration   3: 7.956 ops/ms
Iteration   1: 8.400 ops/ms
Iteration   2: 8.315 ops/ms
Iteration   3: 8.474 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.396 ±(99.9%) 1.446 ops/ms [Average]
  (min, avg, max) = (8.315, 8.396, 8.474), stdev = 0.079
  CI (99.9%): [6.951, 9.842] (assumes normal distribution)


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
# Warmup Iteration   1: 9.050 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 3.551 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.510 ±(99.9%) 0.004 ms/op
Iteration   1: 3.269 ±(99.9%) 0.004 ms/op
Iteration   2: 3.257 ±(99.9%) 0.004 ms/op
Iteration   3: 3.243 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.256 ±(99.9%) 0.240 ms/op [Average]
  (min, avg, max) = (3.243, 3.256, 3.269), stdev = 0.013
  CI (99.9%): [3.016, 3.497] (assumes normal distribution)


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
# Warmup Iteration   1: 7.872 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.486 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.224 ±(99.9%) 0.006 ms/op
Iteration   1: 3.249 ±(99.9%) 0.004 ms/op
Iteration   2: 3.126 ±(99.9%) 0.007 ms/op
Iteration   3: 3.113 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.163 ±(99.9%) 1.364 ms/op [Average]
  (min, avg, max) = (3.113, 3.163, 3.249), stdev = 0.075
  CI (99.9%): [1.799, 4.527] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 7.244 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 3.493 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.266 ±(99.9%) 0.003 ms/op
Iteration   1: 3.445 ±(99.9%) 0.003 ms/op
Iteration   2: 3.285 ±(99.9%) 0.005 ms/op
Iteration   3: 3.325 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.351 ±(99.9%) 1.517 ms/op [Average]
  (min, avg, max) = (3.285, 3.351, 3.445), stdev = 0.083
  CI (99.9%): [1.834, 4.869] (assumes normal distribution)


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
# Warmup Iteration   1: 9.003 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 4.162 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.872 ±(99.9%) 0.004 ms/op
Iteration   1: 3.814 ±(99.9%) 0.008 ms/op
Iteration   2: 3.810 ±(99.9%) 0.005 ms/op
Iteration   3: 3.797 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.807 ±(99.9%) 0.161 ms/op [Average]
  (min, avg, max) = (3.797, 3.807, 3.814), stdev = 0.009
  CI (99.9%): [3.646, 3.968] (assumes normal distribution)


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
# Warmup Iteration   1: 8.780 ±(99.9%) 0.121 ms/op
# Warmup Iteration   2: 3.721 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.382 ±(99.9%) 0.010 ms/op
Iteration   1: 3.359 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.673 ms/op
                 createUser·p0.50:   3.244 ms/op
                 createUser·p0.90:   3.858 ms/op
                 createUser·p0.95:   4.563 ms/op
                 createUser·p0.99:   6.365 ms/op
                 createUser·p0.999:  17.881 ms/op
                 createUser·p0.9999: 21.594 ms/op
                 createUser·p1.00:   22.708 ms/op

Iteration   2: 3.239 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.323 ms/op
                 createUser·p0.50:   3.219 ms/op
                 createUser·p0.90:   3.523 ms/op
                 createUser·p0.95:   3.813 ms/op
                 createUser·p0.99:   5.784 ms/op
                 createUser·p0.999:  13.745 ms/op
                 createUser·p0.9999: 23.270 ms/op
                 createUser·p1.00:   24.216 ms/op

Iteration   3: 3.237 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.497 ms/op
                 createUser·p0.50:   3.133 ms/op
                 createUser·p0.90:   3.617 ms/op
                 createUser·p0.95:   3.887 ms/op
                 createUser·p0.99:   6.144 ms/op
                 createUser·p0.999:  15.910 ms/op
                 createUser·p0.9999: 26.808 ms/op
                 createUser·p1.00:   27.689 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 292732
  mean =      3.278 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 20307 
    [ 2.500,  5.000) = 264946 
    [ 5.000,  7.500) = 6028 
    [ 7.500, 10.000) = 1020 
    [10.000, 12.500) = 85 
    [12.500, 15.000) = 55 
    [15.000, 17.500) = 9 
    [17.500, 20.000) = 143 
    [20.000, 22.500) = 85 
    [22.500, 25.000) = 22 
    [25.000, 27.500) = 31 

  Percentiles, ms/op:
      p(0.0000) =      0.673 ms/op
     p(50.0000) =      3.207 ms/op
     p(90.0000) =      3.662 ms/op
     p(95.0000) =      4.030 ms/op
     p(99.0000) =      6.128 ms/op
     p(99.9000) =     14.390 ms/op
     p(99.9900) =     25.893 ms/op
     p(99.9990) =     27.308 ms/op
     p(99.9999) =     27.689 ms/op
    p(100.0000) =     27.689 ms/op


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
# Warmup Iteration   1: 7.986 ±(99.9%) 0.102 ms/op
# Warmup Iteration   2: 3.327 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.225 ±(99.9%) 0.007 ms/op
Iteration   1: 3.103 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.079 ms/op
                 existUser·p0.50:   2.982 ms/op
                 existUser·p0.90:   3.400 ms/op
                 existUser·p0.95:   4.153 ms/op
                 existUser·p0.99:   5.997 ms/op
                 existUser·p0.999:  13.565 ms/op
                 existUser·p0.9999: 18.035 ms/op
                 existUser·p1.00:   19.923 ms/op

Iteration   2: 3.171 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.067 ms/op
                 existUser·p0.50:   2.974 ms/op
                 existUser·p0.90:   3.564 ms/op
                 existUser·p0.95:   4.694 ms/op
                 existUser·p0.99:   6.275 ms/op
                 existUser·p0.999:  10.011 ms/op
                 existUser·p0.9999: 19.822 ms/op
                 existUser·p1.00:   20.808 ms/op

Iteration   3: 3.255 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.767 ms/op
                 existUser·p0.50:   3.183 ms/op
                 existUser·p0.90:   3.662 ms/op
                 existUser·p0.95:   4.121 ms/op
                 existUser·p0.99:   5.775 ms/op
                 existUser·p0.999:  11.256 ms/op
                 existUser·p0.9999: 22.186 ms/op
                 existUser·p1.00:   25.002 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 302065
  mean =      3.175 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 20967 
    [ 2.500,  5.000) = 270389 
    [ 5.000,  7.500) = 9527 
    [ 7.500, 10.000) = 781 
    [10.000, 12.500) = 88 
    [12.500, 15.000) = 30 
    [15.000, 17.500) = 145 
    [17.500, 20.000) = 80 
    [20.000, 22.500) = 50 
    [22.500, 25.000) = 7 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.067 ms/op
     p(50.0000) =      3.068 ms/op
     p(90.0000) =      3.568 ms/op
     p(95.0000) =      4.284 ms/op
     p(99.0000) =      6.128 ms/op
     p(99.9000) =     13.114 ms/op
     p(99.9900) =     21.312 ms/op
     p(99.9990) =     23.626 ms/op
     p(99.9999) =     25.002 ms/op
    p(100.0000) =     25.002 ms/op


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
# Warmup Iteration   1: 8.027 ±(99.9%) 0.109 ms/op
# Warmup Iteration   2: 3.723 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.443 ±(99.9%) 0.011 ms/op
Iteration   1: 3.405 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.313 ms/op
                 getUser·p0.50:   3.248 ms/op
                 getUser·p0.90:   3.973 ms/op
                 getUser·p0.95:   4.866 ms/op
                 getUser·p0.99:   6.226 ms/op
                 getUser·p0.999:  18.356 ms/op
                 getUser·p0.9999: 27.611 ms/op
                 getUser·p1.00:   28.541 ms/op

Iteration   2: 3.204 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.128 ms/op
                 getUser·p0.50:   3.133 ms/op
                 getUser·p0.90:   3.523 ms/op
                 getUser·p0.95:   3.703 ms/op
                 getUser·p0.99:   5.292 ms/op
                 getUser·p0.999:  10.133 ms/op
                 getUser·p0.9999: 27.625 ms/op
                 getUser·p1.00:   29.229 ms/op

Iteration   3: 3.380 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.039 ms/op
                 getUser·p0.50:   3.248 ms/op
                 getUser·p0.90:   3.912 ms/op
                 getUser·p0.95:   4.645 ms/op
                 getUser·p0.99:   6.366 ms/op
                 getUser·p0.999:  16.496 ms/op
                 getUser·p0.9999: 27.117 ms/op
                 getUser·p1.00:   27.820 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 288293
  mean =      3.327 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13295 
    [ 2.500,  5.000) = 265546 
    [ 5.000,  7.500) = 8107 
    [ 7.500, 10.000) = 954 
    [10.000, 12.500) = 73 
    [12.500, 15.000) = 30 
    [15.000, 17.500) = 27 
    [17.500, 20.000) = 46 
    [20.000, 22.500) = 70 
    [22.500, 25.000) = 34 
    [25.000, 27.500) = 83 

  Percentiles, ms/op:
      p(0.0000) =      1.039 ms/op
     p(50.0000) =      3.215 ms/op
     p(90.0000) =      3.781 ms/op
     p(95.0000) =      4.284 ms/op
     p(99.0000) =      6.070 ms/op
     p(99.9000) =     15.484 ms/op
     p(99.9900) =     27.476 ms/op
     p(99.9990) =     28.281 ms/op
     p(99.9999) =     29.229 ms/op
    p(100.0000) =     29.229 ms/op


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
# Warmup Iteration   1: 9.779 ±(99.9%) 0.131 ms/op
# Warmup Iteration   2: 4.211 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.014 ±(99.9%) 0.013 ms/op
Iteration   1: 3.990 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.608 ms/op
                 listUser·p0.50:   3.822 ms/op
                 listUser·p0.90:   4.440 ms/op
                 listUser·p0.95:   5.292 ms/op
                 listUser·p0.99:   7.807 ms/op
                 listUser·p0.999:  19.432 ms/op
                 listUser·p0.9999: 25.852 ms/op
                 listUser·p1.00:   27.722 ms/op

Iteration   2: 3.818 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.347 ms/op
                 listUser·p0.50:   3.727 ms/op
                 listUser·p0.90:   4.067 ms/op
                 listUser·p0.95:   4.407 ms/op
                 listUser·p0.99:   7.586 ms/op
                 listUser·p0.999:  14.909 ms/op
                 listUser·p0.9999: 18.043 ms/op
                 listUser·p1.00:   18.121 ms/op

Iteration   3: 3.828 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.220 ms/op
                 listUser·p0.50:   3.670 ms/op
                 listUser·p0.90:   4.174 ms/op
                 listUser·p0.95:   4.399 ms/op
                 listUser·p0.99:   7.917 ms/op
                 listUser·p0.999:  14.707 ms/op
                 listUser·p0.9999: 17.433 ms/op
                 listUser·p1.00:   17.433 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 247445
  mean =      3.877 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 56 
    [ 2.500,  5.000) = 237702 
    [ 5.000,  7.500) = 6829 
    [ 7.500, 10.000) = 2016 
    [10.000, 12.500) = 365 
    [12.500, 15.000) = 235 
    [15.000, 17.500) = 129 
    [17.500, 20.000) = 49 
    [20.000, 22.500) = 18 
    [22.500, 25.000) = 27 
    [25.000, 27.500) = 17 

  Percentiles, ms/op:
      p(0.0000) =      1.608 ms/op
     p(50.0000) =      3.748 ms/op
     p(90.0000) =      4.227 ms/op
     p(95.0000) =      4.628 ms/op
     p(99.0000) =      7.758 ms/op
     p(99.9000) =     14.942 ms/op
     p(99.9900) =     24.675 ms/op
     p(99.9990) =     27.563 ms/op
     p(99.9999) =     27.722 ms/op
    p(100.0000) =     27.722 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.487 ± 1.072  ops/ms
ClientPb.existUser                       thrpt       3   9.962 ± 0.649  ops/ms
ClientPb.getUser                         thrpt       3   9.944 ± 1.385  ops/ms
ClientPb.listUser                        thrpt       3   8.396 ± 1.446  ops/ms
ClientPb.createUser                       avgt       3   3.256 ± 0.240   ms/op
ClientPb.existUser                        avgt       3   3.163 ± 1.364   ms/op
ClientPb.getUser                          avgt       3   3.351 ± 1.517   ms/op
ClientPb.listUser                         avgt       3   3.807 ± 0.161   ms/op
ClientPb.createUser                     sample  292732   3.278 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.673           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.207           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.662           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.030           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.128           ms/op
ClientPb.createUser:createUser·p0.999   sample          14.390           ms/op
ClientPb.createUser:createUser·p0.9999  sample          25.893           ms/op
ClientPb.createUser:createUser·p1.00    sample          27.689           ms/op
ClientPb.existUser                      sample  302065   3.175 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.067           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.068           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.568           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.284           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.128           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.114           ms/op
ClientPb.existUser:existUser·p0.9999    sample          21.312           ms/op
ClientPb.existUser:existUser·p1.00      sample          25.002           ms/op
ClientPb.getUser                        sample  288293   3.327 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.039           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.215           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.781           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.284           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.070           ms/op
ClientPb.getUser:getUser·p0.999         sample          15.484           ms/op
ClientPb.getUser:getUser·p0.9999        sample          27.476           ms/op
ClientPb.getUser:getUser·p1.00          sample          29.229           ms/op
ClientPb.listUser                       sample  247445   3.877 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.608           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.748           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.227           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.628           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.758           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.942           ms/op
ClientPb.listUser:listUser·p0.9999      sample          24.675           ms/op
ClientPb.listUser:listUser·p1.00        sample          27.722           ms/op
