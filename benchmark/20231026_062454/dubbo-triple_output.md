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
# Warmup Iteration   1: 1.073 ops/ms
# Warmup Iteration   2: 2.184 ops/ms
# Warmup Iteration   3: 4.677 ops/ms
Iteration   1: 5.110 ops/ms
Iteration   2: 5.269 ops/ms
Iteration   3: 5.426 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.268 ±(99.9%) 2.888 ops/ms [Average]
  (min, avg, max) = (5.110, 5.268, 5.426), stdev = 0.158
  CI (99.9%): [2.380, 8.157] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:10
# Fork: 1 of 1
# Warmup Iteration   1: 1.473 ops/ms
# Warmup Iteration   2: 4.526 ops/ms
# Warmup Iteration   3: 5.606 ops/ms
Iteration   1: 5.602 ops/ms
Iteration   2: 5.641 ops/ms
Iteration   3: 5.762 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.668 ±(99.9%) 1.522 ops/ms [Average]
  (min, avg, max) = (5.602, 5.668, 5.762), stdev = 0.083
  CI (99.9%): [4.146, 7.190] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:06
# Fork: 1 of 1
# Warmup Iteration   1: 1.508 ops/ms
# Warmup Iteration   2: 4.248 ops/ms
# Warmup Iteration   3: 5.226 ops/ms
Iteration   1: 5.310 ops/ms
Iteration   2: 5.480 ops/ms
Iteration   3: 5.585 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.458 ±(99.9%) 2.529 ops/ms [Average]
  (min, avg, max) = (5.310, 5.458, 5.585), stdev = 0.139
  CI (99.9%): [2.929, 7.988] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:10:00
# Fork: 1 of 1
# Warmup Iteration   1: 1.435 ops/ms
# Warmup Iteration   2: 3.533 ops/ms
# Warmup Iteration   3: 4.513 ops/ms
Iteration   1: 4.397 ops/ms
Iteration   2: 4.396 ops/ms
Iteration   3: 4.535 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.443 ±(99.9%) 1.457 ops/ms [Average]
  (min, avg, max) = (4.396, 4.443, 4.535), stdev = 0.080
  CI (99.9%): [2.986, 5.899] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:52
# Fork: 1 of 1
# Warmup Iteration   1: 20.251 ±(99.9%) 0.164 ms/op
# Warmup Iteration   2: 7.414 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 5.996 ±(99.9%) 0.009 ms/op
Iteration   1: 6.051 ±(99.9%) 0.009 ms/op
Iteration   2: 5.983 ±(99.9%) 0.008 ms/op
Iteration   3: 5.846 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.960 ±(99.9%) 1.905 ms/op [Average]
  (min, avg, max) = (5.846, 5.960, 6.051), stdev = 0.104
  CI (99.9%): [4.055, 7.865] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:44
# Fork: 1 of 1
# Warmup Iteration   1: 19.919 ±(99.9%) 0.125 ms/op
# Warmup Iteration   2: 6.968 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 5.737 ±(99.9%) 0.008 ms/op
Iteration   1: 5.925 ±(99.9%) 0.007 ms/op
Iteration   2: 5.597 ±(99.9%) 0.015 ms/op
Iteration   3: 5.691 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.738 ±(99.9%) 3.082 ms/op [Average]
  (min, avg, max) = (5.597, 5.738, 5.925), stdev = 0.169
  CI (99.9%): [2.656, 8.819] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:39
# Fork: 1 of 1
# Warmup Iteration   1: 18.476 ±(99.9%) 0.083 ms/op
# Warmup Iteration   2: 7.222 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 5.956 ±(99.9%) 0.012 ms/op
Iteration   1: 6.113 ±(99.9%) 0.014 ms/op
Iteration   2: 6.079 ±(99.9%) 0.010 ms/op
Iteration   3: 6.080 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  6.091 ±(99.9%) 0.347 ms/op [Average]
  (min, avg, max) = (6.079, 6.091, 6.113), stdev = 0.019
  CI (99.9%): [5.744, 6.438] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:32
# Fork: 1 of 1
# Warmup Iteration   1: 20.741 ±(99.9%) 0.162 ms/op
# Warmup Iteration   2: 9.181 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 7.405 ±(99.9%) 0.014 ms/op
Iteration   1: 7.163 ±(99.9%) 0.015 ms/op
Iteration   2: 6.792 ±(99.9%) 0.013 ms/op
Iteration   3: 6.957 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.971 ±(99.9%) 3.387 ms/op [Average]
  (min, avg, max) = (6.792, 6.971, 7.163), stdev = 0.186
  CI (99.9%): [3.583, 10.358] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:26
# Fork: 1 of 1
# Warmup Iteration   1: 19.033 ±(99.9%) 0.304 ms/op
# Warmup Iteration   2: 7.943 ±(99.9%) 0.060 ms/op
# Warmup Iteration   3: 6.066 ±(99.9%) 0.030 ms/op
Iteration   1: 5.697 ±(99.9%) 0.022 ms/op
                 createUser·p0.00:   1.833 ms/op
                 createUser·p0.50:   5.308 ms/op
                 createUser·p0.90:   7.201 ms/op
                 createUser·p0.95:   8.323 ms/op
                 createUser·p0.99:   11.332 ms/op
                 createUser·p0.999:  25.756 ms/op
                 createUser·p0.9999: 29.917 ms/op
                 createUser·p1.00:   30.507 ms/op

Iteration   2: 5.879 ±(99.9%) 0.024 ms/op
                 createUser·p0.00:   2.449 ms/op
                 createUser·p0.50:   5.439 ms/op
                 createUser·p0.90:   7.520 ms/op
                 createUser·p0.95:   8.733 ms/op
                 createUser·p0.99:   12.304 ms/op
                 createUser·p0.999:  22.741 ms/op
                 createUser·p0.9999: 28.344 ms/op
                 createUser·p1.00:   29.000 ms/op

Iteration   3: 5.951 ±(99.9%) 0.029 ms/op
                 createUser·p0.00:   2.445 ms/op
                 createUser·p0.50:   5.448 ms/op
                 createUser·p0.90:   7.725 ms/op
                 createUser·p0.95:   9.060 ms/op
                 createUser·p0.99:   12.939 ms/op
                 createUser·p0.999:  29.031 ms/op
                 createUser·p0.9999: 49.562 ms/op
                 createUser·p1.00:   51.118 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 164258
  mean =      5.840 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 48266 
    [ 5.000, 10.000) = 111718 
    [10.000, 15.000) = 3567 
    [15.000, 20.000) = 477 
    [20.000, 25.000) = 67 
    [25.000, 30.000) = 109 
    [30.000, 35.000) = 22 
    [35.000, 40.000) = 0 
    [40.000, 45.000) = 10 
    [45.000, 50.000) = 19 
    [50.000, 55.000) = 3 

  Percentiles, ms/op:
      p(0.0000) =      1.833 ms/op
     p(50.0000) =      5.390 ms/op
     p(90.0000) =      7.487 ms/op
     p(95.0000) =      8.700 ms/op
     p(99.0000) =     12.272 ms/op
     p(99.9000) =     24.718 ms/op
     p(99.9900) =     46.073 ms/op
     p(99.9990) =     50.739 ms/op
     p(99.9999) =     51.118 ms/op
    p(100.0000) =     51.118 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:20
# Fork: 1 of 1
# Warmup Iteration   1: 19.264 ±(99.9%) 0.348 ms/op
# Warmup Iteration   2: 7.976 ±(99.9%) 0.063 ms/op
# Warmup Iteration   3: 5.857 ±(99.9%) 0.025 ms/op
Iteration   1: 5.897 ±(99.9%) 0.028 ms/op
                 existUser·p0.00:   2.408 ms/op
                 existUser·p0.50:   5.341 ms/op
                 existUser·p0.90:   7.954 ms/op
                 existUser·p0.95:   9.339 ms/op
                 existUser·p0.99:   13.557 ms/op
                 existUser·p0.999:  29.114 ms/op
                 existUser·p0.9999: 31.752 ms/op
                 existUser·p1.00:   32.571 ms/op

Iteration   2: 6.021 ±(99.9%) 0.026 ms/op
                 existUser·p0.00:   1.999 ms/op
                 existUser·p0.50:   5.546 ms/op
                 existUser·p0.90:   7.963 ms/op
                 existUser·p0.95:   9.241 ms/op
                 existUser·p0.99:   13.124 ms/op
                 existUser·p0.999:  18.509 ms/op
                 existUser·p0.9999: 32.168 ms/op
                 existUser·p1.00:   32.539 ms/op

Iteration   3: 5.689 ±(99.9%) 0.024 ms/op
                 existUser·p0.00:   1.665 ms/op
                 existUser·p0.50:   5.251 ms/op
                 existUser·p0.90:   7.356 ms/op
                 existUser·p0.95:   8.503 ms/op
                 existUser·p0.99:   11.895 ms/op
                 existUser·p0.999:  31.776 ms/op
                 existUser·p0.9999: 34.939 ms/op
                 existUser·p1.00:   36.176 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 163591
  mean =      5.866 ±(99.9%) 0.015 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 33 
    [ 2.500,  5.000) = 51577 
    [ 5.000,  7.500) = 93026 
    [ 7.500, 10.000) = 13640 
    [10.000, 12.500) = 3397 
    [12.500, 15.000) = 1243 
    [15.000, 17.500) = 417 
    [17.500, 20.000) = 47 
    [20.000, 22.500) = 27 
    [22.500, 25.000) = 24 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 46 
    [30.000, 32.500) = 61 
    [32.500, 35.000) = 48 
    [35.000, 37.500) = 5 

  Percentiles, ms/op:
      p(0.0000) =      1.665 ms/op
     p(50.0000) =      5.366 ms/op
     p(90.0000) =      7.774 ms/op
     p(95.0000) =      9.011 ms/op
     p(99.0000) =     12.845 ms/op
     p(99.9000) =     24.327 ms/op
     p(99.9900) =     34.514 ms/op
     p(99.9990) =     36.051 ms/op
     p(99.9999) =     36.176 ms/op
    p(100.0000) =     36.176 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:13
# Fork: 1 of 1
# Warmup Iteration   1: 21.242 ±(99.9%) 0.319 ms/op
# Warmup Iteration   2: 7.544 ±(99.9%) 0.056 ms/op
# Warmup Iteration   3: 6.370 ±(99.9%) 0.030 ms/op
Iteration   1: 6.329 ±(99.9%) 0.029 ms/op
                 getUser·p0.00:   2.970 ms/op
                 getUser·p0.50:   5.767 ms/op
                 getUser·p0.90:   8.798 ms/op
                 getUser·p0.95:   10.191 ms/op
                 getUser·p0.99:   14.074 ms/op
                 getUser·p0.999:  21.692 ms/op
                 getUser·p0.9999: 26.704 ms/op
                 getUser·p1.00:   28.049 ms/op

Iteration   2: 6.081 ±(99.9%) 0.029 ms/op
                 getUser·p0.00:   2.552 ms/op
                 getUser·p0.50:   5.480 ms/op
                 getUser·p0.90:   8.225 ms/op
                 getUser·p0.95:   9.732 ms/op
                 getUser·p0.99:   13.763 ms/op
                 getUser·p0.999:  29.034 ms/op
                 getUser·p0.9999: 34.734 ms/op
                 getUser·p1.00:   35.193 ms/op

Iteration   3: 6.256 ±(99.9%) 0.033 ms/op
                 getUser·p0.00:   2.302 ms/op
                 getUser·p0.50:   5.612 ms/op
                 getUser·p0.90:   8.569 ms/op
                 getUser·p0.95:   10.289 ms/op
                 getUser·p0.99:   14.582 ms/op
                 getUser·p0.999:  32.503 ms/op
                 getUser·p0.9999: 44.420 ms/op
                 getUser·p1.00:   45.351 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 154224
  mean =      6.220 ±(99.9%) 0.018 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 34268 
    [ 5.000, 10.000) = 112096 
    [10.000, 15.000) = 6836 
    [15.000, 20.000) = 787 
    [20.000, 25.000) = 79 
    [25.000, 30.000) = 54 
    [30.000, 35.000) = 64 
    [35.000, 40.000) = 8 
    [40.000, 45.000) = 31 

  Percentiles, ms/op:
      p(0.0000) =      2.302 ms/op
     p(50.0000) =      5.620 ms/op
     p(90.0000) =      8.536 ms/op
     p(95.0000) =     10.043 ms/op
     p(99.0000) =     14.172 ms/op
     p(99.9000) =     25.249 ms/op
     p(99.9900) =     42.712 ms/op
     p(99.9990) =     44.960 ms/op
     p(99.9999) =     45.351 ms/op
    p(100.0000) =     45.351 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 22.607 ±(99.9%) 0.432 ms/op
# Warmup Iteration   2: 8.682 ±(99.9%) 0.063 ms/op
# Warmup Iteration   3: 7.204 ±(99.9%) 0.038 ms/op
Iteration   1: 6.838 ±(99.9%) 0.032 ms/op
                 listUser·p0.00:   3.396 ms/op
                 listUser·p0.50:   6.291 ms/op
                 listUser·p0.90:   8.634 ms/op
                 listUser·p0.95:   10.469 ms/op
                 listUser·p0.99:   14.662 ms/op
                 listUser·p0.999:  31.168 ms/op
                 listUser·p0.9999: 34.755 ms/op
                 listUser·p1.00:   35.389 ms/op

Iteration   2: 6.888 ±(99.9%) 0.032 ms/op
                 listUser·p0.00:   3.121 ms/op
                 listUser·p0.50:   6.390 ms/op
                 listUser·p0.90:   8.618 ms/op
                 listUser·p0.95:   10.060 ms/op
                 listUser·p0.99:   14.189 ms/op
                 listUser·p0.999:  30.999 ms/op
                 listUser·p0.9999: 33.110 ms/op
                 listUser·p1.00:   33.686 ms/op

Iteration   3: 7.010 ±(99.9%) 0.032 ms/op
                 listUser·p0.00:   3.453 ms/op
                 listUser·p0.50:   6.513 ms/op
                 listUser·p0.90:   8.880 ms/op
                 listUser·p0.95:   10.519 ms/op
                 listUser·p0.99:   13.943 ms/op
                 listUser·p0.999:  35.193 ms/op
                 listUser·p0.9999: 40.006 ms/op
                 listUser·p1.00:   40.829 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 138791
  mean =      6.911 ±(99.9%) 0.018 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 2900 
    [ 5.000, 10.000) = 127964 
    [10.000, 15.000) = 6798 
    [15.000, 20.000) = 670 
    [20.000, 25.000) = 121 
    [25.000, 30.000) = 111 
    [30.000, 35.000) = 175 
    [35.000, 40.000) = 48 
    [40.000, 45.000) = 4 

  Percentiles, ms/op:
      p(0.0000) =      3.121 ms/op
     p(50.0000) =      6.406 ms/op
     p(90.0000) =      8.716 ms/op
     p(95.0000) =     10.322 ms/op
     p(99.0000) =     14.254 ms/op
     p(99.9000) =     31.752 ms/op
     p(99.9900) =     38.478 ms/op
     p(99.9990) =     40.651 ms/op
     p(99.9999) =     40.829 ms/op
    p(100.0000) =     40.829 ms/op


# Run complete. Total time: 00:13:23

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.268 ± 2.888  ops/ms
ClientPb.existUser                       thrpt       3   5.668 ± 1.522  ops/ms
ClientPb.getUser                         thrpt       3   5.458 ± 2.529  ops/ms
ClientPb.listUser                        thrpt       3   4.443 ± 1.457  ops/ms
ClientPb.createUser                       avgt       3   5.960 ± 1.905   ms/op
ClientPb.existUser                        avgt       3   5.738 ± 3.082   ms/op
ClientPb.getUser                          avgt       3   6.091 ± 0.347   ms/op
ClientPb.listUser                         avgt       3   6.971 ± 3.387   ms/op
ClientPb.createUser                     sample  164258   5.840 ± 0.014   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.833           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.390           ms/op
ClientPb.createUser:createUser·p0.90    sample           7.487           ms/op
ClientPb.createUser:createUser·p0.95    sample           8.700           ms/op
ClientPb.createUser:createUser·p0.99    sample          12.272           ms/op
ClientPb.createUser:createUser·p0.999   sample          24.718           ms/op
ClientPb.createUser:createUser·p0.9999  sample          46.073           ms/op
ClientPb.createUser:createUser·p1.00    sample          51.118           ms/op
ClientPb.existUser                      sample  163591   5.866 ± 0.015   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.665           ms/op
ClientPb.existUser:existUser·p0.50      sample           5.366           ms/op
ClientPb.existUser:existUser·p0.90      sample           7.774           ms/op
ClientPb.existUser:existUser·p0.95      sample           9.011           ms/op
ClientPb.existUser:existUser·p0.99      sample          12.845           ms/op
ClientPb.existUser:existUser·p0.999     sample          24.327           ms/op
ClientPb.existUser:existUser·p0.9999    sample          34.514           ms/op
ClientPb.existUser:existUser·p1.00      sample          36.176           ms/op
ClientPb.getUser                        sample  154224   6.220 ± 0.018   ms/op
ClientPb.getUser:getUser·p0.00          sample           2.302           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.620           ms/op
ClientPb.getUser:getUser·p0.90          sample           8.536           ms/op
ClientPb.getUser:getUser·p0.95          sample          10.043           ms/op
ClientPb.getUser:getUser·p0.99          sample          14.172           ms/op
ClientPb.getUser:getUser·p0.999         sample          25.249           ms/op
ClientPb.getUser:getUser·p0.9999        sample          42.712           ms/op
ClientPb.getUser:getUser·p1.00          sample          45.351           ms/op
ClientPb.listUser                       sample  138791   6.911 ± 0.018   ms/op
ClientPb.listUser:listUser·p0.00        sample           3.121           ms/op
ClientPb.listUser:listUser·p0.50        sample           6.406           ms/op
ClientPb.listUser:listUser·p0.90        sample           8.716           ms/op
ClientPb.listUser:listUser·p0.95        sample          10.322           ms/op
ClientPb.listUser:listUser·p0.99        sample          14.254           ms/op
ClientPb.listUser:listUser·p0.999       sample          31.752           ms/op
ClientPb.listUser:listUser·p0.9999      sample          38.478           ms/op
ClientPb.listUser:listUser·p1.00        sample          40.829           ms/op
