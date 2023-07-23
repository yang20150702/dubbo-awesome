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
# Warmup Iteration   1: 0.867 ops/ms
# Warmup Iteration   2: 1.981 ops/ms
# Warmup Iteration   3: 4.299 ops/ms
Iteration   1: 4.885 ops/ms
Iteration   2: 5.115 ops/ms
Iteration   3: 5.276 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.092 ±(99.9%) 3.584 ops/ms [Average]
  (min, avg, max) = (4.885, 5.092, 5.276), stdev = 0.196
  CI (99.9%): [1.508, 8.676] (assumes normal distribution)


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
# Warmup Iteration   1: 1.403 ops/ms
# Warmup Iteration   2: 3.423 ops/ms
# Warmup Iteration   3: 5.162 ops/ms
Iteration   1: 5.193 ops/ms
Iteration   2: 5.317 ops/ms
Iteration   3: 5.246 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.252 ±(99.9%) 1.135 ops/ms [Average]
  (min, avg, max) = (5.193, 5.252, 5.317), stdev = 0.062
  CI (99.9%): [4.117, 6.388] (assumes normal distribution)


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
# Warmup Iteration   1: 1.211 ops/ms
# Warmup Iteration   2: 3.357 ops/ms
# Warmup Iteration   3: 4.618 ops/ms
Iteration   1: 4.620 ops/ms
Iteration   2: 4.653 ops/ms
Iteration   3: 4.635 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  4.636 ±(99.9%) 0.308 ops/ms [Average]
  (min, avg, max) = (4.620, 4.636, 4.653), stdev = 0.017
  CI (99.9%): [4.328, 4.944] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:55
# Fork: 1 of 1
# Warmup Iteration   1: 1.346 ops/ms
# Warmup Iteration   2: 3.268 ops/ms
# Warmup Iteration   3: 3.925 ops/ms
Iteration   1: 3.955 ops/ms
Iteration   2: 4.122 ops/ms
Iteration   3: 4.003 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.027 ±(99.9%) 1.574 ops/ms [Average]
  (min, avg, max) = (3.955, 4.027, 4.122), stdev = 0.086
  CI (99.9%): [2.453, 5.601] (assumes normal distribution)


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
# Warmup Iteration   1: 22.242 ±(99.9%) 0.146 ms/op
# Warmup Iteration   2: 9.084 ±(99.9%) 0.026 ms/op
# Warmup Iteration   3: 6.770 ±(99.9%) 0.020 ms/op
Iteration   1: 6.545 ±(99.9%) 0.020 ms/op
Iteration   2: 6.355 ±(99.9%) 0.015 ms/op
Iteration   3: 6.506 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  6.469 ±(99.9%) 1.829 ms/op [Average]
  (min, avg, max) = (6.355, 6.469, 6.545), stdev = 0.100
  CI (99.9%): [4.640, 8.298] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:44
# Fork: 1 of 1
# Warmup Iteration   1: 18.734 ±(99.9%) 0.105 ms/op
# Warmup Iteration   2: 7.858 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 6.668 ±(99.9%) 0.014 ms/op
Iteration   1: 6.487 ±(99.9%) 0.012 ms/op
Iteration   2: 6.354 ±(99.9%) 0.013 ms/op
Iteration   3: 6.345 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  6.395 ±(99.9%) 1.447 ms/op [Average]
  (min, avg, max) = (6.345, 6.395, 6.487), stdev = 0.079
  CI (99.9%): [4.948, 7.842] (assumes normal distribution)


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
# Warmup Iteration   1: 22.228 ±(99.9%) 0.114 ms/op
# Warmup Iteration   2: 8.957 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 7.246 ±(99.9%) 0.016 ms/op
Iteration   1: 6.849 ±(99.9%) 0.010 ms/op
Iteration   2: 6.612 ±(99.9%) 0.016 ms/op
Iteration   3: 6.731 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  6.730 ±(99.9%) 2.161 ms/op [Average]
  (min, avg, max) = (6.612, 6.730, 6.849), stdev = 0.118
  CI (99.9%): [4.569, 8.891] (assumes normal distribution)


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
# Warmup Iteration   1: 23.680 ±(99.9%) 0.111 ms/op
# Warmup Iteration   2: 9.535 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 8.031 ±(99.9%) 0.014 ms/op
Iteration   1: 7.665 ±(99.9%) 0.014 ms/op
Iteration   2: 7.641 ±(99.9%) 0.021 ms/op
Iteration   3: 7.992 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.766 ±(99.9%) 3.578 ms/op [Average]
  (min, avg, max) = (7.641, 7.766, 7.992), stdev = 0.196
  CI (99.9%): [4.187, 11.344] (assumes normal distribution)


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
# Warmup Iteration   1: 20.747 ±(99.9%) 0.398 ms/op
# Warmup Iteration   2: 8.251 ±(99.9%) 0.073 ms/op
# Warmup Iteration   3: 7.317 ±(99.9%) 0.057 ms/op
Iteration   1: 6.730 ±(99.9%) 0.045 ms/op
                 createUser·p0.00:   2.462 ms/op
                 createUser·p0.50:   5.702 ms/op
                 createUser·p0.90:   10.355 ms/op
                 createUser·p0.95:   12.730 ms/op
                 createUser·p0.99:   18.317 ms/op
                 createUser·p0.999:  28.901 ms/op
                 createUser·p0.9999: 33.767 ms/op
                 createUser·p1.00:   34.210 ms/op

Iteration   2: 6.535 ±(99.9%) 0.043 ms/op
                 createUser·p0.00:   2.146 ms/op
                 createUser·p0.50:   5.587 ms/op
                 createUser·p0.90:   9.814 ms/op
                 createUser·p0.95:   12.190 ms/op
                 createUser·p0.99:   17.302 ms/op
                 createUser·p0.999:  28.606 ms/op
                 createUser·p0.9999: 44.964 ms/op
                 createUser·p1.00:   46.334 ms/op

Iteration   3: 6.674 ±(99.9%) 0.046 ms/op
                 createUser·p0.00:   1.694 ms/op
                 createUser·p0.50:   5.669 ms/op
                 createUser·p0.90:   9.945 ms/op
                 createUser·p0.95:   12.780 ms/op
                 createUser·p0.99:   18.143 ms/op
                 createUser·p0.999:  35.783 ms/op
                 createUser·p0.9999: 40.777 ms/op
                 createUser·p1.00:   41.026 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 144435
  mean =      6.645 ±(99.9%) 0.026 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 41852 
    [ 5.000, 10.000) = 87905 
    [10.000, 15.000) = 10963 
    [15.000, 20.000) = 2895 
    [20.000, 25.000) = 515 
    [25.000, 30.000) = 156 
    [30.000, 35.000) = 55 
    [35.000, 40.000) = 56 
    [40.000, 45.000) = 34 

  Percentiles, ms/op:
      p(0.0000) =      1.694 ms/op
     p(50.0000) =      5.652 ms/op
     p(90.0000) =     10.060 ms/op
     p(95.0000) =     12.567 ms/op
     p(99.0000) =     18.022 ms/op
     p(99.9000) =     30.468 ms/op
     p(99.9900) =     44.696 ms/op
     p(99.9990) =     46.305 ms/op
     p(99.9999) =     46.334 ms/op
    p(100.0000) =     46.334 ms/op


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
# Warmup Iteration   1: 20.107 ±(99.9%) 0.374 ms/op
# Warmup Iteration   2: 7.580 ±(99.9%) 0.063 ms/op
# Warmup Iteration   3: 6.943 ±(99.9%) 0.051 ms/op
Iteration   1: 6.420 ±(99.9%) 0.043 ms/op
                 existUser·p0.00:   2.339 ms/op
                 existUser·p0.50:   5.276 ms/op
                 existUser·p0.90:   10.240 ms/op
                 existUser·p0.95:   12.559 ms/op
                 existUser·p0.99:   17.662 ms/op
                 existUser·p0.999:  24.754 ms/op
                 existUser·p0.9999: 28.871 ms/op
                 existUser·p1.00:   31.293 ms/op

Iteration   2: 6.258 ±(99.9%) 0.043 ms/op
                 existUser·p0.00:   2.396 ms/op
                 existUser·p0.50:   5.194 ms/op
                 existUser·p0.90:   9.683 ms/op
                 existUser·p0.95:   12.485 ms/op
                 existUser·p0.99:   17.924 ms/op
                 existUser·p0.999:  30.495 ms/op
                 existUser·p0.9999: 37.472 ms/op
                 existUser·p1.00:   38.076 ms/op

Iteration   3: 6.445 ±(99.9%) 0.044 ms/op
                 existUser·p0.00:   2.310 ms/op
                 existUser·p0.50:   5.300 ms/op
                 existUser·p0.90:   10.158 ms/op
                 existUser·p0.95:   13.042 ms/op
                 existUser·p0.99:   18.350 ms/op
                 existUser·p0.999:  26.195 ms/op
                 existUser·p0.9999: 32.047 ms/op
                 existUser·p1.00:   38.076 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 150516
  mean =      6.373 ±(99.9%) 0.025 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14 
    [ 2.500,  5.000) = 61615 
    [ 5.000,  7.500) = 58551 
    [ 7.500, 10.000) = 15195 
    [10.000, 12.500) = 7200 
    [12.500, 15.000) = 4019 
    [15.000, 17.500) = 2145 
    [17.500, 20.000) = 1083 
    [20.000, 22.500) = 373 
    [22.500, 25.000) = 150 
    [25.000, 27.500) = 45 
    [27.500, 30.000) = 42 
    [30.000, 32.500) = 43 
    [32.500, 35.000) = 22 
    [35.000, 37.500) = 14 

  Percentiles, ms/op:
      p(0.0000) =      2.310 ms/op
     p(50.0000) =      5.251 ms/op
     p(90.0000) =     10.027 ms/op
     p(95.0000) =     12.698 ms/op
     p(99.0000) =     17.990 ms/op
     p(99.9000) =     26.296 ms/op
     p(99.9900) =     36.962 ms/op
     p(99.9990) =     38.076 ms/op
     p(99.9999) =     38.076 ms/op
    p(100.0000) =     38.076 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:13
# Fork: 1 of 1
# Warmup Iteration   1: 19.660 ±(99.9%) 0.321 ms/op
# Warmup Iteration   2: 8.294 ±(99.9%) 0.073 ms/op
# Warmup Iteration   3: 6.875 ±(99.9%) 0.050 ms/op
Iteration   1: 6.992 ±(99.9%) 0.050 ms/op
                 getUser·p0.00:   2.773 ms/op
                 getUser·p0.50:   5.833 ms/op
                 getUser·p0.90:   10.813 ms/op
                 getUser·p0.95:   13.910 ms/op
                 getUser·p0.99:   20.054 ms/op
                 getUser·p0.999:  27.300 ms/op
                 getUser·p0.9999: 35.483 ms/op
                 getUser·p1.00:   37.159 ms/op

Iteration   2: 6.635 ±(99.9%) 0.035 ms/op
                 getUser·p0.00:   2.224 ms/op
                 getUser·p0.50:   6.013 ms/op
                 getUser·p0.90:   9.093 ms/op
                 getUser·p0.95:   10.797 ms/op
                 getUser·p0.99:   15.663 ms/op
                 getUser·p0.999:  32.391 ms/op
                 getUser·p0.9999: 36.176 ms/op
                 getUser·p1.00:   36.962 ms/op

Iteration   3: 6.448 ±(99.9%) 0.028 ms/op
                 getUser·p0.00:   2.187 ms/op
                 getUser·p0.50:   6.038 ms/op
                 getUser·p0.90:   8.487 ms/op
                 getUser·p0.95:   9.552 ms/op
                 getUser·p0.99:   11.846 ms/op
                 getUser·p0.999:  33.227 ms/op
                 getUser·p0.9999: 36.919 ms/op
                 getUser·p1.00:   40.763 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 143475
  mean =      6.684 ±(99.9%) 0.022 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 24318 
    [ 5.000, 10.000) = 108291 
    [10.000, 15.000) = 8409 
    [15.000, 20.000) = 1811 
    [20.000, 25.000) = 440 
    [25.000, 30.000) = 55 
    [30.000, 35.000) = 90 
    [35.000, 40.000) = 60 
    [40.000, 45.000) = 1 

  Percentiles, ms/op:
      p(0.0000) =      2.187 ms/op
     p(50.0000) =      5.980 ms/op
     p(90.0000) =      9.290 ms/op
     p(95.0000) =     11.158 ms/op
     p(99.0000) =     17.039 ms/op
     p(99.9000) =     31.556 ms/op
     p(99.9900) =     36.612 ms/op
     p(99.9990) =     39.624 ms/op
     p(99.9999) =     40.763 ms/op
    p(100.0000) =     40.763 ms/op


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
# Warmup Iteration   1: 23.316 ±(99.9%) 0.459 ms/op
# Warmup Iteration   2: 10.719 ±(99.9%) 0.098 ms/op
# Warmup Iteration   3: 7.992 ±(99.9%) 0.042 ms/op
Iteration   1: 7.612 ±(99.9%) 0.033 ms/op
                 listUser·p0.00:   3.150 ms/op
                 listUser·p0.50:   7.119 ms/op
                 listUser·p0.90:   10.147 ms/op
                 listUser·p0.95:   11.141 ms/op
                 listUser·p0.99:   13.765 ms/op
                 listUser·p0.999:  30.731 ms/op
                 listUser·p0.9999: 35.269 ms/op
                 listUser·p1.00:   36.241 ms/op

Iteration   2: 8.302 ±(99.9%) 0.066 ms/op
                 listUser·p0.00:   1.247 ms/op
                 listUser·p0.50:   6.824 ms/op
                 listUser·p0.90:   13.206 ms/op
                 listUser·p0.95:   16.056 ms/op
                 listUser·p0.99:   23.432 ms/op
                 listUser·p0.999:  33.948 ms/op
                 listUser·p0.9999: 40.257 ms/op
                 listUser·p1.00:   42.074 ms/op

Iteration   3: 7.703 ±(99.9%) 0.055 ms/op
                 listUser·p0.00:   2.998 ms/op
                 listUser·p0.50:   6.455 ms/op
                 listUser·p0.90:   11.665 ms/op
                 listUser·p0.95:   14.336 ms/op
                 listUser·p0.99:   21.103 ms/op
                 listUser·p0.999:  34.701 ms/op
                 listUser·p0.9999: 45.003 ms/op
                 listUser·p1.00:   45.679 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 122183
  mean =      7.861 ±(99.9%) 0.030 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 2603 
    [ 5.000, 10.000) = 100041 
    [10.000, 15.000) = 15065 
    [15.000, 20.000) = 2965 
    [20.000, 25.000) = 986 
    [25.000, 30.000) = 297 
    [30.000, 35.000) = 153 
    [35.000, 40.000) = 47 
    [40.000, 45.000) = 22 

  Percentiles, ms/op:
      p(0.0000) =      1.247 ms/op
     p(50.0000) =      6.840 ms/op
     p(90.0000) =     11.370 ms/op
     p(95.0000) =     13.861 ms/op
     p(99.0000) =     20.977 ms/op
     p(99.9000) =     32.965 ms/op
     p(99.9900) =     43.815 ms/op
     p(99.9990) =     45.548 ms/op
     p(99.9999) =     45.679 ms/op
    p(100.0000) =     45.679 ms/op


# Run complete. Total time: 00:13:20

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.092 ± 3.584  ops/ms
ClientPb.existUser                       thrpt       3   5.252 ± 1.135  ops/ms
ClientPb.getUser                         thrpt       3   4.636 ± 0.308  ops/ms
ClientPb.listUser                        thrpt       3   4.027 ± 1.574  ops/ms
ClientPb.createUser                       avgt       3   6.469 ± 1.829   ms/op
ClientPb.existUser                        avgt       3   6.395 ± 1.447   ms/op
ClientPb.getUser                          avgt       3   6.730 ± 2.161   ms/op
ClientPb.listUser                         avgt       3   7.766 ± 3.578   ms/op
ClientPb.createUser                     sample  144435   6.645 ± 0.026   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.694           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.652           ms/op
ClientPb.createUser:createUser·p0.90    sample          10.060           ms/op
ClientPb.createUser:createUser·p0.95    sample          12.567           ms/op
ClientPb.createUser:createUser·p0.99    sample          18.022           ms/op
ClientPb.createUser:createUser·p0.999   sample          30.468           ms/op
ClientPb.createUser:createUser·p0.9999  sample          44.696           ms/op
ClientPb.createUser:createUser·p1.00    sample          46.334           ms/op
ClientPb.existUser                      sample  150516   6.373 ± 0.025   ms/op
ClientPb.existUser:existUser·p0.00      sample           2.310           ms/op
ClientPb.existUser:existUser·p0.50      sample           5.251           ms/op
ClientPb.existUser:existUser·p0.90      sample          10.027           ms/op
ClientPb.existUser:existUser·p0.95      sample          12.698           ms/op
ClientPb.existUser:existUser·p0.99      sample          17.990           ms/op
ClientPb.existUser:existUser·p0.999     sample          26.296           ms/op
ClientPb.existUser:existUser·p0.9999    sample          36.962           ms/op
ClientPb.existUser:existUser·p1.00      sample          38.076           ms/op
ClientPb.getUser                        sample  143475   6.684 ± 0.022   ms/op
ClientPb.getUser:getUser·p0.00          sample           2.187           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.980           ms/op
ClientPb.getUser:getUser·p0.90          sample           9.290           ms/op
ClientPb.getUser:getUser·p0.95          sample          11.158           ms/op
ClientPb.getUser:getUser·p0.99          sample          17.039           ms/op
ClientPb.getUser:getUser·p0.999         sample          31.556           ms/op
ClientPb.getUser:getUser·p0.9999        sample          36.612           ms/op
ClientPb.getUser:getUser·p1.00          sample          40.763           ms/op
ClientPb.listUser                       sample  122183   7.861 ± 0.030   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.247           ms/op
ClientPb.listUser:listUser·p0.50        sample           6.840           ms/op
ClientPb.listUser:listUser·p0.90        sample          11.370           ms/op
ClientPb.listUser:listUser·p0.95        sample          13.861           ms/op
ClientPb.listUser:listUser·p0.99        sample          20.977           ms/op
ClientPb.listUser:listUser·p0.999       sample          32.965           ms/op
ClientPb.listUser:listUser·p0.9999      sample          43.815           ms/op
ClientPb.listUser:listUser·p1.00        sample          45.679           ms/op
