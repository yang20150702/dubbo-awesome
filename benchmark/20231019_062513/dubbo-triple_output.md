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
# Warmup Iteration   1: 2.424 ops/ms
# Warmup Iteration   2: 5.230 ops/ms
# Warmup Iteration   3: 9.169 ops/ms
Iteration   1: 9.751 ops/ms
Iteration   2: 9.803 ops/ms
Iteration   3: 9.759 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.771 ±(99.9%) 0.511 ops/ms [Average]
  (min, avg, max) = (9.751, 9.771, 9.803), stdev = 0.028
  CI (99.9%): [9.260, 10.282] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 3.156 ops/ms
# Warmup Iteration   2: 9.244 ops/ms
# Warmup Iteration   3: 9.967 ops/ms
Iteration   1: 10.171 ops/ms
Iteration   2: 10.206 ops/ms
Iteration   3: 10.139 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.172 ±(99.9%) 0.613 ops/ms [Average]
  (min, avg, max) = (10.139, 10.172, 10.206), stdev = 0.034
  CI (99.9%): [9.559, 10.785] (assumes normal distribution)


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
# Warmup Iteration   1: 3.357 ops/ms
# Warmup Iteration   2: 9.113 ops/ms
# Warmup Iteration   3: 9.910 ops/ms
Iteration   1: 9.866 ops/ms
Iteration   2: 10.052 ops/ms
Iteration   3: 10.062 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.994 ±(99.9%) 2.020 ops/ms [Average]
  (min, avg, max) = (9.866, 9.994, 10.062), stdev = 0.111
  CI (99.9%): [7.973, 12.014] (assumes normal distribution)


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
# Warmup Iteration   1: 3.384 ops/ms
# Warmup Iteration   2: 8.062 ops/ms
# Warmup Iteration   3: 8.213 ops/ms
Iteration   1: 8.441 ops/ms
Iteration   2: 8.514 ops/ms
Iteration   3: 8.301 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.419 ±(99.9%) 1.971 ops/ms [Average]
  (min, avg, max) = (8.301, 8.419, 8.514), stdev = 0.108
  CI (99.9%): [6.448, 10.390] (assumes normal distribution)


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
# Warmup Iteration   1: 8.138 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 3.436 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.430 ±(99.9%) 0.002 ms/op
Iteration   1: 3.291 ±(99.9%) 0.003 ms/op
Iteration   2: 3.173 ±(99.9%) 0.004 ms/op
Iteration   3: 3.215 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.226 ±(99.9%) 1.090 ms/op [Average]
  (min, avg, max) = (3.173, 3.226, 3.291), stdev = 0.060
  CI (99.9%): [2.136, 4.316] (assumes normal distribution)


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
# Warmup Iteration   1: 7.175 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 3.341 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.252 ±(99.9%) 0.003 ms/op
Iteration   1: 3.114 ±(99.9%) 0.002 ms/op
Iteration   2: 3.209 ±(99.9%) 0.004 ms/op
Iteration   3: 3.115 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.146 ±(99.9%) 1.000 ms/op [Average]
  (min, avg, max) = (3.114, 3.146, 3.209), stdev = 0.055
  CI (99.9%): [2.146, 4.146] (assumes normal distribution)


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
# Warmup Iteration   1: 9.555 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.477 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.232 ±(99.9%) 0.002 ms/op
Iteration   1: 3.160 ±(99.9%) 0.002 ms/op
Iteration   2: 3.193 ±(99.9%) 0.002 ms/op
Iteration   3: 3.248 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.200 ±(99.9%) 0.805 ms/op [Average]
  (min, avg, max) = (3.160, 3.200, 3.248), stdev = 0.044
  CI (99.9%): [2.395, 4.006] (assumes normal distribution)


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
# Warmup Iteration   1: 9.137 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 4.067 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.855 ±(99.9%) 0.004 ms/op
Iteration   1: 3.813 ±(99.9%) 0.005 ms/op
Iteration   2: 3.736 ±(99.9%) 0.007 ms/op
Iteration   3: 3.761 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.770 ±(99.9%) 0.721 ms/op [Average]
  (min, avg, max) = (3.736, 3.770, 3.813), stdev = 0.040
  CI (99.9%): [3.049, 4.491] (assumes normal distribution)


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
# Warmup Iteration   1: 8.137 ±(99.9%) 0.110 ms/op
# Warmup Iteration   2: 3.578 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.328 ±(99.9%) 0.010 ms/op
Iteration   1: 3.257 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   1.153 ms/op
                 createUser·p0.50:   3.228 ms/op
                 createUser·p0.90:   3.695 ms/op
                 createUser·p0.95:   3.916 ms/op
                 createUser·p0.99:   4.792 ms/op
                 createUser·p0.999:  8.507 ms/op
                 createUser·p0.9999: 22.649 ms/op
                 createUser·p1.00:   23.265 ms/op

Iteration   2: 3.353 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.268 ms/op
                 createUser·p0.50:   3.228 ms/op
                 createUser·p0.90:   3.863 ms/op
                 createUser·p0.95:   4.108 ms/op
                 createUser·p0.99:   5.743 ms/op
                 createUser·p0.999:  19.199 ms/op
                 createUser·p0.9999: 23.852 ms/op
                 createUser·p1.00:   24.281 ms/op

Iteration   3: 3.184 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.186 ms/op
                 createUser·p0.50:   3.105 ms/op
                 createUser·p0.90:   3.510 ms/op
                 createUser·p0.95:   3.727 ms/op
                 createUser·p0.99:   4.694 ms/op
                 createUser·p0.999:  17.221 ms/op
                 createUser·p0.9999: 22.573 ms/op
                 createUser·p1.00:   29.393 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 294074
  mean =      3.263 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13655 
    [ 2.500,  5.000) = 276953 
    [ 5.000,  7.500) = 2643 
    [ 7.500, 10.000) = 234 
    [10.000, 12.500) = 210 
    [12.500, 15.000) = 44 
    [15.000, 17.500) = 54 
    [17.500, 20.000) = 141 
    [20.000, 22.500) = 88 
    [22.500, 25.000) = 51 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.153 ms/op
     p(50.0000) =      3.191 ms/op
     p(90.0000) =      3.703 ms/op
     p(95.0000) =      3.953 ms/op
     p(99.0000) =      5.251 ms/op
     p(99.9000) =     17.168 ms/op
     p(99.9900) =     23.337 ms/op
     p(99.9990) =     24.219 ms/op
     p(99.9999) =     29.393 ms/op
    p(100.0000) =     29.393 ms/op


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
# Warmup Iteration   1: 7.083 ±(99.9%) 0.088 ms/op
# Warmup Iteration   2: 3.318 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.202 ±(99.9%) 0.007 ms/op
Iteration   1: 3.104 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.092 ms/op
                 existUser·p0.50:   3.006 ms/op
                 existUser·p0.90:   3.359 ms/op
                 existUser·p0.95:   3.580 ms/op
                 existUser·p0.99:   5.300 ms/op
                 existUser·p0.999:  17.858 ms/op
                 existUser·p0.9999: 20.677 ms/op
                 existUser·p1.00:   23.265 ms/op

Iteration   2: 3.144 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.873 ms/op
                 existUser·p0.50:   3.088 ms/op
                 existUser·p0.90:   3.437 ms/op
                 existUser·p0.95:   3.613 ms/op
                 existUser·p0.99:   5.128 ms/op
                 existUser·p0.999:  15.990 ms/op
                 existUser·p0.9999: 21.982 ms/op
                 existUser·p1.00:   22.872 ms/op

Iteration   3: 3.146 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.339 ms/op
                 existUser·p0.50:   3.097 ms/op
                 existUser·p0.90:   3.416 ms/op
                 existUser·p0.95:   3.613 ms/op
                 existUser·p0.99:   5.161 ms/op
                 existUser·p0.999:  12.976 ms/op
                 existUser·p0.9999: 23.233 ms/op
                 existUser·p1.00:   23.986 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 306346
  mean =      3.131 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10530 
    [ 2.500,  5.000) = 291957 
    [ 5.000,  7.500) = 3152 
    [ 7.500, 10.000) = 187 
    [10.000, 12.500) = 137 
    [12.500, 15.000) = 66 
    [15.000, 17.500) = 71 
    [17.500, 20.000) = 108 
    [20.000, 22.500) = 114 
    [22.500, 25.000) = 24 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.873 ms/op
     p(50.0000) =      3.060 ms/op
     p(90.0000) =      3.408 ms/op
     p(95.0000) =      3.600 ms/op
     p(99.0000) =      5.251 ms/op
     p(99.9000) =     15.903 ms/op
     p(99.9900) =     22.047 ms/op
     p(99.9990) =     23.790 ms/op
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
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 7.238 ±(99.9%) 0.083 ms/op
# Warmup Iteration   2: 3.341 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.324 ±(99.9%) 0.010 ms/op
Iteration   1: 3.171 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.239 ms/op
                 getUser·p0.50:   3.056 ms/op
                 getUser·p0.90:   3.432 ms/op
                 getUser·p0.95:   3.670 ms/op
                 getUser·p0.99:   5.915 ms/op
                 getUser·p0.999:  17.571 ms/op
                 getUser·p0.9999: 21.388 ms/op
                 getUser·p1.00:   23.495 ms/op

Iteration   2: 3.212 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.243 ms/op
                 getUser·p0.50:   3.133 ms/op
                 getUser·p0.90:   3.588 ms/op
                 getUser·p0.95:   3.768 ms/op
                 getUser·p0.99:   5.063 ms/op
                 getUser·p0.999:  13.903 ms/op
                 getUser·p0.9999: 22.184 ms/op
                 getUser·p1.00:   22.446 ms/op

Iteration   3: 3.315 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.409 ms/op
                 getUser·p0.50:   3.260 ms/op
                 getUser·p0.90:   3.711 ms/op
                 getUser·p0.95:   4.088 ms/op
                 getUser·p0.99:   5.988 ms/op
                 getUser·p0.999:  14.869 ms/op
                 getUser·p0.9999: 16.670 ms/op
                 getUser·p1.00:   17.629 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 296819
  mean =      3.231 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12761 
    [ 2.500,  5.000) = 278764 
    [ 5.000,  7.500) = 4347 
    [ 7.500, 10.000) = 325 
    [10.000, 12.500) = 105 
    [12.500, 15.000) = 199 
    [15.000, 17.500) = 118 
    [17.500, 20.000) = 106 
    [20.000, 22.500) = 91 
    [22.500, 25.000) = 3 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.239 ms/op
     p(50.0000) =      3.142 ms/op
     p(90.0000) =      3.588 ms/op
     p(95.0000) =      3.842 ms/op
     p(99.0000) =      5.726 ms/op
     p(99.9000) =     15.551 ms/op
     p(99.9900) =     21.527 ms/op
     p(99.9990) =     22.541 ms/op
     p(99.9999) =     23.495 ms/op
    p(100.0000) =     23.495 ms/op


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
# Warmup Iteration   1: 9.676 ±(99.9%) 0.123 ms/op
# Warmup Iteration   2: 4.160 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.919 ±(99.9%) 0.011 ms/op
Iteration   1: 3.939 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.323 ms/op
                 listUser·p0.50:   3.842 ms/op
                 listUser·p0.90:   4.293 ms/op
                 listUser·p0.95:   4.530 ms/op
                 listUser·p0.99:   6.914 ms/op
                 listUser·p0.999:  14.516 ms/op
                 listUser·p0.9999: 17.498 ms/op
                 listUser·p1.00:   17.727 ms/op

Iteration   2: 3.827 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.191 ms/op
                 listUser·p0.50:   3.650 ms/op
                 listUser·p0.90:   4.260 ms/op
                 listUser·p0.95:   4.497 ms/op
                 listUser·p0.99:   6.849 ms/op
                 listUser·p0.999:  13.261 ms/op
                 listUser·p0.9999: 15.969 ms/op
                 listUser·p1.00:   16.187 ms/op

Iteration   3: 3.851 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.845 ms/op
                 listUser·p0.50:   3.760 ms/op
                 listUser·p0.90:   4.190 ms/op
                 listUser·p0.95:   4.375 ms/op
                 listUser·p0.99:   6.389 ms/op
                 listUser·p0.999:  15.188 ms/op
                 listUser·p0.9999: 17.271 ms/op
                 listUser·p1.00:   19.857 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 247822
  mean =      3.872 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 0 
    [ 1.250,  2.500) = 71 
    [ 2.500,  3.750) = 123628 
    [ 3.750,  5.000) = 116939 
    [ 5.000,  6.250) = 3070 
    [ 6.250,  7.500) = 2597 
    [ 7.500,  8.750) = 636 
    [ 8.750, 10.000) = 176 
    [10.000, 11.250) = 85 
    [11.250, 12.500) = 137 
    [12.500, 13.750) = 159 
    [13.750, 15.000) = 134 
    [15.000, 16.250) = 97 
    [16.250, 17.500) = 80 
    [17.500, 18.750) = 12 

  Percentiles, ms/op:
      p(0.0000) =      1.323 ms/op
     p(50.0000) =      3.752 ms/op
     p(90.0000) =      4.252 ms/op
     p(95.0000) =      4.473 ms/op
     p(99.0000) =      6.799 ms/op
     p(99.9000) =     14.467 ms/op
     p(99.9900) =     17.152 ms/op
     p(99.9990) =     18.175 ms/op
     p(99.9999) =     19.857 ms/op
    p(100.0000) =     19.857 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.771 ± 0.511  ops/ms
ClientPb.existUser                       thrpt       3  10.172 ± 0.613  ops/ms
ClientPb.getUser                         thrpt       3   9.994 ± 2.020  ops/ms
ClientPb.listUser                        thrpt       3   8.419 ± 1.971  ops/ms
ClientPb.createUser                       avgt       3   3.226 ± 1.090   ms/op
ClientPb.existUser                        avgt       3   3.146 ± 1.000   ms/op
ClientPb.getUser                          avgt       3   3.200 ± 0.805   ms/op
ClientPb.listUser                         avgt       3   3.770 ± 0.721   ms/op
ClientPb.createUser                     sample  294074   3.263 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.153           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.191           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.703           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.953           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.251           ms/op
ClientPb.createUser:createUser·p0.999   sample          17.168           ms/op
ClientPb.createUser:createUser·p0.9999  sample          23.337           ms/op
ClientPb.createUser:createUser·p1.00    sample          29.393           ms/op
ClientPb.existUser                      sample  306346   3.131 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.873           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.060           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.408           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.600           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.251           ms/op
ClientPb.existUser:existUser·p0.999     sample          15.903           ms/op
ClientPb.existUser:existUser·p0.9999    sample          22.047           ms/op
ClientPb.existUser:existUser·p1.00      sample          23.986           ms/op
ClientPb.getUser                        sample  296819   3.231 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.239           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.142           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.588           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.842           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.726           ms/op
ClientPb.getUser:getUser·p0.999         sample          15.551           ms/op
ClientPb.getUser:getUser·p0.9999        sample          21.527           ms/op
ClientPb.getUser:getUser·p1.00          sample          23.495           ms/op
ClientPb.listUser                       sample  247822   3.872 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.323           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.752           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.252           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.473           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.799           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.467           ms/op
ClientPb.listUser:listUser·p0.9999      sample          17.152           ms/op
ClientPb.listUser:listUser·p1.00        sample          19.857           ms/op
