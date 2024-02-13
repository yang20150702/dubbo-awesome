# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 5.196 ops/ms
# Warmup Iteration   2: 12.440 ops/ms
# Warmup Iteration   3: 12.631 ops/ms
Iteration   1: 12.812 ops/ms
Iteration   2: 13.065 ops/ms
Iteration   3: 13.231 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  13.036 ±(99.9%) 3.841 ops/ms [Average]
  (min, avg, max) = (12.812, 13.036, 13.231), stdev = 0.211
  CI (99.9%): [9.195, 16.877] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:02
# Fork: 1 of 1
# Warmup Iteration   1: 8.512 ops/ms
# Warmup Iteration   2: 13.726 ops/ms
# Warmup Iteration   3: 13.807 ops/ms
Iteration   1: 13.727 ops/ms
Iteration   2: 13.813 ops/ms
Iteration   3: 13.910 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.817 ±(99.9%) 1.671 ops/ms [Average]
  (min, avg, max) = (13.727, 13.817, 13.910), stdev = 0.092
  CI (99.9%): [12.145, 15.488] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 7.944 ops/ms
# Warmup Iteration   2: 12.910 ops/ms
# Warmup Iteration   3: 12.873 ops/ms
Iteration   1: 12.647 ops/ms
Iteration   2: 12.947 ops/ms
Iteration   3: 12.906 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.833 ±(99.9%) 2.966 ops/ms [Average]
  (min, avg, max) = (12.647, 12.833, 12.947), stdev = 0.163
  CI (99.9%): [9.868, 15.799] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:47
# Fork: 1 of 1
# Warmup Iteration   1: 6.839 ops/ms
# Warmup Iteration   2: 10.698 ops/ms
# Warmup Iteration   3: 10.880 ops/ms
Iteration   1: 11.143 ops/ms
Iteration   2: 11.001 ops/ms
Iteration   3: 11.210 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  11.118 ±(99.9%) 1.946 ops/ms [Average]
  (min, avg, max) = (11.001, 11.118, 11.210), stdev = 0.107
  CI (99.9%): [9.172, 13.064] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 3.706 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 2.502 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.483 ±(99.9%) 0.008 ms/op
Iteration   1: 2.499 ±(99.9%) 0.006 ms/op
Iteration   2: 2.436 ±(99.9%) 0.004 ms/op
Iteration   3: 2.468 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.468 ±(99.9%) 0.568 ms/op [Average]
  (min, avg, max) = (2.436, 2.468, 2.499), stdev = 0.031
  CI (99.9%): [1.899, 3.036] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:35
# Fork: 1 of 1
# Warmup Iteration   1: 3.662 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 2.423 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.419 ±(99.9%) 0.003 ms/op
Iteration   1: 2.390 ±(99.9%) 0.004 ms/op
Iteration   2: 2.407 ±(99.9%) 0.004 ms/op
Iteration   3: 2.406 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.401 ±(99.9%) 0.172 ms/op [Average]
  (min, avg, max) = (2.390, 2.401, 2.407), stdev = 0.009
  CI (99.9%): [2.229, 2.573] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:29
# Fork: 1 of 1
# Warmup Iteration   1: 3.777 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.497 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.423 ±(99.9%) 0.006 ms/op
Iteration   1: 2.384 ±(99.9%) 0.005 ms/op
Iteration   2: 2.355 ±(99.9%) 0.005 ms/op
Iteration   3: 2.406 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.381 ±(99.9%) 0.468 ms/op [Average]
  (min, avg, max) = (2.355, 2.381, 2.406), stdev = 0.026
  CI (99.9%): [1.913, 2.849] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:24
# Fork: 1 of 1
# Warmup Iteration   1: 4.538 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 2.970 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.894 ±(99.9%) 0.009 ms/op
Iteration   1: 2.886 ±(99.9%) 0.008 ms/op
Iteration   2: 2.901 ±(99.9%) 0.008 ms/op
Iteration   3: 2.908 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.898 ±(99.9%) 0.203 ms/op [Average]
  (min, avg, max) = (2.886, 2.898, 2.908), stdev = 0.011
  CI (99.9%): [2.696, 3.101] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:19
# Fork: 1 of 1
# Warmup Iteration   1: 4.065 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 2.633 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.509 ±(99.9%) 0.007 ms/op
Iteration   1: 2.496 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.641 ms/op
                 createUser·p0.50:   2.454 ms/op
                 createUser·p0.90:   3.244 ms/op
                 createUser·p0.95:   3.629 ms/op
                 createUser·p0.99:   4.620 ms/op
                 createUser·p0.999:  12.036 ms/op
                 createUser·p0.9999: 15.276 ms/op
                 createUser·p1.00:   16.073 ms/op

Iteration   2: 2.458 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.684 ms/op
                 createUser·p0.50:   2.433 ms/op
                 createUser·p0.90:   3.150 ms/op
                 createUser·p0.95:   3.506 ms/op
                 createUser·p0.99:   4.317 ms/op
                 createUser·p0.999:  11.271 ms/op
                 createUser·p0.9999: 14.713 ms/op
                 createUser·p1.00:   15.335 ms/op

Iteration   3: 2.486 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.524 ms/op
                 createUser·p0.50:   2.458 ms/op
                 createUser·p0.90:   3.170 ms/op
                 createUser·p0.95:   3.490 ms/op
                 createUser·p0.99:   4.350 ms/op
                 createUser·p0.999:  10.098 ms/op
                 createUser·p0.9999: 14.044 ms/op
                 createUser·p1.00:   15.417 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 386745
  mean =      2.480 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 405 
    [ 1.250,  2.500) = 205164 
    [ 2.500,  3.750) = 168149 
    [ 3.750,  5.000) = 11208 
    [ 5.000,  6.250) = 1013 
    [ 6.250,  7.500) = 219 
    [ 7.500,  8.750) = 98 
    [ 8.750, 10.000) = 55 
    [10.000, 11.250) = 100 
    [11.250, 12.500) = 126 
    [12.500, 13.750) = 90 
    [13.750, 15.000) = 96 
    [15.000, 16.250) = 22 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.524 ms/op
     p(50.0000) =      2.445 ms/op
     p(90.0000) =      3.191 ms/op
     p(95.0000) =      3.547 ms/op
     p(99.0000) =      4.432 ms/op
     p(99.9000) =     10.555 ms/op
     p(99.9900) =     14.746 ms/op
     p(99.9990) =     15.799 ms/op
     p(99.9999) =     16.073 ms/op
    p(100.0000) =     16.073 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.854 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 2.392 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.395 ±(99.9%) 0.005 ms/op
Iteration   1: 2.387 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.557 ms/op
                 existUser·p0.50:   2.322 ms/op
                 existUser·p0.90:   2.953 ms/op
                 existUser·p0.95:   3.133 ms/op
                 existUser·p0.99:   3.908 ms/op
                 existUser·p0.999:  7.672 ms/op
                 existUser·p0.9999: 13.330 ms/op
                 existUser·p1.00:   14.123 ms/op

Iteration   2: 2.359 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.840 ms/op
                 existUser·p0.50:   2.294 ms/op
                 existUser·p0.90:   2.961 ms/op
                 existUser·p0.95:   3.195 ms/op
                 existUser·p0.99:   3.996 ms/op
                 existUser·p0.999:  8.660 ms/op
                 existUser·p0.9999: 13.664 ms/op
                 existUser·p1.00:   15.696 ms/op

Iteration   3: 2.393 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.356 ms/op
                 existUser·p0.50:   2.347 ms/op
                 existUser·p0.90:   2.937 ms/op
                 existUser·p0.95:   3.064 ms/op
                 existUser·p0.99:   3.723 ms/op
                 existUser·p0.999:  5.923 ms/op
                 existUser·p0.9999: 10.480 ms/op
                 existUser·p1.00:   10.879 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 403009
  mean =      2.380 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 280 
    [ 1.250,  2.500) = 237910 
    [ 2.500,  3.750) = 159588 
    [ 3.750,  5.000) = 4271 
    [ 5.000,  6.250) = 472 
    [ 6.250,  7.500) = 100 
    [ 7.500,  8.750) = 27 
    [ 8.750, 10.000) = 97 
    [10.000, 11.250) = 68 
    [11.250, 12.500) = 63 
    [12.500, 13.750) = 118 
    [13.750, 15.000) = 14 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.356 ms/op
     p(50.0000) =      2.314 ms/op
     p(90.0000) =      2.949 ms/op
     p(95.0000) =      3.125 ms/op
     p(99.0000) =      3.883 ms/op
     p(99.9000) =      6.996 ms/op
     p(99.9900) =     13.369 ms/op
     p(99.9990) =     14.139 ms/op
     p(99.9999) =     15.696 ms/op
    p(100.0000) =     15.696 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:09
# Fork: 1 of 1
# Warmup Iteration   1: 4.114 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 2.596 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.529 ±(99.9%) 0.007 ms/op
Iteration   1: 2.514 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.672 ms/op
                 getUser·p0.50:   2.441 ms/op
                 getUser·p0.90:   3.273 ms/op
                 getUser·p0.95:   3.580 ms/op
                 getUser·p0.99:   4.563 ms/op
                 getUser·p0.999:  12.870 ms/op
                 getUser·p0.9999: 15.225 ms/op
                 getUser·p1.00:   17.433 ms/op

Iteration   2: 2.482 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.587 ms/op
                 getUser·p0.50:   2.425 ms/op
                 getUser·p0.90:   3.211 ms/op
                 getUser·p0.95:   3.584 ms/op
                 getUser·p0.99:   4.489 ms/op
                 getUser·p0.999:  8.716 ms/op
                 getUser·p0.9999: 13.685 ms/op
                 getUser·p1.00:   14.746 ms/op

Iteration   3: 2.477 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.800 ms/op
                 getUser·p0.50:   2.466 ms/op
                 getUser·p0.90:   3.092 ms/op
                 getUser·p0.95:   3.391 ms/op
                 getUser·p0.99:   4.219 ms/op
                 getUser·p0.999:  9.146 ms/op
                 getUser·p0.9999: 12.868 ms/op
                 getUser·p1.00:   13.648 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 385048
  mean =      2.491 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 515 
    [ 1.250,  2.500) = 202354 
    [ 2.500,  3.750) = 169707 
    [ 3.750,  5.000) = 10803 
    [ 5.000,  6.250) = 1036 
    [ 6.250,  7.500) = 166 
    [ 7.500,  8.750) = 61 
    [ 8.750, 10.000) = 49 
    [10.000, 11.250) = 51 
    [11.250, 12.500) = 53 
    [12.500, 13.750) = 167 
    [13.750, 15.000) = 69 
    [15.000, 16.250) = 16 
    [16.250, 17.500) = 1 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.587 ms/op
     p(50.0000) =      2.441 ms/op
     p(90.0000) =      3.187 ms/op
     p(95.0000) =      3.531 ms/op
     p(99.0000) =      4.424 ms/op
     p(99.9000) =      9.354 ms/op
     p(99.9900) =     14.606 ms/op
     p(99.9990) =     15.441 ms/op
     p(99.9999) =     17.433 ms/op
    p(100.0000) =     17.433 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:04
# Fork: 1 of 1
# Warmup Iteration   1: 4.872 ±(99.9%) 0.054 ms/op
# Warmup Iteration   2: 3.072 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 2.973 ±(99.9%) 0.010 ms/op
Iteration   1: 2.982 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.784 ms/op
                 listUser·p0.50:   2.884 ms/op
                 listUser·p0.90:   4.133 ms/op
                 listUser·p0.95:   4.669 ms/op
                 listUser·p0.99:   5.865 ms/op
                 listUser·p0.999:  9.846 ms/op
                 listUser·p0.9999: 12.012 ms/op
                 listUser·p1.00:   18.514 ms/op

Iteration   2: 2.983 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   0.815 ms/op
                 listUser·p0.50:   2.892 ms/op
                 listUser·p0.90:   4.076 ms/op
                 listUser·p0.95:   4.579 ms/op
                 listUser·p0.99:   5.751 ms/op
                 listUser·p0.999:  9.994 ms/op
                 listUser·p0.9999: 12.346 ms/op
                 listUser·p1.00:   15.745 ms/op

Iteration   3: 2.932 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   0.642 ms/op
                 listUser·p0.50:   2.830 ms/op
                 listUser·p0.90:   4.047 ms/op
                 listUser·p0.95:   4.530 ms/op
                 listUser·p0.99:   5.702 ms/op
                 listUser·p0.999:  10.926 ms/op
                 listUser·p0.9999: 12.908 ms/op
                 listUser·p1.00:   17.924 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 323268
  mean =      2.966 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 627 
    [ 1.250,  2.500) = 119190 
    [ 2.500,  3.750) = 153326 
    [ 3.750,  5.000) = 41163 
    [ 5.000,  6.250) = 6978 
    [ 6.250,  7.500) = 941 
    [ 7.500,  8.750) = 357 
    [ 8.750, 10.000) = 320 
    [10.000, 11.250) = 207 
    [11.250, 12.500) = 126 
    [12.500, 13.750) = 18 
    [13.750, 15.000) = 8 
    [15.000, 16.250) = 5 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.642 ms/op
     p(50.0000) =      2.867 ms/op
     p(90.0000) =      4.084 ms/op
     p(95.0000) =      4.588 ms/op
     p(99.0000) =      5.767 ms/op
     p(99.9000) =     10.191 ms/op
     p(99.9900) =     12.512 ms/op
     p(99.9990) =     15.908 ms/op
     p(99.9999) =     18.514 ms/op
    p(100.0000) =     18.514 ms/op


# Run complete. Total time: 00:13:00

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  13.036 ± 3.841  ops/ms
ClientPb.existUser                       thrpt       3  13.817 ± 1.671  ops/ms
ClientPb.getUser                         thrpt       3  12.833 ± 2.966  ops/ms
ClientPb.listUser                        thrpt       3  11.118 ± 1.946  ops/ms
ClientPb.createUser                       avgt       3   2.468 ± 0.568   ms/op
ClientPb.existUser                        avgt       3   2.401 ± 0.172   ms/op
ClientPb.getUser                          avgt       3   2.381 ± 0.468   ms/op
ClientPb.listUser                         avgt       3   2.898 ± 0.203   ms/op
ClientPb.createUser                     sample  386745   2.480 ± 0.004   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.524           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.445           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.191           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.547           ms/op
ClientPb.createUser:createUser·p0.99    sample           4.432           ms/op
ClientPb.createUser:createUser·p0.999   sample          10.555           ms/op
ClientPb.createUser:createUser·p0.9999  sample          14.746           ms/op
ClientPb.createUser:createUser·p1.00    sample          16.073           ms/op
ClientPb.existUser                      sample  403009   2.380 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.356           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.314           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.949           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.125           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.883           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.996           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.369           ms/op
ClientPb.existUser:existUser·p1.00      sample          15.696           ms/op
ClientPb.getUser                        sample  385048   2.491 ± 0.004   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.587           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.441           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.187           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.531           ms/op
ClientPb.getUser:getUser·p0.99          sample           4.424           ms/op
ClientPb.getUser:getUser·p0.999         sample           9.354           ms/op
ClientPb.getUser:getUser·p0.9999        sample          14.606           ms/op
ClientPb.getUser:getUser·p1.00          sample          17.433           ms/op
ClientPb.listUser                       sample  323268   2.966 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.642           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.867           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.084           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.588           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.767           ms/op
ClientPb.listUser:listUser·p0.999       sample          10.191           ms/op
ClientPb.listUser:listUser·p0.9999      sample          12.512           ms/op
ClientPb.listUser:listUser·p1.00        sample          18.514           ms/op
