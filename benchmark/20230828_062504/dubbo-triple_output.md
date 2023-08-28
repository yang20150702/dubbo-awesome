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
# Warmup Iteration   1: 1.489 ops/ms
# Warmup Iteration   2: 3.340 ops/ms
# Warmup Iteration   3: 6.678 ops/ms
Iteration   1: 6.881 ops/ms
Iteration   2: 7.545 ops/ms
Iteration   3: 7.619 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.349 ±(99.9%) 7.411 ops/ms [Average]
  (min, avg, max) = (6.881, 7.349, 7.619), stdev = 0.406
  CI (99.9%): [≈ 0, 14.759] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:03
# Fork: 1 of 1
# Warmup Iteration   1: 1.825 ops/ms
# Warmup Iteration   2: 5.734 ops/ms
# Warmup Iteration   3: 7.948 ops/ms
Iteration   1: 7.772 ops/ms
Iteration   2: 7.705 ops/ms
Iteration   3: 8.160 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  7.879 ±(99.9%) 4.480 ops/ms [Average]
  (min, avg, max) = (7.705, 7.879, 8.160), stdev = 0.246
  CI (99.9%): [3.399, 12.359] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:57
# Fork: 1 of 1
# Warmup Iteration   1: 2.017 ops/ms
# Warmup Iteration   2: 5.552 ops/ms
# Warmup Iteration   3: 7.282 ops/ms
Iteration   1: 7.371 ops/ms
Iteration   2: 7.560 ops/ms
Iteration   3: 7.423 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  7.451 ±(99.9%) 1.780 ops/ms [Average]
  (min, avg, max) = (7.371, 7.451, 7.560), stdev = 0.098
  CI (99.9%): [5.671, 9.231] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:54
# Fork: 1 of 1
# Warmup Iteration   1: 1.871 ops/ms
# Warmup Iteration   2: 5.116 ops/ms
# Warmup Iteration   3: 6.282 ops/ms
Iteration   1: 6.575 ops/ms
Iteration   2: 6.712 ops/ms
Iteration   3: 6.452 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.580 ±(99.9%) 2.369 ops/ms [Average]
  (min, avg, max) = (6.452, 6.580, 6.712), stdev = 0.130
  CI (99.9%): [4.210, 8.949] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:49
# Fork: 1 of 1
# Warmup Iteration   1: 14.956 ±(99.9%) 0.066 ms/op
# Warmup Iteration   2: 5.454 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 4.492 ±(99.9%) 0.008 ms/op
Iteration   1: 4.189 ±(99.9%) 0.007 ms/op
Iteration   2: 4.172 ±(99.9%) 0.007 ms/op
Iteration   3: 4.071 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  4.144 ±(99.9%) 1.160 ms/op [Average]
  (min, avg, max) = (4.071, 4.144, 4.189), stdev = 0.064
  CI (99.9%): [2.984, 5.304] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:43
# Fork: 1 of 1
# Warmup Iteration   1: 13.613 ±(99.9%) 0.064 ms/op
# Warmup Iteration   2: 5.165 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.308 ±(99.9%) 0.006 ms/op
Iteration   1: 4.245 ±(99.9%) 0.006 ms/op
Iteration   2: 4.143 ±(99.9%) 0.006 ms/op
Iteration   3: 4.285 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  4.224 ±(99.9%) 1.336 ms/op [Average]
  (min, avg, max) = (4.143, 4.224, 4.285), stdev = 0.073
  CI (99.9%): [2.889, 5.560] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:36
# Fork: 1 of 1
# Warmup Iteration   1: 13.487 ±(99.9%) 0.058 ms/op
# Warmup Iteration   2: 5.207 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.266 ±(99.9%) 0.005 ms/op
Iteration   1: 4.317 ±(99.9%) 0.005 ms/op
Iteration   2: 4.073 ±(99.9%) 0.006 ms/op
Iteration   3: 3.963 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  4.118 ±(99.9%) 3.298 ms/op [Average]
  (min, avg, max) = (3.963, 4.118, 4.317), stdev = 0.181
  CI (99.9%): [0.820, 7.415] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:30
# Fork: 1 of 1
# Warmup Iteration   1: 14.415 ±(99.9%) 0.058 ms/op
# Warmup Iteration   2: 5.769 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 5.011 ±(99.9%) 0.012 ms/op
Iteration   1: 4.943 ±(99.9%) 0.010 ms/op
Iteration   2: 4.960 ±(99.9%) 0.006 ms/op
Iteration   3: 4.782 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.895 ±(99.9%) 1.792 ms/op [Average]
  (min, avg, max) = (4.782, 4.895, 4.960), stdev = 0.098
  CI (99.9%): [3.103, 6.687] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:24
# Fork: 1 of 1
# Warmup Iteration   1: 14.177 ±(99.9%) 0.202 ms/op
# Warmup Iteration   2: 4.867 ±(99.9%) 0.025 ms/op
# Warmup Iteration   3: 4.643 ±(99.9%) 0.022 ms/op
Iteration   1: 4.394 ±(99.9%) 0.016 ms/op
                 createUser·p0.00:   1.946 ms/op
                 createUser·p0.50:   4.092 ms/op
                 createUser·p0.90:   5.325 ms/op
                 createUser·p0.95:   6.397 ms/op
                 createUser·p0.99:   9.437 ms/op
                 createUser·p0.999:  18.389 ms/op
                 createUser·p0.9999: 28.504 ms/op
                 createUser·p1.00:   29.426 ms/op

Iteration   2: 4.285 ±(99.9%) 0.017 ms/op
                 createUser·p0.00:   1.745 ms/op
                 createUser·p0.50:   3.916 ms/op
                 createUser·p0.90:   5.235 ms/op
                 createUser·p0.95:   6.513 ms/op
                 createUser·p0.99:   9.010 ms/op
                 createUser·p0.999:  26.214 ms/op
                 createUser·p0.9999: 29.164 ms/op
                 createUser·p1.00:   30.179 ms/op

Iteration   3: 4.213 ±(99.9%) 0.016 ms/op
                 createUser·p0.00:   1.999 ms/op
                 createUser·p0.50:   3.965 ms/op
                 createUser·p0.90:   4.989 ms/op
                 createUser·p0.95:   6.154 ms/op
                 createUser·p0.99:   9.634 ms/op
                 createUser·p0.999:  18.487 ms/op
                 createUser·p0.9999: 31.229 ms/op
                 createUser·p1.00:   32.276 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 223421
  mean =      4.296 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 147 
    [ 2.500,  5.000) = 196386 
    [ 5.000,  7.500) = 21925 
    [ 7.500, 10.000) = 3154 
    [10.000, 12.500) = 1021 
    [12.500, 15.000) = 469 
    [15.000, 17.500) = 50 
    [17.500, 20.000) = 38 
    [20.000, 22.500) = 5 
    [22.500, 25.000) = 19 
    [25.000, 27.500) = 101 
    [27.500, 30.000) = 80 
    [30.000, 32.500) = 26 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.745 ms/op
     p(50.0000) =      3.998 ms/op
     p(90.0000) =      5.202 ms/op
     p(95.0000) =      6.332 ms/op
     p(99.0000) =      9.339 ms/op
     p(99.9000) =     24.141 ms/op
     p(99.9900) =     30.309 ms/op
     p(99.9990) =     32.211 ms/op
     p(99.9999) =     32.276 ms/op
    p(100.0000) =     32.276 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 13.593 ±(99.9%) 0.224 ms/op
# Warmup Iteration   2: 4.742 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 4.387 ±(99.9%) 0.016 ms/op
Iteration   1: 4.198 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   1.462 ms/op
                 existUser·p0.50:   3.908 ms/op
                 existUser·p0.90:   5.054 ms/op
                 existUser·p0.95:   6.193 ms/op
                 existUser·p0.99:   9.929 ms/op
                 existUser·p0.999:  20.442 ms/op
                 existUser·p0.9999: 36.135 ms/op
                 existUser·p1.00:   39.256 ms/op

Iteration   2: 4.141 ±(99.9%) 0.015 ms/op
                 existUser·p0.00:   1.849 ms/op
                 existUser·p0.50:   3.887 ms/op
                 existUser·p0.90:   5.030 ms/op
                 existUser·p0.95:   6.267 ms/op
                 existUser·p0.99:   8.389 ms/op
                 existUser·p0.999:  16.007 ms/op
                 existUser·p0.9999: 31.341 ms/op
                 existUser·p1.00:   32.145 ms/op

Iteration   3: 4.279 ±(99.9%) 0.019 ms/op
                 existUser·p0.00:   1.657 ms/op
                 existUser·p0.50:   3.936 ms/op
                 existUser·p0.90:   5.267 ms/op
                 existUser·p0.95:   6.423 ms/op
                 existUser·p0.99:   10.037 ms/op
                 existUser·p0.999:  31.540 ms/op
                 existUser·p0.9999: 35.389 ms/op
                 existUser·p1.00:   36.307 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 228243
  mean =      4.205 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 274 
    [ 2.500,  5.000) = 202749 
    [ 5.000,  7.500) = 20029 
    [ 7.500, 10.000) = 3394 
    [10.000, 12.500) = 1234 
    [12.500, 15.000) = 219 
    [15.000, 17.500) = 82 
    [17.500, 20.000) = 16 
    [20.000, 22.500) = 22 
    [22.500, 25.000) = 23 
    [25.000, 27.500) = 9 
    [27.500, 30.000) = 47 
    [30.000, 32.500) = 67 
    [32.500, 35.000) = 40 
    [35.000, 37.500) = 36 

  Percentiles, ms/op:
      p(0.0000) =      1.462 ms/op
     p(50.0000) =      3.908 ms/op
     p(90.0000) =      5.128 ms/op
     p(95.0000) =      6.308 ms/op
     p(99.0000) =      9.388 ms/op
     p(99.9000) =     21.570 ms/op
     p(99.9900) =     35.729 ms/op
     p(99.9990) =     38.682 ms/op
     p(99.9999) =     39.256 ms/op
    p(100.0000) =     39.256 ms/op


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
# Warmup Iteration   1: 14.138 ±(99.9%) 0.207 ms/op
# Warmup Iteration   2: 4.923 ±(99.9%) 0.025 ms/op
# Warmup Iteration   3: 4.576 ±(99.9%) 0.021 ms/op
Iteration   1: 4.362 ±(99.9%) 0.016 ms/op
                 getUser·p0.00:   2.159 ms/op
                 getUser·p0.50:   4.063 ms/op
                 getUser·p0.90:   5.366 ms/op
                 getUser·p0.95:   6.726 ms/op
                 getUser·p0.99:   9.198 ms/op
                 getUser·p0.999:  18.416 ms/op
                 getUser·p0.9999: 24.707 ms/op
                 getUser·p1.00:   25.756 ms/op

Iteration   2: 4.411 ±(99.9%) 0.017 ms/op
                 getUser·p0.00:   2.159 ms/op
                 getUser·p0.50:   4.055 ms/op
                 getUser·p0.90:   5.497 ms/op
                 getUser·p0.95:   6.873 ms/op
                 getUser·p0.99:   9.880 ms/op
                 getUser·p0.999:  19.303 ms/op
                 getUser·p0.9999: 30.343 ms/op
                 getUser·p1.00:   30.441 ms/op

Iteration   3: 4.392 ±(99.9%) 0.016 ms/op
                 getUser·p0.00:   1.466 ms/op
                 getUser·p0.50:   4.096 ms/op
                 getUser·p0.90:   5.390 ms/op
                 getUser·p0.95:   6.636 ms/op
                 getUser·p0.99:   9.176 ms/op
                 getUser·p0.999:  13.209 ms/op
                 getUser·p0.9999: 28.794 ms/op
                 getUser·p1.00:   29.327 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 218588
  mean =      4.388 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 51 
    [ 2.500,  5.000) = 187959 
    [ 5.000,  7.500) = 23533 
    [ 7.500, 10.000) = 5444 
    [10.000, 12.500) = 1142 
    [12.500, 15.000) = 205 
    [15.000, 17.500) = 24 
    [17.500, 20.000) = 38 
    [20.000, 22.500) = 10 
    [22.500, 25.000) = 78 
    [25.000, 27.500) = 37 
    [27.500, 30.000) = 58 
    [30.000, 32.500) = 9 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.466 ms/op
     p(50.0000) =      4.071 ms/op
     p(90.0000) =      5.415 ms/op
     p(95.0000) =      6.734 ms/op
     p(99.0000) =      9.454 ms/op
     p(99.9000) =     18.364 ms/op
     p(99.9900) =     28.934 ms/op
     p(99.9990) =     30.435 ms/op
     p(99.9999) =     30.441 ms/op
    p(100.0000) =     30.441 ms/op


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
# Warmup Iteration   1: 16.047 ±(99.9%) 0.251 ms/op
# Warmup Iteration   2: 6.104 ±(99.9%) 0.037 ms/op
# Warmup Iteration   3: 5.296 ±(99.9%) 0.023 ms/op
Iteration   1: 4.857 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   1.593 ms/op
                 listUser·p0.50:   4.637 ms/op
                 listUser·p0.90:   5.259 ms/op
                 listUser·p0.95:   6.054 ms/op
                 listUser·p0.99:   9.372 ms/op
                 listUser·p0.999:  26.345 ms/op
                 listUser·p0.9999: 28.672 ms/op
                 listUser·p1.00:   29.196 ms/op

Iteration   2: 4.853 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   1.186 ms/op
                 listUser·p0.50:   4.604 ms/op
                 listUser·p0.90:   5.521 ms/op
                 listUser·p0.95:   6.447 ms/op
                 listUser·p0.99:   9.681 ms/op
                 listUser·p0.999:  22.747 ms/op
                 listUser·p0.9999: 27.026 ms/op
                 listUser·p1.00:   27.820 ms/op

Iteration   3: 4.799 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   2.798 ms/op
                 listUser·p0.50:   4.547 ms/op
                 listUser·p0.90:   5.308 ms/op
                 listUser·p0.95:   6.373 ms/op
                 listUser·p0.99:   9.830 ms/op
                 listUser·p0.999:  16.898 ms/op
                 listUser·p0.9999: 19.694 ms/op
                 listUser·p1.00:   20.021 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 198373
  mean =      4.836 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12 
    [ 2.500,  5.000) = 159807 
    [ 5.000,  7.500) = 32004 
    [ 7.500, 10.000) = 4775 
    [10.000, 12.500) = 1054 
    [12.500, 15.000) = 263 
    [15.000, 17.500) = 85 
    [17.500, 20.000) = 79 
    [20.000, 22.500) = 63 
    [22.500, 25.000) = 96 
    [25.000, 27.500) = 106 

  Percentiles, ms/op:
      p(0.0000) =      1.186 ms/op
     p(50.0000) =      4.596 ms/op
     p(90.0000) =      5.341 ms/op
     p(95.0000) =      6.324 ms/op
     p(99.0000) =      9.601 ms/op
     p(99.9000) =     23.372 ms/op
     p(99.9900) =     27.891 ms/op
     p(99.9990) =     28.938 ms/op
     p(99.9999) =     29.196 ms/op
    p(100.0000) =     29.196 ms/op


# Run complete. Total time: 00:13:14

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   7.349 ± 7.411  ops/ms
ClientPb.existUser                       thrpt       3   7.879 ± 4.480  ops/ms
ClientPb.getUser                         thrpt       3   7.451 ± 1.780  ops/ms
ClientPb.listUser                        thrpt       3   6.580 ± 2.369  ops/ms
ClientPb.createUser                       avgt       3   4.144 ± 1.160   ms/op
ClientPb.existUser                        avgt       3   4.224 ± 1.336   ms/op
ClientPb.getUser                          avgt       3   4.118 ± 3.298   ms/op
ClientPb.listUser                         avgt       3   4.895 ± 1.792   ms/op
ClientPb.createUser                     sample  223421   4.296 ± 0.009   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.745           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.998           ms/op
ClientPb.createUser:createUser·p0.90    sample           5.202           ms/op
ClientPb.createUser:createUser·p0.95    sample           6.332           ms/op
ClientPb.createUser:createUser·p0.99    sample           9.339           ms/op
ClientPb.createUser:createUser·p0.999   sample          24.141           ms/op
ClientPb.createUser:createUser·p0.9999  sample          30.309           ms/op
ClientPb.createUser:createUser·p1.00    sample          32.276           ms/op
ClientPb.existUser                      sample  228243   4.205 ± 0.010   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.462           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.908           ms/op
ClientPb.existUser:existUser·p0.90      sample           5.128           ms/op
ClientPb.existUser:existUser·p0.95      sample           6.308           ms/op
ClientPb.existUser:existUser·p0.99      sample           9.388           ms/op
ClientPb.existUser:existUser·p0.999     sample          21.570           ms/op
ClientPb.existUser:existUser·p0.9999    sample          35.729           ms/op
ClientPb.existUser:existUser·p1.00      sample          39.256           ms/op
ClientPb.getUser                        sample  218588   4.388 ± 0.009   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.466           ms/op
ClientPb.getUser:getUser·p0.50          sample           4.071           ms/op
ClientPb.getUser:getUser·p0.90          sample           5.415           ms/op
ClientPb.getUser:getUser·p0.95          sample           6.734           ms/op
ClientPb.getUser:getUser·p0.99          sample           9.454           ms/op
ClientPb.getUser:getUser·p0.999         sample          18.364           ms/op
ClientPb.getUser:getUser·p0.9999        sample          28.934           ms/op
ClientPb.getUser:getUser·p1.00          sample          30.441           ms/op
ClientPb.listUser                       sample  198373   4.836 ± 0.009   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.186           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.596           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.341           ms/op
ClientPb.listUser:listUser·p0.95        sample           6.324           ms/op
ClientPb.listUser:listUser·p0.99        sample           9.601           ms/op
ClientPb.listUser:listUser·p0.999       sample          23.372           ms/op
ClientPb.listUser:listUser·p0.9999      sample          27.891           ms/op
ClientPb.listUser:listUser·p1.00        sample          29.196           ms/op
