# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 4.392 ops/ms
# Warmup Iteration   2: 11.538 ops/ms
# Warmup Iteration   3: 12.055 ops/ms
Iteration   1: 12.178 ops/ms
Iteration   2: 12.280 ops/ms
Iteration   3: 12.315 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.258 ±(99.9%) 1.307 ops/ms [Average]
  (min, avg, max) = (12.178, 12.258, 12.315), stdev = 0.072
  CI (99.9%): [10.951, 13.565] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:11:52
# Fork: 1 of 1
# Warmup Iteration   1: 8.247 ops/ms
# Warmup Iteration   2: 12.707 ops/ms
# Warmup Iteration   3: 12.726 ops/ms
Iteration   1: 12.619 ops/ms
Iteration   2: 12.718 ops/ms
Iteration   3: 12.871 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.736 ±(99.9%) 2.322 ops/ms [Average]
  (min, avg, max) = (12.619, 12.736, 12.871), stdev = 0.127
  CI (99.9%): [10.414, 15.058] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:47
# Fork: 1 of 1
# Warmup Iteration   1: 7.544 ops/ms
# Warmup Iteration   2: 12.196 ops/ms
# Warmup Iteration   3: 12.376 ops/ms
Iteration   1: 12.269 ops/ms
Iteration   2: 12.412 ops/ms
Iteration   3: 12.449 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.377 ±(99.9%) 1.736 ops/ms [Average]
  (min, avg, max) = (12.269, 12.377, 12.449), stdev = 0.095
  CI (99.9%): [10.641, 14.113] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:42
# Fork: 1 of 1
# Warmup Iteration   1: 6.755 ops/ms
# Warmup Iteration   2: 10.291 ops/ms
# Warmup Iteration   3: 10.353 ops/ms
Iteration   1: 10.286 ops/ms
Iteration   2: 10.427 ops/ms
Iteration   3: 10.486 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.400 ±(99.9%) 1.873 ops/ms [Average]
  (min, avg, max) = (10.286, 10.400, 10.486), stdev = 0.103
  CI (99.9%): [8.527, 12.273] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:37
# Fork: 1 of 1
# Warmup Iteration   1: 4.093 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 2.649 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.590 ±(99.9%) 0.005 ms/op
Iteration   1: 2.562 ±(99.9%) 0.003 ms/op
Iteration   2: 2.634 ±(99.9%) 0.004 ms/op
Iteration   3: 2.560 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.585 ±(99.9%) 0.772 ms/op [Average]
  (min, avg, max) = (2.560, 2.585, 2.634), stdev = 0.042
  CI (99.9%): [1.814, 3.357] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:33
# Fork: 1 of 1
# Warmup Iteration   1: 3.846 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.502 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.517 ±(99.9%) 0.004 ms/op
Iteration   1: 2.486 ±(99.9%) 0.004 ms/op
Iteration   2: 2.506 ±(99.9%) 0.004 ms/op
Iteration   3: 2.525 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.505 ±(99.9%) 0.355 ms/op [Average]
  (min, avg, max) = (2.486, 2.505, 2.525), stdev = 0.019
  CI (99.9%): [2.150, 2.860] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:28
# Fork: 1 of 1
# Warmup Iteration   1: 3.978 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.619 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.566 ±(99.9%) 0.004 ms/op
Iteration   1: 2.567 ±(99.9%) 0.005 ms/op
Iteration   2: 2.577 ±(99.9%) 0.004 ms/op
Iteration   3: 2.536 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.560 ±(99.9%) 0.388 ms/op [Average]
  (min, avg, max) = (2.536, 2.560, 2.577), stdev = 0.021
  CI (99.9%): [2.172, 2.948] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:24
# Fork: 1 of 1
# Warmup Iteration   1: 4.773 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.117 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.068 ±(99.9%) 0.004 ms/op
Iteration   1: 3.050 ±(99.9%) 0.006 ms/op
Iteration   2: 3.058 ±(99.9%) 0.005 ms/op
Iteration   3: 3.040 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.049 ±(99.9%) 0.165 ms/op [Average]
  (min, avg, max) = (3.040, 3.049, 3.058), stdev = 0.009
  CI (99.9%): [2.884, 3.214] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:19
# Fork: 1 of 1
# Warmup Iteration   1: 4.355 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 2.736 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.595 ±(99.9%) 0.006 ms/op
Iteration   1: 2.609 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.982 ms/op
                 createUser·p0.50:   2.662 ms/op
                 createUser·p0.90:   3.170 ms/op
                 createUser·p0.95:   3.310 ms/op
                 createUser·p0.99:   3.990 ms/op
                 createUser·p0.999:  12.141 ms/op
                 createUser·p0.9999: 14.086 ms/op
                 createUser·p1.00:   14.828 ms/op

Iteration   2: 2.659 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   1.005 ms/op
                 createUser·p0.50:   2.724 ms/op
                 createUser·p0.90:   3.228 ms/op
                 createUser·p0.95:   3.371 ms/op
                 createUser·p0.99:   4.227 ms/op
                 createUser·p0.999:  5.980 ms/op
                 createUser·p0.9999: 12.778 ms/op
                 createUser·p1.00:   13.484 ms/op

Iteration   3: 2.658 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.915 ms/op
                 createUser·p0.50:   2.728 ms/op
                 createUser·p0.90:   3.232 ms/op
                 createUser·p0.95:   3.375 ms/op
                 createUser·p0.99:   4.108 ms/op
                 createUser·p0.999:  8.597 ms/op
                 createUser·p0.9999: 12.993 ms/op
                 createUser·p1.00:   14.975 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 362994
  mean =      2.642 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 44 
    [ 1.250,  2.500) = 167193 
    [ 2.500,  3.750) = 189587 
    [ 3.750,  5.000) = 4997 
    [ 5.000,  6.250) = 750 
    [ 6.250,  7.500) = 57 
    [ 7.500,  8.750) = 29 
    [ 8.750, 10.000) = 22 
    [10.000, 11.250) = 58 
    [11.250, 12.500) = 121 
    [12.500, 13.750) = 102 
    [13.750, 15.000) = 34 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.915 ms/op
     p(50.0000) =      2.703 ms/op
     p(90.0000) =      3.211 ms/op
     p(95.0000) =      3.355 ms/op
     p(99.0000) =      4.104 ms/op
     p(99.9000) =      7.955 ms/op
     p(99.9900) =     13.676 ms/op
     p(99.9990) =     14.202 ms/op
     p(99.9999) =     14.975 ms/op
    p(100.0000) =     14.975 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.947 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 2.595 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.581 ±(99.9%) 0.006 ms/op
Iteration   1: 2.601 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.859 ms/op
                 existUser·p0.50:   2.654 ms/op
                 existUser·p0.90:   3.158 ms/op
                 existUser·p0.95:   3.334 ms/op
                 existUser·p0.99:   4.454 ms/op
                 existUser·p0.999:  7.586 ms/op
                 existUser·p0.9999: 15.206 ms/op
                 existUser·p1.00:   15.974 ms/op

Iteration   2: 2.580 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.949 ms/op
                 existUser·p0.50:   2.609 ms/op
                 existUser·p0.90:   3.146 ms/op
                 existUser·p0.95:   3.273 ms/op
                 existUser·p0.99:   3.891 ms/op
                 existUser·p0.999:  10.781 ms/op
                 existUser·p0.9999: 15.820 ms/op
                 existUser·p1.00:   16.040 ms/op

Iteration   3: 2.583 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.094 ms/op
                 existUser·p0.50:   2.626 ms/op
                 existUser·p0.90:   3.146 ms/op
                 existUser·p0.95:   3.269 ms/op
                 existUser·p0.99:   4.076 ms/op
                 existUser·p0.999:  9.048 ms/op
                 existUser·p0.9999: 12.323 ms/op
                 existUser·p1.00:   12.616 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 370632
  mean =      2.588 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 38 
    [ 1.250,  2.500) = 176497 
    [ 2.500,  3.750) = 187847 
    [ 3.750,  5.000) = 4657 
    [ 5.000,  6.250) = 977 
    [ 6.250,  7.500) = 185 
    [ 7.500,  8.750) = 74 
    [ 8.750, 10.000) = 60 
    [10.000, 11.250) = 55 
    [11.250, 12.500) = 44 
    [12.500, 13.750) = 96 
    [13.750, 15.000) = 48 
    [15.000, 16.250) = 54 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.859 ms/op
     p(50.0000) =      2.634 ms/op
     p(90.0000) =      3.150 ms/op
     p(95.0000) =      3.289 ms/op
     p(99.0000) =      4.170 ms/op
     p(99.9000) =      8.454 ms/op
     p(99.9900) =     15.348 ms/op
     p(99.9990) =     15.951 ms/op
     p(99.9999) =     16.040 ms/op
    p(100.0000) =     16.040 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:09
# Fork: 1 of 1
# Warmup Iteration   1: 4.405 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 2.705 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.641 ±(99.9%) 0.006 ms/op
Iteration   1: 2.633 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.835 ms/op
                 getUser·p0.50:   2.654 ms/op
                 getUser·p0.90:   3.203 ms/op
                 getUser·p0.95:   3.318 ms/op
                 getUser·p0.99:   3.891 ms/op
                 getUser·p0.999:  5.790 ms/op
                 getUser·p0.9999: 14.697 ms/op
                 getUser·p1.00:   15.401 ms/op

Iteration   2: 2.643 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   1.155 ms/op
                 getUser·p0.50:   2.658 ms/op
                 getUser·p0.90:   3.219 ms/op
                 getUser·p0.95:   3.351 ms/op
                 getUser·p0.99:   4.071 ms/op
                 getUser·p0.999:  10.241 ms/op
                 getUser·p0.9999: 14.253 ms/op
                 getUser·p1.00:   14.615 ms/op

Iteration   3: 2.670 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.983 ms/op
                 getUser·p0.50:   2.691 ms/op
                 getUser·p0.90:   3.236 ms/op
                 getUser·p0.95:   3.416 ms/op
                 getUser·p0.99:   4.858 ms/op
                 getUser·p0.999:  9.458 ms/op
                 getUser·p0.9999: 33.949 ms/op
                 getUser·p1.00:   37.618 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 362078
  mean =      2.649 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 170484 
    [ 2.500,  5.000) = 189767 
    [ 5.000,  7.500) = 1436 
    [ 7.500, 10.000) = 86 
    [10.000, 12.500) = 105 
    [12.500, 15.000) = 161 
    [15.000, 17.500) = 7 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 3 
    [32.500, 35.000) = 22 
    [35.000, 37.500) = 6 

  Percentiles, ms/op:
      p(0.0000) =      0.835 ms/op
     p(50.0000) =      2.671 ms/op
     p(90.0000) =      3.219 ms/op
     p(95.0000) =      3.359 ms/op
     p(99.0000) =      4.227 ms/op
     p(99.9000) =      8.711 ms/op
     p(99.9900) =     15.119 ms/op
     p(99.9990) =     37.290 ms/op
     p(99.9999) =     37.618 ms/op
    p(100.0000) =     37.618 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:04
# Fork: 1 of 1
# Warmup Iteration   1: 5.088 ±(99.9%) 0.059 ms/op
# Warmup Iteration   2: 3.159 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.164 ±(99.9%) 0.009 ms/op
Iteration   1: 3.113 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.958 ms/op
                 listUser·p0.50:   3.043 ms/op
                 listUser·p0.90:   4.030 ms/op
                 listUser·p0.95:   4.522 ms/op
                 listUser·p0.99:   5.669 ms/op
                 listUser·p0.999:  9.945 ms/op
                 listUser·p0.9999: 12.009 ms/op
                 listUser·p1.00:   12.337 ms/op

Iteration   2: 3.101 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.031 ms/op
                 listUser·p0.50:   3.035 ms/op
                 listUser·p0.90:   4.026 ms/op
                 listUser·p0.95:   4.530 ms/op
                 listUser·p0.99:   5.726 ms/op
                 listUser·p0.999:  10.730 ms/op
                 listUser·p0.9999: 16.800 ms/op
                 listUser·p1.00:   17.367 ms/op

Iteration   3: 3.111 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   0.837 ms/op
                 listUser·p0.50:   3.035 ms/op
                 listUser·p0.90:   4.035 ms/op
                 listUser·p0.95:   4.547 ms/op
                 listUser·p0.99:   5.865 ms/op
                 listUser·p0.999:  9.847 ms/op
                 listUser·p0.9999: 11.128 ms/op
                 listUser·p1.00:   12.468 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 308547
  mean =      3.108 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 86 
    [ 1.250,  2.500) = 74836 
    [ 2.500,  3.750) = 186733 
    [ 3.750,  5.000) = 38463 
    [ 5.000,  6.250) = 6845 
    [ 6.250,  7.500) = 878 
    [ 7.500,  8.750) = 162 
    [ 8.750, 10.000) = 239 
    [10.000, 11.250) = 203 
    [11.250, 12.500) = 70 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 16 
    [16.250, 17.500) = 16 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.837 ms/op
     p(50.0000) =      3.039 ms/op
     p(90.0000) =      4.030 ms/op
     p(95.0000) =      4.530 ms/op
     p(99.0000) =      5.743 ms/op
     p(99.9000) =      9.985 ms/op
     p(99.9900) =     15.526 ms/op
     p(99.9990) =     17.135 ms/op
     p(99.9999) =     17.367 ms/op
    p(100.0000) =     17.367 ms/op


# Run complete. Total time: 00:12:58

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.258 ± 1.307  ops/ms
ClientPb.existUser                       thrpt       3  12.736 ± 2.322  ops/ms
ClientPb.getUser                         thrpt       3  12.377 ± 1.736  ops/ms
ClientPb.listUser                        thrpt       3  10.400 ± 1.873  ops/ms
ClientPb.createUser                       avgt       3   2.585 ± 0.772   ms/op
ClientPb.existUser                        avgt       3   2.505 ± 0.355   ms/op
ClientPb.getUser                          avgt       3   2.560 ± 0.388   ms/op
ClientPb.listUser                         avgt       3   3.049 ± 0.165   ms/op
ClientPb.createUser                     sample  362994   2.642 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.915           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.703           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.211           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.355           ms/op
ClientPb.createUser:createUser·p0.99    sample           4.104           ms/op
ClientPb.createUser:createUser·p0.999   sample           7.955           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.676           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.975           ms/op
ClientPb.existUser                      sample  370632   2.588 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.859           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.634           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.150           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.289           ms/op
ClientPb.existUser:existUser·p0.99      sample           4.170           ms/op
ClientPb.existUser:existUser·p0.999     sample           8.454           ms/op
ClientPb.existUser:existUser·p0.9999    sample          15.348           ms/op
ClientPb.existUser:existUser·p1.00      sample          16.040           ms/op
ClientPb.getUser                        sample  362078   2.649 ± 0.004   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.835           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.671           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.219           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.359           ms/op
ClientPb.getUser:getUser·p0.99          sample           4.227           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.711           ms/op
ClientPb.getUser:getUser·p0.9999        sample          15.119           ms/op
ClientPb.getUser:getUser·p1.00          sample          37.618           ms/op
ClientPb.listUser                       sample  308547   3.108 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.837           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.039           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.030           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.530           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.743           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.985           ms/op
ClientPb.listUser:listUser·p0.9999      sample          15.526           ms/op
ClientPb.listUser:listUser·p1.00        sample          17.367           ms/op
