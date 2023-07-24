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
# Warmup Iteration   1: 2.349 ops/ms
# Warmup Iteration   2: 5.957 ops/ms
# Warmup Iteration   3: 8.996 ops/ms
Iteration   1: 9.683 ops/ms
Iteration   2: 9.780 ops/ms
Iteration   3: 9.901 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.788 ±(99.9%) 1.992 ops/ms [Average]
  (min, avg, max) = (9.683, 9.788, 9.901), stdev = 0.109
  CI (99.9%): [7.796, 11.780] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:07
# Fork: 1 of 1
# Warmup Iteration   1: 3.730 ops/ms
# Warmup Iteration   2: 9.295 ops/ms
# Warmup Iteration   3: 9.896 ops/ms
Iteration   1: 10.162 ops/ms
Iteration   2: 10.161 ops/ms
Iteration   3: 10.707 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.343 ±(99.9%) 5.737 ops/ms [Average]
  (min, avg, max) = (10.161, 10.343, 10.707), stdev = 0.314
  CI (99.9%): [4.606, 16.081] (assumes normal distribution)


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
# Warmup Iteration   1: 3.540 ops/ms
# Warmup Iteration   2: 9.027 ops/ms
# Warmup Iteration   3: 9.976 ops/ms
Iteration   1: 9.966 ops/ms
Iteration   2: 10.221 ops/ms
Iteration   3: 10.158 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  10.115 ±(99.9%) 2.425 ops/ms [Average]
  (min, avg, max) = (9.966, 10.115, 10.221), stdev = 0.133
  CI (99.9%): [7.690, 12.540] (assumes normal distribution)


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
# Warmup Iteration   1: 2.973 ops/ms
# Warmup Iteration   2: 7.485 ops/ms
# Warmup Iteration   3: 8.109 ops/ms
Iteration   1: 8.669 ops/ms
Iteration   2: 8.727 ops/ms
Iteration   3: 8.729 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.708 ±(99.9%) 0.620 ops/ms [Average]
  (min, avg, max) = (8.669, 8.708, 8.729), stdev = 0.034
  CI (99.9%): [8.089, 9.328] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:45
# Fork: 1 of 1
# Warmup Iteration   1: 8.567 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 3.642 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.393 ±(99.9%) 0.005 ms/op
Iteration   1: 3.244 ±(99.9%) 0.006 ms/op
Iteration   2: 3.223 ±(99.9%) 0.006 ms/op
Iteration   3: 3.382 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.283 ±(99.9%) 1.572 ms/op [Average]
  (min, avg, max) = (3.223, 3.283, 3.382), stdev = 0.086
  CI (99.9%): [1.711, 4.855] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 6.981 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 3.435 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.161 ±(99.9%) 0.008 ms/op
Iteration   1: 3.173 ±(99.9%) 0.007 ms/op
Iteration   2: 3.184 ±(99.9%) 0.005 ms/op
Iteration   3: 3.171 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.176 ±(99.9%) 0.136 ms/op [Average]
  (min, avg, max) = (3.171, 3.176, 3.184), stdev = 0.007
  CI (99.9%): [3.040, 3.312] (assumes normal distribution)


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
# Warmup Iteration   1: 7.240 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 3.454 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.393 ±(99.9%) 0.002 ms/op
Iteration   1: 3.193 ±(99.9%) 0.005 ms/op
Iteration   2: 3.229 ±(99.9%) 0.002 ms/op
Iteration   3: 3.155 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.192 ±(99.9%) 0.678 ms/op [Average]
  (min, avg, max) = (3.155, 3.192, 3.229), stdev = 0.037
  CI (99.9%): [2.515, 3.870] (assumes normal distribution)


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
# Warmup Iteration   1: 10.476 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 4.508 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.883 ±(99.9%) 0.008 ms/op
Iteration   1: 3.719 ±(99.9%) 0.006 ms/op
Iteration   2: 3.770 ±(99.9%) 0.011 ms/op
Iteration   3: 3.804 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.764 ±(99.9%) 0.776 ms/op [Average]
  (min, avg, max) = (3.719, 3.764, 3.804), stdev = 0.043
  CI (99.9%): [2.988, 4.540] (assumes normal distribution)


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
# Warmup Iteration   1: 9.352 ±(99.9%) 0.116 ms/op
# Warmup Iteration   2: 3.834 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.246 ±(99.9%) 0.009 ms/op
Iteration   1: 3.191 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.298 ms/op
                 createUser·p0.50:   3.043 ms/op
                 createUser·p0.90:   3.584 ms/op
                 createUser·p0.95:   3.863 ms/op
                 createUser·p0.99:   5.612 ms/op
                 createUser·p0.999:  18.612 ms/op
                 createUser·p0.9999: 20.120 ms/op
                 createUser·p1.00:   21.266 ms/op

Iteration   2: 3.174 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.223 ms/op
                 createUser·p0.50:   3.121 ms/op
                 createUser·p0.90:   3.408 ms/op
                 createUser·p0.95:   3.690 ms/op
                 createUser·p0.99:   5.358 ms/op
                 createUser·p0.999:  15.879 ms/op
                 createUser·p0.9999: 24.347 ms/op
                 createUser·p1.00:   25.395 ms/op

Iteration   3: 3.167 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   1.413 ms/op
                 createUser·p0.50:   3.072 ms/op
                 createUser·p0.90:   3.494 ms/op
                 createUser·p0.95:   3.723 ms/op
                 createUser·p0.99:   5.530 ms/op
                 createUser·p0.999:  14.762 ms/op
                 createUser·p0.9999: 18.547 ms/op
                 createUser·p1.00:   18.973 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 302169
  mean =      3.177 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12094 
    [ 2.500,  5.000) = 285044 
    [ 5.000,  7.500) = 4235 
    [ 7.500, 10.000) = 325 
    [10.000, 12.500) = 95 
    [12.500, 15.000) = 58 
    [15.000, 17.500) = 71 
    [17.500, 20.000) = 180 
    [20.000, 22.500) = 35 
    [22.500, 25.000) = 30 
    [25.000, 27.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      1.223 ms/op
     p(50.0000) =      3.080 ms/op
     p(90.0000) =      3.502 ms/op
     p(95.0000) =      3.764 ms/op
     p(99.0000) =      5.532 ms/op
     p(99.9000) =     15.677 ms/op
     p(99.9900) =     23.298 ms/op
     p(99.9990) =     24.969 ms/op
     p(99.9999) =     25.395 ms/op
    p(100.0000) =     25.395 ms/op


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
# Warmup Iteration   1: 7.807 ±(99.9%) 0.088 ms/op
# Warmup Iteration   2: 3.503 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.213 ±(99.9%) 0.008 ms/op
Iteration   1: 3.071 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.608 ms/op
                 existUser·p0.50:   3.092 ms/op
                 existUser·p0.90:   3.219 ms/op
                 existUser·p0.95:   3.301 ms/op
                 existUser·p0.99:   5.235 ms/op
                 existUser·p0.999:  8.815 ms/op
                 existUser·p0.9999: 22.045 ms/op
                 existUser·p1.00:   23.691 ms/op

Iteration   2: 3.182 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.178 ms/op
                 existUser·p0.50:   3.158 ms/op
                 existUser·p0.90:   3.523 ms/op
                 existUser·p0.95:   3.858 ms/op
                 existUser·p0.99:   5.243 ms/op
                 existUser·p0.999:  14.107 ms/op
                 existUser·p0.9999: 21.650 ms/op
                 existUser·p1.00:   22.512 ms/op

Iteration   3: 3.118 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.231 ms/op
                 existUser·p0.50:   3.006 ms/op
                 existUser·p0.90:   3.457 ms/op
                 existUser·p0.95:   3.703 ms/op
                 existUser·p0.99:   5.415 ms/op
                 existUser·p0.999:  12.540 ms/op
                 existUser·p0.9999: 24.992 ms/op
                 existUser·p1.00:   25.756 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 307297
  mean =      3.123 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 24010 
    [ 2.500,  5.000) = 278838 
    [ 5.000,  7.500) = 3829 
    [ 7.500, 10.000) = 260 
    [10.000, 12.500) = 28 
    [12.500, 15.000) = 47 
    [15.000, 17.500) = 42 
    [17.500, 20.000) = 104 
    [20.000, 22.500) = 98 
    [22.500, 25.000) = 31 
    [25.000, 27.500) = 10 

  Percentiles, ms/op:
      p(0.0000) =      1.178 ms/op
     p(50.0000) =      3.101 ms/op
     p(90.0000) =      3.387 ms/op
     p(95.0000) =      3.658 ms/op
     p(99.0000) =      5.292 ms/op
     p(99.9000) =     13.604 ms/op
     p(99.9900) =     23.709 ms/op
     p(99.9990) =     25.360 ms/op
     p(99.9999) =     25.756 ms/op
    p(100.0000) =     25.756 ms/op


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
# Warmup Iteration   1: 8.447 ±(99.9%) 0.097 ms/op
# Warmup Iteration   2: 3.492 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.385 ±(99.9%) 0.011 ms/op
Iteration   1: 3.179 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.434 ms/op
                 getUser·p0.50:   3.019 ms/op
                 getUser·p0.90:   3.391 ms/op
                 getUser·p0.95:   3.863 ms/op
                 getUser·p0.99:   6.103 ms/op
                 getUser·p0.999:  17.617 ms/op
                 getUser·p0.9999: 22.308 ms/op
                 getUser·p1.00:   23.167 ms/op

Iteration   2: 3.119 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   1.008 ms/op
                 getUser·p0.50:   3.035 ms/op
                 getUser·p0.90:   3.424 ms/op
                 getUser·p0.95:   3.555 ms/op
                 getUser·p0.99:   4.538 ms/op
                 getUser·p0.999:  10.813 ms/op
                 getUser·p0.9999: 20.283 ms/op
                 getUser·p1.00:   21.594 ms/op

Iteration   3: 3.207 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   1.567 ms/op
                 getUser·p0.50:   3.088 ms/op
                 getUser·p0.90:   3.564 ms/op
                 getUser·p0.95:   3.858 ms/op
                 getUser·p0.99:   5.726 ms/op
                 getUser·p0.999:  11.162 ms/op
                 getUser·p0.9999: 20.382 ms/op
                 getUser·p1.00:   21.987 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 303026
  mean =      3.168 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4774 
    [ 2.500,  5.000) = 291775 
    [ 5.000,  7.500) = 5609 
    [ 7.500, 10.000) = 424 
    [10.000, 12.500) = 52 
    [12.500, 15.000) = 85 
    [15.000, 17.500) = 82 
    [17.500, 20.000) = 127 
    [20.000, 22.500) = 91 
    [22.500, 25.000) = 7 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.008 ms/op
     p(50.0000) =      3.039 ms/op
     p(90.0000) =      3.461 ms/op
     p(95.0000) =      3.699 ms/op
     p(99.0000) =      5.677 ms/op
     p(99.9000) =     15.221 ms/op
     p(99.9900) =     21.125 ms/op
     p(99.9990) =     22.774 ms/op
     p(99.9999) =     23.167 ms/op
    p(100.0000) =     23.167 ms/op


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
# Warmup Iteration   1: 8.816 ±(99.9%) 0.111 ms/op
# Warmup Iteration   2: 4.057 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.848 ±(99.9%) 0.012 ms/op
Iteration   1: 3.807 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.154 ms/op
                 listUser·p0.50:   3.727 ms/op
                 listUser·p0.90:   4.104 ms/op
                 listUser·p0.95:   4.325 ms/op
                 listUser·p0.99:   6.889 ms/op
                 listUser·p0.999:  17.039 ms/op
                 listUser·p0.9999: 18.973 ms/op
                 listUser·p1.00:   19.595 ms/op

Iteration   2: 3.767 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.925 ms/op
                 listUser·p0.50:   3.596 ms/op
                 listUser·p0.90:   4.088 ms/op
                 listUser·p0.95:   4.383 ms/op
                 listUser·p0.99:   7.520 ms/op
                 listUser·p0.999:  15.024 ms/op
                 listUser·p0.9999: 17.548 ms/op
                 listUser·p1.00:   18.317 ms/op

Iteration   3: 3.674 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.585 ms/op
                 listUser·p0.50:   3.674 ms/op
                 listUser·p0.90:   3.781 ms/op
                 listUser·p0.95:   3.928 ms/op
                 listUser·p0.99:   6.454 ms/op
                 listUser·p0.999:  13.320 ms/op
                 listUser·p0.9999: 14.352 ms/op
                 listUser·p1.00:   14.500 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 255921
  mean =      3.748 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 0 
    [ 1.250,  2.500) = 74 
    [ 2.500,  3.750) = 179048 
    [ 3.750,  5.000) = 69437 
    [ 5.000,  6.250) = 2979 
    [ 6.250,  7.500) = 2531 
    [ 7.500,  8.750) = 796 
    [ 8.750, 10.000) = 377 
    [10.000, 11.250) = 78 
    [11.250, 12.500) = 82 
    [12.500, 13.750) = 199 
    [13.750, 15.000) = 105 
    [15.000, 16.250) = 59 
    [16.250, 17.500) = 86 
    [17.500, 18.750) = 48 

  Percentiles, ms/op:
      p(0.0000) =      1.585 ms/op
     p(50.0000) =      3.670 ms/op
     p(90.0000) =      4.026 ms/op
     p(95.0000) =      4.268 ms/op
     p(99.0000) =      6.970 ms/op
     p(99.9000) =     14.305 ms/op
     p(99.9900) =     18.429 ms/op
     p(99.9990) =     19.460 ms/op
     p(99.9999) =     19.595 ms/op
    p(100.0000) =     19.595 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.788 ± 1.992  ops/ms
ClientPb.existUser                       thrpt       3  10.343 ± 5.737  ops/ms
ClientPb.getUser                         thrpt       3  10.115 ± 2.425  ops/ms
ClientPb.listUser                        thrpt       3   8.708 ± 0.620  ops/ms
ClientPb.createUser                       avgt       3   3.283 ± 1.572   ms/op
ClientPb.existUser                        avgt       3   3.176 ± 0.136   ms/op
ClientPb.getUser                          avgt       3   3.192 ± 0.678   ms/op
ClientPb.listUser                         avgt       3   3.764 ± 0.776   ms/op
ClientPb.createUser                     sample  302169   3.177 ± 0.004   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.223           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.080           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.502           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.764           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.532           ms/op
ClientPb.createUser:createUser·p0.999   sample          15.677           ms/op
ClientPb.createUser:createUser·p0.9999  sample          23.298           ms/op
ClientPb.createUser:createUser·p1.00    sample          25.395           ms/op
ClientPb.existUser                      sample  307297   3.123 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.178           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.101           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.387           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.658           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.292           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.604           ms/op
ClientPb.existUser:existUser·p0.9999    sample          23.709           ms/op
ClientPb.existUser:existUser·p1.00      sample          25.756           ms/op
ClientPb.getUser                        sample  303026   3.168 ± 0.004   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.008           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.039           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.461           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.699           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.677           ms/op
ClientPb.getUser:getUser·p0.999         sample          15.221           ms/op
ClientPb.getUser:getUser·p0.9999        sample          21.125           ms/op
ClientPb.getUser:getUser·p1.00          sample          23.167           ms/op
ClientPb.listUser                       sample  255921   3.748 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.585           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.670           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.026           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.268           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.970           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.305           ms/op
ClientPb.listUser:listUser·p0.9999      sample          18.429           ms/op
ClientPb.listUser:listUser·p1.00        sample          19.595           ms/op
