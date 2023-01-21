# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.200 ops/ms
# Warmup Iteration   2: 5.951 ops/ms
# Warmup Iteration   3: 8.612 ops/ms
Iteration   1: 8.696 ops/ms
Iteration   2: 8.980 ops/ms
Iteration   3: 9.488 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.055 ±(99.9%) 7.325 ops/ms [Average]
  (min, avg, max) = (8.696, 9.055, 9.488), stdev = 0.402
  CI (99.9%): [1.729, 16.380] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:07
# Fork: 1 of 1
# Warmup Iteration   1: 3.425 ops/ms
# Warmup Iteration   2: 8.966 ops/ms
# Warmup Iteration   3: 9.671 ops/ms
Iteration   1: 9.930 ops/ms
Iteration   2: 10.028 ops/ms
Iteration   3: 9.696 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.884 ±(99.9%) 3.116 ops/ms [Average]
  (min, avg, max) = (9.696, 9.884, 10.028), stdev = 0.171
  CI (99.9%): [6.768, 13.000] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.130 ops/ms
# Warmup Iteration   2: 8.419 ops/ms
# Warmup Iteration   3: 9.024 ops/ms
Iteration   1: 9.086 ops/ms
Iteration   2: 9.462 ops/ms
Iteration   3: 9.105 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.218 ±(99.9%) 3.861 ops/ms [Average]
  (min, avg, max) = (9.086, 9.218, 9.462), stdev = 0.212
  CI (99.9%): [5.357, 13.079] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 2.787 ops/ms
# Warmup Iteration   2: 7.251 ops/ms
# Warmup Iteration   3: 7.905 ops/ms
Iteration   1: 8.094 ops/ms
Iteration   2: 7.924 ops/ms
Iteration   3: 8.079 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.032 ±(99.9%) 1.715 ops/ms [Average]
  (min, avg, max) = (7.924, 8.032, 8.094), stdev = 0.094
  CI (99.9%): [6.317, 9.747] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 8.911 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.912 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.760 ±(99.9%) 0.007 ms/op
Iteration   1: 3.289 ±(99.9%) 0.014 ms/op
Iteration   2: 3.468 ±(99.9%) 0.003 ms/op
Iteration   3: 3.503 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.420 ±(99.9%) 2.096 ms/op [Average]
  (min, avg, max) = (3.289, 3.420, 3.503), stdev = 0.115
  CI (99.9%): [1.324, 5.516] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 9.460 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.631 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.437 ±(99.9%) 0.012 ms/op
Iteration   1: 3.440 ±(99.9%) 0.005 ms/op
Iteration   2: 3.386 ±(99.9%) 0.004 ms/op
Iteration   3: 3.313 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.380 ±(99.9%) 1.158 ms/op [Average]
  (min, avg, max) = (3.313, 3.380, 3.440), stdev = 0.063
  CI (99.9%): [2.222, 4.537] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 8.871 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.626 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.646 ±(99.9%) 0.006 ms/op
Iteration   1: 3.423 ±(99.9%) 0.008 ms/op
Iteration   2: 3.445 ±(99.9%) 0.003 ms/op
Iteration   3: 3.631 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.500 ±(99.9%) 2.084 ms/op [Average]
  (min, avg, max) = (3.423, 3.500, 3.631), stdev = 0.114
  CI (99.9%): [1.416, 5.583] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 11.653 ±(99.9%) 0.061 ms/op
# Warmup Iteration   2: 4.454 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.138 ±(99.9%) 0.007 ms/op
Iteration   1: 3.976 ±(99.9%) 0.006 ms/op
Iteration   2: 4.055 ±(99.9%) 0.015 ms/op
Iteration   3: 3.947 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.993 ±(99.9%) 1.015 ms/op [Average]
  (min, avg, max) = (3.947, 3.993, 4.055), stdev = 0.056
  CI (99.9%): [2.977, 5.008] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 9.885 ±(99.9%) 0.126 ms/op
# Warmup Iteration   2: 4.007 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.566 ±(99.9%) 0.011 ms/op
Iteration   1: 3.504 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.542 ms/op
                 createUser·p0.50:   3.363 ms/op
                 createUser·p0.90:   4.026 ms/op
                 createUser·p0.95:   4.334 ms/op
                 createUser·p0.99:   5.663 ms/op
                 createUser·p0.999:  18.981 ms/op
                 createUser·p0.9999: 36.298 ms/op
                 createUser·p1.00:   37.552 ms/op

Iteration   2: 3.463 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.462 ms/op
                 createUser·p0.50:   3.314 ms/op
                 createUser·p0.90:   3.936 ms/op
                 createUser·p0.95:   4.219 ms/op
                 createUser·p0.99:   5.964 ms/op
                 createUser·p0.999:  21.449 ms/op
                 createUser·p0.9999: 26.554 ms/op
                 createUser·p1.00:   29.098 ms/op

Iteration   3: 3.548 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.583 ms/op
                 createUser·p0.50:   3.379 ms/op
                 createUser·p0.90:   4.112 ms/op
                 createUser·p0.95:   4.456 ms/op
                 createUser·p0.99:   6.529 ms/op
                 createUser·p0.999:  20.880 ms/op
                 createUser·p0.9999: 27.488 ms/op
                 createUser·p1.00:   30.802 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 273912
  mean =      3.505 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6460 
    [ 2.500,  5.000) = 260719 
    [ 5.000,  7.500) = 5526 
    [ 7.500, 10.000) = 589 
    [10.000, 12.500) = 262 
    [12.500, 15.000) = 36 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 48 
    [20.000, 22.500) = 84 
    [22.500, 25.000) = 87 
    [25.000, 27.500) = 60 
    [27.500, 30.000) = 8 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 31 

  Percentiles, ms/op:
      p(0.0000) =      1.462 ms/op
     p(50.0000) =      3.363 ms/op
     p(90.0000) =      4.026 ms/op
     p(95.0000) =      4.342 ms/op
     p(99.0000) =      5.988 ms/op
     p(99.9000) =     19.959 ms/op
     p(99.9900) =     35.521 ms/op
     p(99.9990) =     36.817 ms/op
     p(99.9999) =     37.552 ms/op
    p(100.0000) =     37.552 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 7.857 ±(99.9%) 0.109 ms/op
# Warmup Iteration   2: 3.562 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.392 ±(99.9%) 0.009 ms/op
Iteration   1: 3.373 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.335 ms/op
                 existUser·p0.50:   3.277 ms/op
                 existUser·p0.90:   3.797 ms/op
                 existUser·p0.95:   4.182 ms/op
                 existUser·p0.99:   6.093 ms/op
                 existUser·p0.999:  20.590 ms/op
                 existUser·p0.9999: 26.173 ms/op
                 existUser·p1.00:   31.490 ms/op

Iteration   2: 3.394 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.772 ms/op
                 existUser·p0.50:   3.293 ms/op
                 existUser·p0.90:   3.932 ms/op
                 existUser·p0.95:   4.579 ms/op
                 existUser·p0.99:   5.964 ms/op
                 existUser·p0.999:  12.776 ms/op
                 existUser·p0.9999: 26.514 ms/op
                 existUser·p1.00:   27.197 ms/op

Iteration   3: 3.287 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.532 ms/op
                 existUser·p0.50:   3.174 ms/op
                 existUser·p0.90:   3.564 ms/op
                 existUser·p0.95:   3.887 ms/op
                 existUser·p0.99:   5.939 ms/op
                 existUser·p0.999:  10.811 ms/op
                 existUser·p0.9999: 31.490 ms/op
                 existUser·p1.00:   32.997 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 286412
  mean =      3.351 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17083 
    [ 2.500,  5.000) = 261216 
    [ 5.000,  7.500) = 7065 
    [ 7.500, 10.000) = 569 
    [10.000, 12.500) = 161 
    [12.500, 15.000) = 62 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 35 
    [22.500, 25.000) = 57 
    [25.000, 27.500) = 91 
    [27.500, 30.000) = 41 
    [30.000, 32.500) = 27 
    [32.500, 35.000) = 5 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.532 ms/op
     p(50.0000) =      3.265 ms/op
     p(90.0000) =      3.744 ms/op
     p(95.0000) =      4.284 ms/op
     p(99.0000) =      5.980 ms/op
     p(99.9000) =     12.759 ms/op
     p(99.9900) =     30.257 ms/op
     p(99.9990) =     32.688 ms/op
     p(99.9999) =     32.997 ms/op
    p(100.0000) =     32.997 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 9.712 ±(99.9%) 0.129 ms/op
# Warmup Iteration   2: 3.809 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.604 ±(99.9%) 0.011 ms/op
Iteration   1: 3.463 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.959 ms/op
                 getUser·p0.50:   3.310 ms/op
                 getUser·p0.90:   3.863 ms/op
                 getUser·p0.95:   4.596 ms/op
                 getUser·p0.99:   6.504 ms/op
                 getUser·p0.999:  12.894 ms/op
                 getUser·p0.9999: 24.175 ms/op
                 getUser·p1.00:   25.985 ms/op

Iteration   2: 3.374 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.298 ms/op
                 getUser·p0.50:   3.252 ms/op
                 getUser·p0.90:   3.764 ms/op
                 getUser·p0.95:   4.096 ms/op
                 getUser·p0.99:   6.283 ms/op
                 getUser·p0.999:  22.194 ms/op
                 getUser·p0.9999: 25.937 ms/op
                 getUser·p1.00:   27.558 ms/op

Iteration   3: 3.382 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.509 ms/op
                 getUser·p0.50:   3.260 ms/op
                 getUser·p0.90:   3.707 ms/op
                 getUser·p0.95:   3.912 ms/op
                 getUser·p0.99:   5.874 ms/op
                 getUser·p0.999:  19.839 ms/op
                 getUser·p0.9999: 28.216 ms/op
                 getUser·p1.00:   30.278 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 281556
  mean =      3.406 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5620 
    [ 2.500,  5.000) = 268047 
    [ 5.000,  7.500) = 6596 
    [ 7.500, 10.000) = 859 
    [10.000, 12.500) = 134 
    [12.500, 15.000) = 42 
    [15.000, 17.500) = 2 
    [17.500, 20.000) = 5 
    [20.000, 22.500) = 37 
    [22.500, 25.000) = 121 
    [25.000, 27.500) = 62 
    [27.500, 30.000) = 30 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.959 ms/op
     p(50.0000) =      3.273 ms/op
     p(90.0000) =      3.777 ms/op
     p(95.0000) =      4.108 ms/op
     p(99.0000) =      6.128 ms/op
     p(99.9000) =     12.927 ms/op
     p(99.9900) =     27.613 ms/op
     p(99.9990) =     29.064 ms/op
     p(99.9999) =     30.278 ms/op
    p(100.0000) =     30.278 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 10.722 ±(99.9%) 0.141 ms/op
# Warmup Iteration   2: 4.412 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.181 ±(99.9%) 0.012 ms/op
Iteration   1: 3.997 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.497 ms/op
                 listUser·p0.50:   3.777 ms/op
                 listUser·p0.90:   4.440 ms/op
                 listUser·p0.95:   4.784 ms/op
                 listUser·p0.99:   7.805 ms/op
                 listUser·p0.999:  22.839 ms/op
                 listUser·p0.9999: 27.656 ms/op
                 listUser·p1.00:   28.770 ms/op

Iteration   2: 3.989 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.915 ms/op
                 listUser·p0.50:   3.826 ms/op
                 listUser·p0.90:   4.391 ms/op
                 listUser·p0.95:   4.653 ms/op
                 listUser·p0.99:   6.980 ms/op
                 listUser·p0.999:  16.772 ms/op
                 listUser·p0.9999: 19.103 ms/op
                 listUser·p1.00:   22.315 ms/op

Iteration   3: 3.949 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.421 ms/op
                 listUser·p0.50:   3.838 ms/op
                 listUser·p0.90:   4.506 ms/op
                 listUser·p0.95:   4.841 ms/op
                 listUser·p0.99:   6.808 ms/op
                 listUser·p0.999:  16.417 ms/op
                 listUser·p0.9999: 20.349 ms/op
                 listUser·p1.00:   20.808 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 241313
  mean =      3.978 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 63 
    [ 2.500,  5.000) = 232294 
    [ 5.000,  7.500) = 7021 
    [ 7.500, 10.000) = 872 
    [10.000, 12.500) = 501 
    [12.500, 15.000) = 130 
    [15.000, 17.500) = 191 
    [17.500, 20.000) = 121 
    [20.000, 22.500) = 37 
    [22.500, 25.000) = 49 
    [25.000, 27.500) = 24 

  Percentiles, ms/op:
      p(0.0000) =      0.915 ms/op
     p(50.0000) =      3.817 ms/op
     p(90.0000) =      4.432 ms/op
     p(95.0000) =      4.784 ms/op
     p(99.0000) =      7.062 ms/op
     p(99.9000) =     17.521 ms/op
     p(99.9900) =     26.075 ms/op
     p(99.9990) =     28.658 ms/op
     p(99.9999) =     28.770 ms/op
    p(100.0000) =     28.770 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.055 ± 7.325  ops/ms
ClientPb.existUser                       thrpt       3   9.884 ± 3.116  ops/ms
ClientPb.getUser                         thrpt       3   9.218 ± 3.861  ops/ms
ClientPb.listUser                        thrpt       3   8.032 ± 1.715  ops/ms
ClientPb.createUser                       avgt       3   3.420 ± 2.096   ms/op
ClientPb.existUser                        avgt       3   3.380 ± 1.158   ms/op
ClientPb.getUser                          avgt       3   3.500 ± 2.084   ms/op
ClientPb.listUser                         avgt       3   3.993 ± 1.015   ms/op
ClientPb.createUser                     sample  273912   3.505 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.462           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.363           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.026           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.342           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.988           ms/op
ClientPb.createUser:createUser·p0.999   sample          19.959           ms/op
ClientPb.createUser:createUser·p0.9999  sample          35.521           ms/op
ClientPb.createUser:createUser·p1.00    sample          37.552           ms/op
ClientPb.existUser                      sample  286412   3.351 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.532           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.265           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.744           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.284           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.980           ms/op
ClientPb.existUser:existUser·p0.999     sample          12.759           ms/op
ClientPb.existUser:existUser·p0.9999    sample          30.257           ms/op
ClientPb.existUser:existUser·p1.00      sample          32.997           ms/op
ClientPb.getUser                        sample  281556   3.406 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.959           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.273           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.777           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.108           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.128           ms/op
ClientPb.getUser:getUser·p0.999         sample          12.927           ms/op
ClientPb.getUser:getUser·p0.9999        sample          27.613           ms/op
ClientPb.getUser:getUser·p1.00          sample          30.278           ms/op
ClientPb.listUser                       sample  241313   3.978 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.915           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.817           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.432           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.784           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.062           ms/op
ClientPb.listUser:listUser·p0.999       sample          17.521           ms/op
ClientPb.listUser:listUser·p0.9999      sample          26.075           ms/op
ClientPb.listUser:listUser·p1.00        sample          28.770           ms/op
