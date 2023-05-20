# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.072 ops/ms
# Warmup Iteration   2: 4.887 ops/ms
# Warmup Iteration   3: 8.463 ops/ms
Iteration   1: 8.855 ops/ms
Iteration   2: 9.521 ops/ms
Iteration   3: 9.468 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.281 ±(99.9%) 6.752 ops/ms [Average]
  (min, avg, max) = (8.855, 9.281, 9.521), stdev = 0.370
  CI (99.9%): [2.530, 16.033] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:07
# Fork: 1 of 1
# Warmup Iteration   1: 2.980 ops/ms
# Warmup Iteration   2: 8.378 ops/ms
# Warmup Iteration   3: 9.489 ops/ms
Iteration   1: 9.675 ops/ms
Iteration   2: 9.616 ops/ms
Iteration   3: 9.571 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.621 ±(99.9%) 0.943 ops/ms [Average]
  (min, avg, max) = (9.571, 9.621, 9.675), stdev = 0.052
  CI (99.9%): [8.677, 10.564] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:11:01
# Fork: 1 of 1
# Warmup Iteration   1: 2.944 ops/ms
# Warmup Iteration   2: 8.279 ops/ms
# Warmup Iteration   3: 8.962 ops/ms
Iteration   1: 9.456 ops/ms
Iteration   2: 9.596 ops/ms
Iteration   3: 9.534 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.529 ±(99.9%) 1.280 ops/ms [Average]
  (min, avg, max) = (9.456, 9.529, 9.596), stdev = 0.070
  CI (99.9%): [8.249, 10.808] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:54
# Fork: 1 of 1
# Warmup Iteration   1: 2.884 ops/ms
# Warmup Iteration   2: 7.260 ops/ms
# Warmup Iteration   3: 8.028 ops/ms
Iteration   1: 8.231 ops/ms
Iteration   2: 8.385 ops/ms
Iteration   3: 8.491 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.369 ±(99.9%) 2.379 ops/ms [Average]
  (min, avg, max) = (8.231, 8.369, 8.491), stdev = 0.130
  CI (99.9%): [5.990, 10.748] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:48
# Fork: 1 of 1
# Warmup Iteration   1: 9.372 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 3.888 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.555 ±(99.9%) 0.007 ms/op
Iteration   1: 3.460 ±(99.9%) 0.007 ms/op
Iteration   2: 3.315 ±(99.9%) 0.006 ms/op
Iteration   3: 3.439 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.405 ±(99.9%) 1.429 ms/op [Average]
  (min, avg, max) = (3.315, 3.405, 3.460), stdev = 0.078
  CI (99.9%): [1.975, 4.834] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 7.818 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.728 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.280 ±(99.9%) 0.007 ms/op
Iteration   1: 3.286 ±(99.9%) 0.004 ms/op
Iteration   2: 3.203 ±(99.9%) 0.004 ms/op
Iteration   3: 3.255 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.248 ±(99.9%) 0.763 ms/op [Average]
  (min, avg, max) = (3.203, 3.248, 3.286), stdev = 0.042
  CI (99.9%): [2.485, 4.011] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 10.328 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.938 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.436 ±(99.9%) 0.006 ms/op
Iteration   1: 3.377 ±(99.9%) 0.008 ms/op
Iteration   2: 3.370 ±(99.9%) 0.004 ms/op
Iteration   3: 3.376 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.375 ±(99.9%) 0.068 ms/op [Average]
  (min, avg, max) = (3.370, 3.375, 3.377), stdev = 0.004
  CI (99.9%): [3.307, 3.443] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 10.453 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 4.472 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.029 ±(99.9%) 0.007 ms/op
Iteration   1: 3.996 ±(99.9%) 0.009 ms/op
Iteration   2: 4.002 ±(99.9%) 0.009 ms/op
Iteration   3: 3.990 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.996 ±(99.9%) 0.113 ms/op [Average]
  (min, avg, max) = (3.990, 3.996, 4.002), stdev = 0.006
  CI (99.9%): [3.883, 4.109] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 9.982 ±(99.9%) 0.138 ms/op
# Warmup Iteration   2: 4.035 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.448 ±(99.9%) 0.010 ms/op
Iteration   1: 3.541 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.563 ms/op
                 createUser·p0.50:   3.273 ms/op
                 createUser·p0.90:   4.010 ms/op
                 createUser·p0.95:   5.767 ms/op
                 createUser·p0.99:   7.362 ms/op
                 createUser·p0.999:  21.288 ms/op
                 createUser·p0.9999: 26.272 ms/op
                 createUser·p1.00:   27.460 ms/op

Iteration   2: 3.403 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.483 ms/op
                 createUser·p0.50:   3.211 ms/op
                 createUser·p0.90:   3.871 ms/op
                 createUser·p0.95:   4.293 ms/op
                 createUser·p0.99:   6.644 ms/op
                 createUser·p0.999:  23.955 ms/op
                 createUser·p0.9999: 27.434 ms/op
                 createUser·p1.00:   27.853 ms/op

Iteration   3: 3.309 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.397 ms/op
                 createUser·p0.50:   3.228 ms/op
                 createUser·p0.90:   3.473 ms/op
                 createUser·p0.95:   3.871 ms/op
                 createUser·p0.99:   5.734 ms/op
                 createUser·p0.999:  19.312 ms/op
                 createUser·p0.9999: 26.400 ms/op
                 createUser·p1.00:   27.197 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 280946
  mean =      3.415 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7631 
    [ 2.500,  5.000) = 262863 
    [ 5.000,  7.500) = 8739 
    [ 7.500, 10.000) = 1232 
    [10.000, 12.500) = 137 
    [12.500, 15.000) = 24 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 39 
    [20.000, 22.500) = 61 
    [22.500, 25.000) = 81 
    [25.000, 27.500) = 134 

  Percentiles, ms/op:
      p(0.0000) =      1.397 ms/op
     p(50.0000) =      3.236 ms/op
     p(90.0000) =      3.813 ms/op
     p(95.0000) =      4.325 ms/op
     p(99.0000) =      6.873 ms/op
     p(99.9000) =     19.932 ms/op
     p(99.9900) =     26.837 ms/op
     p(99.9990) =     27.538 ms/op
     p(99.9999) =     27.853 ms/op
    p(100.0000) =     27.853 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 9.405 ±(99.9%) 0.123 ms/op
# Warmup Iteration   2: 3.695 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.284 ±(99.9%) 0.008 ms/op
Iteration   1: 3.282 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.462 ms/op
                 existUser·p0.50:   3.215 ms/op
                 existUser·p0.90:   3.686 ms/op
                 existUser·p0.95:   4.219 ms/op
                 existUser·p0.99:   5.782 ms/op
                 existUser·p0.999:  17.976 ms/op
                 existUser·p0.9999: 23.088 ms/op
                 existUser·p1.00:   24.674 ms/op

Iteration   2: 3.264 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.243 ms/op
                 existUser·p0.50:   3.240 ms/op
                 existUser·p0.90:   3.543 ms/op
                 existUser·p0.95:   3.895 ms/op
                 existUser·p0.99:   5.390 ms/op
                 existUser·p0.999:  12.418 ms/op
                 existUser·p0.9999: 25.475 ms/op
                 existUser·p1.00:   26.771 ms/op

Iteration   3: 3.253 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.311 ms/op
                 existUser·p0.50:   3.109 ms/op
                 existUser·p0.90:   3.584 ms/op
                 existUser·p0.95:   3.939 ms/op
                 existUser·p0.99:   6.004 ms/op
                 existUser·p0.999:  13.059 ms/op
                 existUser·p0.9999: 25.051 ms/op
                 existUser·p1.00:   27.165 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 293541
  mean =      3.266 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 19154 
    [ 2.500,  5.000) = 269143 
    [ 5.000,  7.500) = 4089 
    [ 7.500, 10.000) = 534 
    [10.000, 12.500) = 253 
    [12.500, 15.000) = 66 
    [15.000, 17.500) = 9 
    [17.500, 20.000) = 45 
    [20.000, 22.500) = 104 
    [22.500, 25.000) = 116 
    [25.000, 27.500) = 28 

  Percentiles, ms/op:
      p(0.0000) =      1.243 ms/op
     p(50.0000) =      3.207 ms/op
     p(90.0000) =      3.587 ms/op
     p(95.0000) =      4.063 ms/op
     p(99.0000) =      5.603 ms/op
     p(99.9000) =     17.478 ms/op
     p(99.9900) =     24.902 ms/op
     p(99.9990) =     26.128 ms/op
     p(99.9999) =     27.165 ms/op
    p(100.0000) =     27.165 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 8.597 ±(99.9%) 0.110 ms/op
# Warmup Iteration   2: 3.807 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.450 ±(99.9%) 0.011 ms/op
Iteration   1: 3.475 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.434 ms/op
                 getUser·p0.50:   3.314 ms/op
                 getUser·p0.90:   4.067 ms/op
                 getUser·p0.95:   4.579 ms/op
                 getUser·p0.99:   6.341 ms/op
                 getUser·p0.999:  10.291 ms/op
                 getUser·p0.9999: 30.187 ms/op
                 getUser·p1.00:   30.802 ms/op

Iteration   2: 3.350 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.206 ms/op
                 getUser·p0.50:   3.236 ms/op
                 getUser·p0.90:   3.670 ms/op
                 getUser·p0.95:   3.863 ms/op
                 getUser·p0.99:   5.513 ms/op
                 getUser·p0.999:  21.999 ms/op
                 getUser·p0.9999: 26.768 ms/op
                 getUser·p1.00:   27.361 ms/op

Iteration   3: 3.520 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.575 ms/op
                 getUser·p0.50:   3.326 ms/op
                 getUser·p0.90:   3.961 ms/op
                 getUser·p0.95:   4.874 ms/op
                 getUser·p0.99:   6.693 ms/op
                 getUser·p0.999:  18.721 ms/op
                 getUser·p0.9999: 29.253 ms/op
                 getUser·p1.00:   30.474 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 278159
  mean =      3.447 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3611 
    [ 2.500,  5.000) = 265715 
    [ 5.000,  7.500) = 7681 
    [ 7.500, 10.000) = 679 
    [10.000, 12.500) = 143 
    [12.500, 15.000) = 68 
    [15.000, 17.500) = 5 
    [17.500, 20.000) = 18 
    [20.000, 22.500) = 33 
    [22.500, 25.000) = 77 
    [25.000, 27.500) = 66 
    [27.500, 30.000) = 48 
    [30.000, 32.500) = 15 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.206 ms/op
     p(50.0000) =      3.281 ms/op
     p(90.0000) =      3.891 ms/op
     p(95.0000) =      4.366 ms/op
     p(99.0000) =      6.291 ms/op
     p(99.9000) =     13.626 ms/op
     p(99.9900) =     29.426 ms/op
     p(99.9990) =     30.711 ms/op
     p(99.9999) =     30.802 ms/op
    p(100.0000) =     30.802 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 10.437 ±(99.9%) 0.132 ms/op
# Warmup Iteration   2: 4.399 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.194 ±(99.9%) 0.014 ms/op
Iteration   1: 4.042 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.134 ms/op
                 listUser·p0.50:   3.916 ms/op
                 listUser·p0.90:   4.399 ms/op
                 listUser·p0.95:   4.792 ms/op
                 listUser·p0.99:   7.299 ms/op
                 listUser·p0.999:  17.293 ms/op
                 listUser·p0.9999: 23.104 ms/op
                 listUser·p1.00:   24.707 ms/op

Iteration   2: 4.022 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.253 ms/op
                 listUser·p0.50:   3.903 ms/op
                 listUser·p0.90:   4.325 ms/op
                 listUser·p0.95:   4.547 ms/op
                 listUser·p0.99:   7.663 ms/op
                 listUser·p0.999:  15.428 ms/op
                 listUser·p0.9999: 18.388 ms/op
                 listUser·p1.00:   19.366 ms/op

Iteration   3: 4.020 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.363 ms/op
                 listUser·p0.50:   3.908 ms/op
                 listUser·p0.90:   4.473 ms/op
                 listUser·p0.95:   4.866 ms/op
                 listUser·p0.99:   7.116 ms/op
                 listUser·p0.999:  16.792 ms/op
                 listUser·p0.9999: 18.940 ms/op
                 listUser·p1.00:   18.973 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 238248
  mean =      4.028 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 25 
    [ 2.500,  5.000) = 229316 
    [ 5.000,  7.500) = 6640 
    [ 7.500, 10.000) = 1394 
    [10.000, 12.500) = 383 
    [12.500, 15.000) = 94 
    [15.000, 17.500) = 250 
    [17.500, 20.000) = 82 
    [20.000, 22.500) = 46 
    [22.500, 25.000) = 18 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.134 ms/op
     p(50.0000) =      3.912 ms/op
     p(90.0000) =      4.391 ms/op
     p(95.0000) =      4.735 ms/op
     p(99.0000) =      7.414 ms/op
     p(99.9000) =     16.466 ms/op
     p(99.9900) =     22.255 ms/op
     p(99.9990) =     24.017 ms/op
     p(99.9999) =     24.707 ms/op
    p(100.0000) =     24.707 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.281 ± 6.752  ops/ms
ClientPb.existUser                       thrpt       3   9.621 ± 0.943  ops/ms
ClientPb.getUser                         thrpt       3   9.529 ± 1.280  ops/ms
ClientPb.listUser                        thrpt       3   8.369 ± 2.379  ops/ms
ClientPb.createUser                       avgt       3   3.405 ± 1.429   ms/op
ClientPb.existUser                        avgt       3   3.248 ± 0.763   ms/op
ClientPb.getUser                          avgt       3   3.375 ± 0.068   ms/op
ClientPb.listUser                         avgt       3   3.996 ± 0.113   ms/op
ClientPb.createUser                     sample  280946   3.415 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.397           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.236           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.813           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.325           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.873           ms/op
ClientPb.createUser:createUser·p0.999   sample          19.932           ms/op
ClientPb.createUser:createUser·p0.9999  sample          26.837           ms/op
ClientPb.createUser:createUser·p1.00    sample          27.853           ms/op
ClientPb.existUser                      sample  293541   3.266 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.243           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.207           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.587           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.063           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.603           ms/op
ClientPb.existUser:existUser·p0.999     sample          17.478           ms/op
ClientPb.existUser:existUser·p0.9999    sample          24.902           ms/op
ClientPb.existUser:existUser·p1.00      sample          27.165           ms/op
ClientPb.getUser                        sample  278159   3.447 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.206           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.281           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.891           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.366           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.291           ms/op
ClientPb.getUser:getUser·p0.999         sample          13.626           ms/op
ClientPb.getUser:getUser·p0.9999        sample          29.426           ms/op
ClientPb.getUser:getUser·p1.00          sample          30.802           ms/op
ClientPb.listUser                       sample  238248   4.028 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.134           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.912           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.391           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.735           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.414           ms/op
ClientPb.listUser:listUser·p0.999       sample          16.466           ms/op
ClientPb.listUser:listUser·p0.9999      sample          22.255           ms/op
ClientPb.listUser:listUser·p1.00        sample          24.707           ms/op
