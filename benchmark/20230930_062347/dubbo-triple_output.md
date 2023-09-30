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
# Warmup Iteration   1: 2.632 ops/ms
# Warmup Iteration   2: 5.533 ops/ms
# Warmup Iteration   3: 9.214 ops/ms
Iteration   1: 9.890 ops/ms
Iteration   2: 9.973 ops/ms
Iteration   3: 10.030 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.964 ±(99.9%) 1.284 ops/ms [Average]
  (min, avg, max) = (9.890, 9.964, 10.030), stdev = 0.070
  CI (99.9%): [8.680, 11.248] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:09
# Fork: 1 of 1
# Warmup Iteration   1: 3.412 ops/ms
# Warmup Iteration   2: 9.202 ops/ms
# Warmup Iteration   3: 9.961 ops/ms
Iteration   1: 10.328 ops/ms
Iteration   2: 10.436 ops/ms
Iteration   3: 10.383 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.382 ±(99.9%) 0.985 ops/ms [Average]
  (min, avg, max) = (10.328, 10.382, 10.436), stdev = 0.054
  CI (99.9%): [9.398, 11.367] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:02
# Fork: 1 of 1
# Warmup Iteration   1: 3.590 ops/ms
# Warmup Iteration   2: 8.942 ops/ms
# Warmup Iteration   3: 9.617 ops/ms
Iteration   1: 9.991 ops/ms
Iteration   2: 9.634 ops/ms
Iteration   3: 9.715 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.780 ±(99.9%) 3.410 ops/ms [Average]
  (min, avg, max) = (9.634, 9.780, 9.991), stdev = 0.187
  CI (99.9%): [6.370, 13.190] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:53
# Fork: 1 of 1
# Warmup Iteration   1: 3.015 ops/ms
# Warmup Iteration   2: 7.480 ops/ms
# Warmup Iteration   3: 8.194 ops/ms
Iteration   1: 8.348 ops/ms
Iteration   2: 8.482 ops/ms
Iteration   3: 8.475 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.435 ±(99.9%) 1.379 ops/ms [Average]
  (min, avg, max) = (8.348, 8.435, 8.482), stdev = 0.076
  CI (99.9%): [7.055, 9.814] (assumes normal distribution)


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
# Warmup Iteration   1: 7.845 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 3.519 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.391 ±(99.9%) 0.004 ms/op
Iteration   1: 3.194 ±(99.9%) 0.003 ms/op
Iteration   2: 3.213 ±(99.9%) 0.005 ms/op
Iteration   3: 3.232 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.213 ±(99.9%) 0.346 ms/op [Average]
  (min, avg, max) = (3.194, 3.213, 3.232), stdev = 0.019
  CI (99.9%): [2.867, 3.559] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:42
# Fork: 1 of 1
# Warmup Iteration   1: 7.816 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.281 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.198 ±(99.9%) 0.004 ms/op
Iteration   1: 3.197 ±(99.9%) 0.004 ms/op
Iteration   2: 3.098 ±(99.9%) 0.003 ms/op
Iteration   3: 3.076 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.124 ±(99.9%) 1.180 ms/op [Average]
  (min, avg, max) = (3.076, 3.124, 3.197), stdev = 0.065
  CI (99.9%): [1.943, 4.304] (assumes normal distribution)


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
# Warmup Iteration   1: 8.235 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 3.444 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.401 ±(99.9%) 0.004 ms/op
Iteration   1: 3.193 ±(99.9%) 0.004 ms/op
Iteration   2: 3.216 ±(99.9%) 0.002 ms/op
Iteration   3: 3.213 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.207 ±(99.9%) 0.228 ms/op [Average]
  (min, avg, max) = (3.193, 3.207, 3.216), stdev = 0.012
  CI (99.9%): [2.980, 3.435] (assumes normal distribution)


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
# Warmup Iteration   1: 8.568 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 4.097 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.850 ±(99.9%) 0.004 ms/op
Iteration   1: 3.870 ±(99.9%) 0.006 ms/op
Iteration   2: 3.854 ±(99.9%) 0.004 ms/op
Iteration   3: 3.835 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.853 ±(99.9%) 0.323 ms/op [Average]
  (min, avg, max) = (3.835, 3.853, 3.870), stdev = 0.018
  CI (99.9%): [3.530, 4.176] (assumes normal distribution)


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
# Warmup Iteration   1: 8.738 ±(99.9%) 0.101 ms/op
# Warmup Iteration   2: 3.788 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.327 ±(99.9%) 0.009 ms/op
Iteration   1: 3.256 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.184 ms/op
                 createUser·p0.50:   3.178 ms/op
                 createUser·p0.90:   3.645 ms/op
                 createUser·p0.95:   3.932 ms/op
                 createUser·p0.99:   5.759 ms/op
                 createUser·p0.999:  16.073 ms/op
                 createUser·p0.9999: 20.885 ms/op
                 createUser·p1.00:   21.692 ms/op

Iteration   2: 3.273 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.262 ms/op
                 createUser·p0.50:   3.228 ms/op
                 createUser·p0.90:   3.686 ms/op
                 createUser·p0.95:   3.981 ms/op
                 createUser·p0.99:   5.464 ms/op
                 createUser·p0.999:  14.975 ms/op
                 createUser·p0.9999: 22.774 ms/op
                 createUser·p1.00:   23.331 ms/op

Iteration   3: 3.267 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   1.305 ms/op
                 createUser·p0.50:   3.195 ms/op
                 createUser·p0.90:   3.670 ms/op
                 createUser·p0.95:   3.936 ms/op
                 createUser·p0.99:   5.603 ms/op
                 createUser·p0.999:  9.601 ms/op
                 createUser·p0.9999: 20.021 ms/op
                 createUser·p1.00:   21.201 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 293756
  mean =      3.265 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12582 
    [ 2.500,  5.000) = 276732 
    [ 5.000,  7.500) = 3694 
    [ 7.500, 10.000) = 364 
    [10.000, 12.500) = 77 
    [12.500, 15.000) = 60 
    [15.000, 17.500) = 23 
    [17.500, 20.000) = 91 
    [20.000, 22.500) = 114 
    [22.500, 25.000) = 19 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.184 ms/op
     p(50.0000) =      3.199 ms/op
     p(90.0000) =      3.666 ms/op
     p(95.0000) =      3.949 ms/op
     p(99.0000) =      5.571 ms/op
     p(99.9000) =     13.902 ms/op
     p(99.9900) =     22.172 ms/op
     p(99.9990) =     23.134 ms/op
     p(99.9999) =     23.331 ms/op
    p(100.0000) =     23.331 ms/op


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
# Warmup Iteration   1: 8.219 ±(99.9%) 0.093 ms/op
# Warmup Iteration   2: 3.423 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.225 ±(99.9%) 0.008 ms/op
Iteration   1: 3.140 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.067 ms/op
                 existUser·p0.50:   3.064 ms/op
                 existUser·p0.90:   3.457 ms/op
                 existUser·p0.95:   3.711 ms/op
                 existUser·p0.99:   5.407 ms/op
                 existUser·p0.999:  13.875 ms/op
                 existUser·p0.9999: 18.711 ms/op
                 existUser·p1.00:   19.726 ms/op

Iteration   2: 3.161 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.739 ms/op
                 existUser·p0.50:   3.039 ms/op
                 existUser·p0.90:   3.432 ms/op
                 existUser·p0.95:   3.879 ms/op
                 existUser·p0.99:   6.275 ms/op
                 existUser·p0.999:  11.859 ms/op
                 existUser·p0.9999: 19.723 ms/op
                 existUser·p1.00:   20.120 ms/op

Iteration   3: 3.177 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.916 ms/op
                 existUser·p0.50:   3.101 ms/op
                 existUser·p0.90:   3.449 ms/op
                 existUser·p0.95:   3.801 ms/op
                 existUser·p0.99:   6.070 ms/op
                 existUser·p0.999:  14.853 ms/op
                 existUser·p0.9999: 20.185 ms/op
                 existUser·p1.00:   21.004 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 303602
  mean =      3.160 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12330 
    [ 2.500,  5.000) = 284605 
    [ 5.000,  7.500) = 5745 
    [ 7.500, 10.000) = 476 
    [10.000, 12.500) = 121 
    [12.500, 15.000) = 36 
    [15.000, 17.500) = 90 
    [17.500, 20.000) = 177 
    [20.000, 22.500) = 22 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.739 ms/op
     p(50.0000) =      3.068 ms/op
     p(90.0000) =      3.445 ms/op
     p(95.0000) =      3.789 ms/op
     p(99.0000) =      5.833 ms/op
     p(99.9000) =     13.844 ms/op
     p(99.9900) =     19.878 ms/op
     p(99.9990) =     20.904 ms/op
     p(99.9999) =     21.004 ms/op
    p(100.0000) =     21.004 ms/op


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
# Warmup Iteration   1: 7.167 ±(99.9%) 0.090 ms/op
# Warmup Iteration   2: 3.414 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.195 ±(99.9%) 0.007 ms/op
Iteration   1: 3.222 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.828 ms/op
                 getUser·p0.50:   3.101 ms/op
                 getUser·p0.90:   3.498 ms/op
                 getUser·p0.95:   3.903 ms/op
                 getUser·p0.99:   6.197 ms/op
                 getUser·p0.999:  18.285 ms/op
                 getUser·p0.9999: 20.251 ms/op
                 getUser·p1.00:   21.463 ms/op

Iteration   2: 3.250 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.391 ms/op
                 getUser·p0.50:   3.178 ms/op
                 getUser·p0.90:   3.596 ms/op
                 getUser·p0.95:   3.805 ms/op
                 getUser·p0.99:   5.399 ms/op
                 getUser·p0.999:  17.759 ms/op
                 getUser·p0.9999: 21.927 ms/op
                 getUser·p1.00:   22.839 ms/op

Iteration   3: 3.266 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   1.186 ms/op
                 getUser·p0.50:   3.203 ms/op
                 getUser·p0.90:   3.633 ms/op
                 getUser·p0.95:   3.858 ms/op
                 getUser·p0.99:   5.865 ms/op
                 getUser·p0.999:  13.763 ms/op
                 getUser·p0.9999: 18.464 ms/op
                 getUser·p1.00:   19.628 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 295476
  mean =      3.246 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11493 
    [ 2.500,  5.000) = 278100 
    [ 5.000,  7.500) = 4734 
    [ 7.500, 10.000) = 552 
    [10.000, 12.500) = 252 
    [12.500, 15.000) = 83 
    [15.000, 17.500) = 43 
    [17.500, 20.000) = 110 
    [20.000, 22.500) = 107 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.828 ms/op
     p(50.0000) =      3.158 ms/op
     p(90.0000) =      3.588 ms/op
     p(95.0000) =      3.842 ms/op
     p(99.0000) =      5.808 ms/op
     p(99.9000) =     13.804 ms/op
     p(99.9900) =     21.543 ms/op
     p(99.9990) =     22.428 ms/op
     p(99.9999) =     22.839 ms/op
    p(100.0000) =     22.839 ms/op


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
# Warmup Iteration   1: 8.839 ±(99.9%) 0.106 ms/op
# Warmup Iteration   2: 4.193 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.877 ±(99.9%) 0.010 ms/op
Iteration   1: 3.790 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.028 ms/op
                 listUser·p0.50:   3.678 ms/op
                 listUser·p0.90:   4.063 ms/op
                 listUser·p0.95:   4.260 ms/op
                 listUser·p0.99:   6.824 ms/op
                 listUser·p0.999:  14.483 ms/op
                 listUser·p0.9999: 22.992 ms/op
                 listUser·p1.00:   23.298 ms/op

Iteration   2: 3.817 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.802 ms/op
                 listUser·p0.50:   3.695 ms/op
                 listUser·p0.90:   4.162 ms/op
                 listUser·p0.95:   4.375 ms/op
                 listUser·p0.99:   7.004 ms/op
                 listUser·p0.999:  13.599 ms/op
                 listUser·p0.9999: 16.083 ms/op
                 listUser·p1.00:   16.679 ms/op

Iteration   3: 3.809 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.351 ms/op
                 listUser·p0.50:   3.707 ms/op
                 listUser·p0.90:   4.092 ms/op
                 listUser·p0.95:   4.258 ms/op
                 listUser·p0.99:   6.668 ms/op
                 listUser·p0.999:  13.173 ms/op
                 listUser·p0.9999: 13.805 ms/op
                 listUser·p1.00:   14.156 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 252237
  mean =      3.805 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 47 
    [ 2.500,  5.000) = 246037 
    [ 5.000,  7.500) = 4540 
    [ 7.500, 10.000) = 814 
    [10.000, 12.500) = 278 
    [12.500, 15.000) = 435 
    [15.000, 17.500) = 53 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 20 
    [22.500, 25.000) = 12 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.802 ms/op
     p(50.0000) =      3.695 ms/op
     p(90.0000) =      4.104 ms/op
     p(95.0000) =      4.301 ms/op
     p(99.0000) =      6.840 ms/op
     p(99.9000) =     13.664 ms/op
     p(99.9900) =     21.161 ms/op
     p(99.9990) =     23.215 ms/op
     p(99.9999) =     23.298 ms/op
    p(100.0000) =     23.298 ms/op


# Run complete. Total time: 00:13:12

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.964 ± 1.284  ops/ms
ClientPb.existUser                       thrpt       3  10.382 ± 0.985  ops/ms
ClientPb.getUser                         thrpt       3   9.780 ± 3.410  ops/ms
ClientPb.listUser                        thrpt       3   8.435 ± 1.379  ops/ms
ClientPb.createUser                       avgt       3   3.213 ± 0.346   ms/op
ClientPb.existUser                        avgt       3   3.124 ± 1.180   ms/op
ClientPb.getUser                          avgt       3   3.207 ± 0.228   ms/op
ClientPb.listUser                         avgt       3   3.853 ± 0.323   ms/op
ClientPb.createUser                     sample  293756   3.265 ± 0.004   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.184           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.199           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.666           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.949           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.571           ms/op
ClientPb.createUser:createUser·p0.999   sample          13.902           ms/op
ClientPb.createUser:createUser·p0.9999  sample          22.172           ms/op
ClientPb.createUser:createUser·p1.00    sample          23.331           ms/op
ClientPb.existUser                      sample  303602   3.160 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.739           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.068           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.445           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.789           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.833           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.844           ms/op
ClientPb.existUser:existUser·p0.9999    sample          19.878           ms/op
ClientPb.existUser:existUser·p1.00      sample          21.004           ms/op
ClientPb.getUser                        sample  295476   3.246 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.828           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.158           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.588           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.842           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.808           ms/op
ClientPb.getUser:getUser·p0.999         sample          13.804           ms/op
ClientPb.getUser:getUser·p0.9999        sample          21.543           ms/op
ClientPb.getUser:getUser·p1.00          sample          22.839           ms/op
ClientPb.listUser                       sample  252237   3.805 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.802           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.695           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.104           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.301           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.840           ms/op
ClientPb.listUser:listUser·p0.999       sample          13.664           ms/op
ClientPb.listUser:listUser·p0.9999      sample          21.161           ms/op
ClientPb.listUser:listUser·p1.00        sample          23.298           ms/op
