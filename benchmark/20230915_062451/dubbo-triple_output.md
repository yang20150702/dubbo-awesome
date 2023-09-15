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
# Warmup Iteration   1: 2.030 ops/ms
# Warmup Iteration   2: 5.382 ops/ms
# Warmup Iteration   3: 8.848 ops/ms
Iteration   1: 9.311 ops/ms
Iteration   2: 9.445 ops/ms
Iteration   3: 9.422 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.393 ±(99.9%) 1.312 ops/ms [Average]
  (min, avg, max) = (9.311, 9.393, 9.445), stdev = 0.072
  CI (99.9%): [8.081, 10.705] (assumes normal distribution)


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
# Warmup Iteration   1: 3.016 ops/ms
# Warmup Iteration   2: 8.584 ops/ms
# Warmup Iteration   3: 9.510 ops/ms
Iteration   1: 9.850 ops/ms
Iteration   2: 9.950 ops/ms
Iteration   3: 9.917 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.906 ±(99.9%) 0.928 ops/ms [Average]
  (min, avg, max) = (9.850, 9.906, 9.950), stdev = 0.051
  CI (99.9%): [8.978, 10.834] (assumes normal distribution)


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
# Warmup Iteration   1: 3.084 ops/ms
# Warmup Iteration   2: 8.347 ops/ms
# Warmup Iteration   3: 9.276 ops/ms
Iteration   1: 9.446 ops/ms
Iteration   2: 9.582 ops/ms
Iteration   3: 9.452 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.493 ±(99.9%) 1.399 ops/ms [Average]
  (min, avg, max) = (9.446, 9.493, 9.582), stdev = 0.077
  CI (99.9%): [8.094, 10.893] (assumes normal distribution)


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
# Warmup Iteration   1: 2.981 ops/ms
# Warmup Iteration   2: 7.476 ops/ms
# Warmup Iteration   3: 7.713 ops/ms
Iteration   1: 7.840 ops/ms
Iteration   2: 8.177 ops/ms
Iteration   3: 7.858 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.958 ±(99.9%) 3.455 ops/ms [Average]
  (min, avg, max) = (7.840, 7.958, 8.177), stdev = 0.189
  CI (99.9%): [4.503, 11.413] (assumes normal distribution)


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
# Warmup Iteration   1: 9.090 ±(99.9%) 0.060 ms/op
# Warmup Iteration   2: 3.733 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.633 ±(99.9%) 0.005 ms/op
Iteration   1: 3.394 ±(99.9%) 0.005 ms/op
Iteration   2: 3.383 ±(99.9%) 0.004 ms/op
Iteration   3: 3.399 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.392 ±(99.9%) 0.151 ms/op [Average]
  (min, avg, max) = (3.383, 3.392, 3.399), stdev = 0.008
  CI (99.9%): [3.240, 3.543] (assumes normal distribution)


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
# Warmup Iteration   1: 9.192 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.579 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.359 ±(99.9%) 0.003 ms/op
Iteration   1: 3.370 ±(99.9%) 0.004 ms/op
Iteration   2: 3.307 ±(99.9%) 0.006 ms/op
Iteration   3: 3.237 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.305 ±(99.9%) 1.206 ms/op [Average]
  (min, avg, max) = (3.237, 3.305, 3.370), stdev = 0.066
  CI (99.9%): [2.098, 4.511] (assumes normal distribution)


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
# Warmup Iteration   1: 9.728 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.648 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.449 ±(99.9%) 0.005 ms/op
Iteration   1: 3.388 ±(99.9%) 0.003 ms/op
Iteration   2: 3.421 ±(99.9%) 0.004 ms/op
Iteration   3: 3.487 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.432 ±(99.9%) 0.915 ms/op [Average]
  (min, avg, max) = (3.388, 3.432, 3.487), stdev = 0.050
  CI (99.9%): [2.518, 4.347] (assumes normal distribution)


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
# Warmup Iteration   1: 11.503 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 4.463 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.160 ±(99.9%) 0.004 ms/op
Iteration   1: 3.999 ±(99.9%) 0.005 ms/op
Iteration   2: 3.968 ±(99.9%) 0.006 ms/op
Iteration   3: 4.028 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.998 ±(99.9%) 0.545 ms/op [Average]
  (min, avg, max) = (3.968, 3.998, 4.028), stdev = 0.030
  CI (99.9%): [3.453, 4.543] (assumes normal distribution)


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
# Warmup Iteration   1: 9.360 ±(99.9%) 0.127 ms/op
# Warmup Iteration   2: 3.787 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.492 ±(99.9%) 0.011 ms/op
Iteration   1: 3.407 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.626 ms/op
                 createUser·p0.50:   3.326 ms/op
                 createUser·p0.90:   3.842 ms/op
                 createUser·p0.95:   4.145 ms/op
                 createUser·p0.99:   5.751 ms/op
                 createUser·p0.999:  20.579 ms/op
                 createUser·p0.9999: 24.557 ms/op
                 createUser·p1.00:   25.395 ms/op

Iteration   2: 3.317 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.990 ms/op
                 createUser·p0.50:   3.248 ms/op
                 createUser·p0.90:   3.629 ms/op
                 createUser·p0.95:   3.867 ms/op
                 createUser·p0.99:   5.063 ms/op
                 createUser·p0.999:  19.373 ms/op
                 createUser·p0.9999: 25.071 ms/op
                 createUser·p1.00:   26.444 ms/op

Iteration   3: 3.367 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.178 ms/op
                 createUser·p0.50:   3.289 ms/op
                 createUser·p0.90:   3.768 ms/op
                 createUser·p0.95:   3.990 ms/op
                 createUser·p0.99:   5.423 ms/op
                 createUser·p0.999:  16.860 ms/op
                 createUser·p0.9999: 24.202 ms/op
                 createUser·p1.00:   25.100 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 285228
  mean =      3.363 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8382 
    [ 2.500,  5.000) = 272903 
    [ 5.000,  7.500) = 3204 
    [ 7.500, 10.000) = 354 
    [10.000, 12.500) = 64 
    [12.500, 15.000) = 25 
    [15.000, 17.500) = 12 
    [17.500, 20.000) = 60 
    [20.000, 22.500) = 63 
    [22.500, 25.000) = 144 
    [25.000, 27.500) = 17 

  Percentiles, ms/op:
      p(0.0000) =      0.990 ms/op
     p(50.0000) =      3.285 ms/op
     p(90.0000) =      3.752 ms/op
     p(95.0000) =      4.006 ms/op
     p(99.0000) =      5.472 ms/op
     p(99.9000) =     17.392 ms/op
     p(99.9900) =     24.740 ms/op
     p(99.9990) =     25.731 ms/op
     p(99.9999) =     26.444 ms/op
    p(100.0000) =     26.444 ms/op


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
# Warmup Iteration   1: 9.854 ±(99.9%) 0.116 ms/op
# Warmup Iteration   2: 3.564 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.367 ±(99.9%) 0.008 ms/op
Iteration   1: 3.334 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.257 ms/op
                 existUser·p0.50:   3.228 ms/op
                 existUser·p0.90:   3.740 ms/op
                 existUser·p0.95:   4.055 ms/op
                 existUser·p0.99:   5.688 ms/op
                 existUser·p0.999:  10.486 ms/op
                 existUser·p0.9999: 19.327 ms/op
                 existUser·p1.00:   19.956 ms/op

Iteration   2: 3.281 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.538 ms/op
                 existUser·p0.50:   3.232 ms/op
                 existUser·p0.90:   3.613 ms/op
                 existUser·p0.95:   3.867 ms/op
                 existUser·p0.99:   5.521 ms/op
                 existUser·p0.999:  14.926 ms/op
                 existUser·p0.9999: 20.742 ms/op
                 existUser·p1.00:   21.660 ms/op

Iteration   3: 3.416 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.329 ms/op
                 existUser·p0.50:   3.297 ms/op
                 existUser·p0.90:   3.805 ms/op
                 existUser·p0.95:   4.227 ms/op
                 existUser·p0.99:   7.053 ms/op
                 existUser·p0.999:  20.263 ms/op
                 existUser·p0.9999: 23.188 ms/op
                 existUser·p1.00:   24.576 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 287066
  mean =      3.343 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9591 
    [ 2.500,  5.000) = 271634 
    [ 5.000,  7.500) = 4483 
    [ 7.500, 10.000) = 816 
    [10.000, 12.500) = 235 
    [12.500, 15.000) = 48 
    [15.000, 17.500) = 7 
    [17.500, 20.000) = 128 
    [20.000, 22.500) = 90 
    [22.500, 25.000) = 34 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.538 ms/op
     p(50.0000) =      3.256 ms/op
     p(90.0000) =      3.723 ms/op
     p(95.0000) =      4.051 ms/op
     p(99.0000) =      5.988 ms/op
     p(99.9000) =     13.826 ms/op
     p(99.9900) =     22.544 ms/op
     p(99.9990) =     24.081 ms/op
     p(99.9999) =     24.576 ms/op
    p(100.0000) =     24.576 ms/op


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
# Warmup Iteration   1: 8.346 ±(99.9%) 0.097 ms/op
# Warmup Iteration   2: 3.631 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.499 ±(99.9%) 0.010 ms/op
Iteration   1: 3.388 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.143 ms/op
                 getUser·p0.50:   3.260 ms/op
                 getUser·p0.90:   3.797 ms/op
                 getUser·p0.95:   4.084 ms/op
                 getUser·p0.99:   6.327 ms/op
                 getUser·p0.999:  19.604 ms/op
                 getUser·p0.9999: 22.479 ms/op
                 getUser·p1.00:   23.200 ms/op

Iteration   2: 3.410 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.278 ms/op
                 getUser·p0.50:   3.342 ms/op
                 getUser·p0.90:   3.719 ms/op
                 getUser·p0.95:   3.879 ms/op
                 getUser·p0.99:   5.612 ms/op
                 getUser·p0.999:  21.038 ms/op
                 getUser·p0.9999: 25.219 ms/op
                 getUser·p1.00:   25.657 ms/op

Iteration   3: 3.400 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.069 ms/op
                 getUser·p0.50:   3.277 ms/op
                 getUser·p0.90:   3.764 ms/op
                 getUser·p0.95:   4.047 ms/op
                 getUser·p0.99:   6.176 ms/op
                 getUser·p0.999:  16.093 ms/op
                 getUser·p0.9999: 23.953 ms/op
                 getUser·p1.00:   25.133 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 282209
  mean =      3.400 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4843 
    [ 2.500,  5.000) = 271974 
    [ 5.000,  7.500) = 4265 
    [ 7.500, 10.000) = 620 
    [10.000, 12.500) = 103 
    [12.500, 15.000) = 64 
    [15.000, 17.500) = 77 
    [17.500, 20.000) = 32 
    [20.000, 22.500) = 133 
    [22.500, 25.000) = 84 
    [25.000, 27.500) = 14 

  Percentiles, ms/op:
      p(0.0000) =      1.069 ms/op
     p(50.0000) =      3.293 ms/op
     p(90.0000) =      3.756 ms/op
     p(95.0000) =      3.998 ms/op
     p(99.0000) =      6.046 ms/op
     p(99.9000) =     16.256 ms/op
     p(99.9900) =     24.012 ms/op
     p(99.9990) =     25.559 ms/op
     p(99.9999) =     25.657 ms/op
    p(100.0000) =     25.657 ms/op


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
# Warmup Iteration   1: 10.175 ±(99.9%) 0.138 ms/op
# Warmup Iteration   2: 4.332 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.082 ±(99.9%) 0.012 ms/op
Iteration   1: 4.090 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.278 ms/op
                 listUser·p0.50:   3.973 ms/op
                 listUser·p0.90:   4.506 ms/op
                 listUser·p0.95:   4.719 ms/op
                 listUser·p0.99:   6.791 ms/op
                 listUser·p0.999:  18.933 ms/op
                 listUser·p0.9999: 22.502 ms/op
                 listUser·p1.00:   23.495 ms/op

Iteration   2: 4.088 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.327 ms/op
                 listUser·p0.50:   3.924 ms/op
                 listUser·p0.90:   4.489 ms/op
                 listUser·p0.95:   4.768 ms/op
                 listUser·p0.99:   7.447 ms/op
                 listUser·p0.999:  14.729 ms/op
                 listUser·p0.9999: 17.338 ms/op
                 listUser·p1.00:   19.857 ms/op

Iteration   3: 4.031 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.204 ms/op
                 listUser·p0.50:   3.899 ms/op
                 listUser·p0.90:   4.407 ms/op
                 listUser·p0.95:   4.661 ms/op
                 listUser·p0.99:   7.152 ms/op
                 listUser·p0.999:  13.648 ms/op
                 listUser·p0.9999: 16.532 ms/op
                 listUser·p1.00:   16.581 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 235847
  mean =      4.069 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 72 
    [ 2.500,  5.000) = 227708 
    [ 5.000,  7.500) = 6156 
    [ 7.500, 10.000) = 954 
    [10.000, 12.500) = 376 
    [12.500, 15.000) = 345 
    [15.000, 17.500) = 130 
    [17.500, 20.000) = 47 
    [20.000, 22.500) = 52 
    [22.500, 25.000) = 7 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.278 ms/op
     p(50.0000) =      3.932 ms/op
     p(90.0000) =      4.473 ms/op
     p(95.0000) =      4.719 ms/op
     p(99.0000) =      7.062 ms/op
     p(99.9000) =     15.008 ms/op
     p(99.9900) =     21.234 ms/op
     p(99.9990) =     23.274 ms/op
     p(99.9999) =     23.495 ms/op
    p(100.0000) =     23.495 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.393 ± 1.312  ops/ms
ClientPb.existUser                       thrpt       3   9.906 ± 0.928  ops/ms
ClientPb.getUser                         thrpt       3   9.493 ± 1.399  ops/ms
ClientPb.listUser                        thrpt       3   7.958 ± 3.455  ops/ms
ClientPb.createUser                       avgt       3   3.392 ± 0.151   ms/op
ClientPb.existUser                        avgt       3   3.305 ± 1.206   ms/op
ClientPb.getUser                          avgt       3   3.432 ± 0.915   ms/op
ClientPb.listUser                         avgt       3   3.998 ± 0.545   ms/op
ClientPb.createUser                     sample  285228   3.363 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.990           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.285           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.752           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.006           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.472           ms/op
ClientPb.createUser:createUser·p0.999   sample          17.392           ms/op
ClientPb.createUser:createUser·p0.9999  sample          24.740           ms/op
ClientPb.createUser:createUser·p1.00    sample          26.444           ms/op
ClientPb.existUser                      sample  287066   3.343 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.538           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.256           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.723           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.051           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.988           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.826           ms/op
ClientPb.existUser:existUser·p0.9999    sample          22.544           ms/op
ClientPb.existUser:existUser·p1.00      sample          24.576           ms/op
ClientPb.getUser                        sample  282209   3.400 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.069           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.293           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.756           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.998           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.046           ms/op
ClientPb.getUser:getUser·p0.999         sample          16.256           ms/op
ClientPb.getUser:getUser·p0.9999        sample          24.012           ms/op
ClientPb.getUser:getUser·p1.00          sample          25.657           ms/op
ClientPb.listUser                       sample  235847   4.069 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.278           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.932           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.473           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.719           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.062           ms/op
ClientPb.listUser:listUser·p0.999       sample          15.008           ms/op
ClientPb.listUser:listUser·p0.9999      sample          21.234           ms/op
ClientPb.listUser:listUser·p1.00        sample          23.495           ms/op
