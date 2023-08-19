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
# Warmup Iteration   1: 1.706 ops/ms
# Warmup Iteration   2: 5.122 ops/ms
# Warmup Iteration   3: 8.477 ops/ms
Iteration   1: 8.870 ops/ms
Iteration   2: 9.419 ops/ms
Iteration   3: 9.192 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.160 ±(99.9%) 5.036 ops/ms [Average]
  (min, avg, max) = (8.870, 9.160, 9.419), stdev = 0.276
  CI (99.9%): [4.125, 14.196] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 2.865 ops/ms
# Warmup Iteration   2: 8.195 ops/ms
# Warmup Iteration   3: 9.107 ops/ms
Iteration   1: 9.370 ops/ms
Iteration   2: 9.236 ops/ms
Iteration   3: 9.401 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.335 ±(99.9%) 1.601 ops/ms [Average]
  (min, avg, max) = (9.236, 9.335, 9.401), stdev = 0.088
  CI (99.9%): [7.734, 10.937] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 2.811 ops/ms
# Warmup Iteration   2: 8.166 ops/ms
# Warmup Iteration   3: 8.570 ops/ms
Iteration   1: 9.362 ops/ms
Iteration   2: 9.204 ops/ms
Iteration   3: 8.689 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.085 ±(99.9%) 6.419 ops/ms [Average]
  (min, avg, max) = (8.689, 9.085, 9.362), stdev = 0.352
  CI (99.9%): [2.666, 15.504] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:49
# Fork: 1 of 1
# Warmup Iteration   1: 2.743 ops/ms
# Warmup Iteration   2: 7.152 ops/ms
# Warmup Iteration   3: 7.848 ops/ms
Iteration   1: 7.908 ops/ms
Iteration   2: 7.806 ops/ms
Iteration   3: 7.849 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.855 ±(99.9%) 0.936 ops/ms [Average]
  (min, avg, max) = (7.806, 7.855, 7.908), stdev = 0.051
  CI (99.9%): [6.919, 8.790] (assumes normal distribution)


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
# Warmup Iteration   1: 11.724 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 4.028 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.833 ±(99.9%) 0.005 ms/op
Iteration   1: 3.646 ±(99.9%) 0.005 ms/op
Iteration   2: 3.554 ±(99.9%) 0.005 ms/op
Iteration   3: 3.563 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.587 ±(99.9%) 0.922 ms/op [Average]
  (min, avg, max) = (3.554, 3.587, 3.646), stdev = 0.051
  CI (99.9%): [2.665, 4.509] (assumes normal distribution)


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
# Warmup Iteration   1: 10.895 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 4.302 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.450 ±(99.9%) 0.007 ms/op
Iteration   1: 3.432 ±(99.9%) 0.002 ms/op
Iteration   2: 3.437 ±(99.9%) 0.007 ms/op
Iteration   3: 3.415 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.428 ±(99.9%) 0.214 ms/op [Average]
  (min, avg, max) = (3.415, 3.428, 3.437), stdev = 0.012
  CI (99.9%): [3.214, 3.642] (assumes normal distribution)


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
# Warmup Iteration   1: 9.659 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 4.202 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.617 ±(99.9%) 0.004 ms/op
Iteration   1: 3.484 ±(99.9%) 0.004 ms/op
Iteration   2: 3.658 ±(99.9%) 0.004 ms/op
Iteration   3: 3.638 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.593 ±(99.9%) 1.729 ms/op [Average]
  (min, avg, max) = (3.484, 3.593, 3.658), stdev = 0.095
  CI (99.9%): [1.865, 5.322] (assumes normal distribution)


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
# Warmup Iteration   1: 11.959 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 4.563 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 4.132 ±(99.9%) 0.009 ms/op
Iteration   1: 4.262 ±(99.9%) 0.006 ms/op
Iteration   2: 3.964 ±(99.9%) 0.009 ms/op
Iteration   3: 4.108 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.111 ±(99.9%) 2.717 ms/op [Average]
  (min, avg, max) = (3.964, 4.111, 4.262), stdev = 0.149
  CI (99.9%): [1.394, 6.828] (assumes normal distribution)


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
# Warmup Iteration   1: 10.116 ±(99.9%) 0.146 ms/op
# Warmup Iteration   2: 4.186 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 3.489 ±(99.9%) 0.011 ms/op
Iteration   1: 3.695 ±(99.9%) 0.015 ms/op
                 createUser·p0.00:   1.591 ms/op
                 createUser·p0.50:   3.383 ms/op
                 createUser·p0.90:   4.447 ms/op
                 createUser·p0.95:   5.915 ms/op
                 createUser·p0.99:   7.602 ms/op
                 createUser·p0.999:  20.935 ms/op
                 createUser·p0.9999: 32.145 ms/op
                 createUser·p1.00:   33.063 ms/op

Iteration   2: 3.436 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.470 ms/op
                 createUser·p0.50:   3.305 ms/op
                 createUser·p0.90:   3.883 ms/op
                 createUser·p0.95:   4.252 ms/op
                 createUser·p0.99:   6.595 ms/op
                 createUser·p0.999:  22.511 ms/op
                 createUser·p0.9999: 26.476 ms/op
                 createUser·p1.00:   29.590 ms/op

Iteration   3: 3.413 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.577 ms/op
                 createUser·p0.50:   3.310 ms/op
                 createUser·p0.90:   3.822 ms/op
                 createUser·p0.95:   4.088 ms/op
                 createUser·p0.99:   6.119 ms/op
                 createUser·p0.999:  19.785 ms/op
                 createUser·p0.9999: 29.426 ms/op
                 createUser·p1.00:   30.933 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 273308
  mean =      3.510 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6113 
    [ 2.500,  5.000) = 256650 
    [ 5.000,  7.500) = 8657 
    [ 7.500, 10.000) = 1175 
    [10.000, 12.500) = 293 
    [12.500, 15.000) = 70 
    [15.000, 17.500) = 13 
    [17.500, 20.000) = 41 
    [20.000, 22.500) = 84 
    [22.500, 25.000) = 118 
    [25.000, 27.500) = 33 
    [27.500, 30.000) = 27 
    [30.000, 32.500) = 29 
    [32.500, 35.000) = 5 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.470 ms/op
     p(50.0000) =      3.322 ms/op
     p(90.0000) =      3.977 ms/op
     p(95.0000) =      4.555 ms/op
     p(99.0000) =      7.200 ms/op
     p(99.9000) =     20.666 ms/op
     p(99.9900) =     31.621 ms/op
     p(99.9990) =     32.836 ms/op
     p(99.9999) =     33.063 ms/op
    p(100.0000) =     33.063 ms/op


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
# Warmup Iteration   1: 8.362 ±(99.9%) 0.111 ms/op
# Warmup Iteration   2: 3.692 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.556 ±(99.9%) 0.010 ms/op
Iteration   1: 3.335 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.522 ms/op
                 existUser·p0.50:   3.207 ms/op
                 existUser·p0.90:   3.596 ms/op
                 existUser·p0.95:   3.863 ms/op
                 existUser·p0.99:   6.341 ms/op
                 existUser·p0.999:  18.744 ms/op
                 existUser·p0.9999: 30.926 ms/op
                 existUser·p1.00:   31.523 ms/op

Iteration   2: 3.424 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.282 ms/op
                 existUser·p0.50:   3.240 ms/op
                 existUser·p0.90:   3.903 ms/op
                 existUser·p0.95:   4.276 ms/op
                 existUser·p0.99:   6.332 ms/op
                 existUser·p0.999:  10.299 ms/op
                 existUser·p0.9999: 29.174 ms/op
                 existUser·p1.00:   29.721 ms/op

Iteration   3: 3.504 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.591 ms/op
                 existUser·p0.50:   3.359 ms/op
                 existUser·p0.90:   3.944 ms/op
                 existUser·p0.95:   4.342 ms/op
                 existUser·p0.99:   7.102 ms/op
                 existUser·p0.999:  20.799 ms/op
                 existUser·p0.9999: 25.448 ms/op
                 existUser·p1.00:   25.887 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 280643
  mean =      3.419 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2770 
    [ 2.500,  5.000) = 270205 
    [ 5.000,  7.500) = 6237 
    [ 7.500, 10.000) = 1007 
    [10.000, 12.500) = 136 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 19 
    [20.000, 22.500) = 81 
    [22.500, 25.000) = 63 
    [25.000, 27.500) = 35 
    [27.500, 30.000) = 45 
    [30.000, 32.500) = 13 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.282 ms/op
     p(50.0000) =      3.252 ms/op
     p(90.0000) =      3.830 ms/op
     p(95.0000) =      4.219 ms/op
     p(99.0000) =      6.504 ms/op
     p(99.9000) =     12.796 ms/op
     p(99.9900) =     28.506 ms/op
     p(99.9990) =     31.253 ms/op
     p(99.9999) =     31.523 ms/op
    p(100.0000) =     31.523 ms/op


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
# Warmup Iteration   1: 11.266 ±(99.9%) 0.163 ms/op
# Warmup Iteration   2: 3.766 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.537 ±(99.9%) 0.012 ms/op
Iteration   1: 3.479 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.446 ms/op
                 getUser·p0.50:   3.301 ms/op
                 getUser·p0.90:   3.793 ms/op
                 getUser·p0.95:   4.604 ms/op
                 getUser·p0.99:   6.955 ms/op
                 getUser·p0.999:  19.663 ms/op
                 getUser·p0.9999: 22.532 ms/op
                 getUser·p1.00:   23.331 ms/op

Iteration   2: 3.543 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.196 ms/op
                 getUser·p0.50:   3.396 ms/op
                 getUser·p0.90:   4.047 ms/op
                 getUser·p0.95:   4.540 ms/op
                 getUser·p0.99:   6.668 ms/op
                 getUser·p0.999:  22.512 ms/op
                 getUser·p0.9999: 25.132 ms/op
                 getUser·p1.00:   25.919 ms/op

Iteration   3: 3.558 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.419 ms/op
                 getUser·p0.50:   3.404 ms/op
                 getUser·p0.90:   3.928 ms/op
                 getUser·p0.95:   4.473 ms/op
                 getUser·p0.99:   6.939 ms/op
                 getUser·p0.999:  10.733 ms/op
                 getUser·p0.9999: 26.248 ms/op
                 getUser·p1.00:   27.558 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 272150
  mean =      3.526 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4165 
    [ 2.500,  5.000) = 256891 
    [ 5.000,  7.500) = 9337 
    [ 7.500, 10.000) = 1262 
    [10.000, 12.500) = 237 
    [12.500, 15.000) = 2 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 14 
    [20.000, 22.500) = 89 
    [22.500, 25.000) = 122 
    [25.000, 27.500) = 30 

  Percentiles, ms/op:
      p(0.0000) =      1.196 ms/op
     p(50.0000) =      3.367 ms/op
     p(90.0000) =      3.940 ms/op
     p(95.0000) =      4.538 ms/op
     p(99.0000) =      6.857 ms/op
     p(99.9000) =     11.925 ms/op
     p(99.9900) =     25.060 ms/op
     p(99.9990) =     26.855 ms/op
     p(99.9999) =     27.558 ms/op
    p(100.0000) =     27.558 ms/op


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
# Warmup Iteration   1: 10.092 ±(99.9%) 0.130 ms/op
# Warmup Iteration   2: 4.548 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.275 ±(99.9%) 0.014 ms/op
Iteration   1: 4.156 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.726 ms/op
                 listUser·p0.50:   3.985 ms/op
                 listUser·p0.90:   4.456 ms/op
                 listUser·p0.95:   4.866 ms/op
                 listUser·p0.99:   8.349 ms/op
                 listUser·p0.999:  21.589 ms/op
                 listUser·p0.9999: 23.959 ms/op
                 listUser·p1.00:   24.904 ms/op

Iteration   2: 4.135 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.306 ms/op
                 listUser·p0.50:   3.977 ms/op
                 listUser·p0.90:   4.588 ms/op
                 listUser·p0.95:   5.030 ms/op
                 listUser·p0.99:   7.569 ms/op
                 listUser·p0.999:  15.385 ms/op
                 listUser·p0.9999: 18.238 ms/op
                 listUser·p1.00:   22.315 ms/op

Iteration   3: 4.164 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   2.347 ms/op
                 listUser·p0.50:   3.977 ms/op
                 listUser·p0.90:   4.465 ms/op
                 listUser·p0.95:   4.932 ms/op
                 listUser·p0.99:   8.380 ms/op
                 listUser·p0.999:  18.649 ms/op
                 listUser·p0.9999: 25.242 ms/op
                 listUser·p1.00:   25.330 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 231286
  mean =      4.151 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 57 
    [ 2.500,  5.000) = 220144 
    [ 5.000,  7.500) = 7777 
    [ 7.500, 10.000) = 2308 
    [10.000, 12.500) = 500 
    [12.500, 15.000) = 99 
    [15.000, 17.500) = 182 
    [17.500, 20.000) = 76 
    [20.000, 22.500) = 59 
    [22.500, 25.000) = 74 
    [25.000, 27.500) = 10 

  Percentiles, ms/op:
      p(0.0000) =      1.726 ms/op
     p(50.0000) =      3.981 ms/op
     p(90.0000) =      4.506 ms/op
     p(95.0000) =      4.956 ms/op
     p(99.0000) =      8.094 ms/op
     p(99.9000) =     17.194 ms/op
     p(99.9900) =     23.855 ms/op
     p(99.9990) =     25.297 ms/op
     p(99.9999) =     25.330 ms/op
    p(100.0000) =     25.330 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.160 ± 5.036  ops/ms
ClientPb.existUser                       thrpt       3   9.335 ± 1.601  ops/ms
ClientPb.getUser                         thrpt       3   9.085 ± 6.419  ops/ms
ClientPb.listUser                        thrpt       3   7.855 ± 0.936  ops/ms
ClientPb.createUser                       avgt       3   3.587 ± 0.922   ms/op
ClientPb.existUser                        avgt       3   3.428 ± 0.214   ms/op
ClientPb.getUser                          avgt       3   3.593 ± 1.729   ms/op
ClientPb.listUser                         avgt       3   4.111 ± 2.717   ms/op
ClientPb.createUser                     sample  273308   3.510 ± 0.007   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.470           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.322           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.977           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.555           ms/op
ClientPb.createUser:createUser·p0.99    sample           7.200           ms/op
ClientPb.createUser:createUser·p0.999   sample          20.666           ms/op
ClientPb.createUser:createUser·p0.9999  sample          31.621           ms/op
ClientPb.createUser:createUser·p1.00    sample          33.063           ms/op
ClientPb.existUser                      sample  280643   3.419 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.282           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.252           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.830           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.219           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.504           ms/op
ClientPb.existUser:existUser·p0.999     sample          12.796           ms/op
ClientPb.existUser:existUser·p0.9999    sample          28.506           ms/op
ClientPb.existUser:existUser·p1.00      sample          31.523           ms/op
ClientPb.getUser                        sample  272150   3.526 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.196           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.367           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.940           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.538           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.857           ms/op
ClientPb.getUser:getUser·p0.999         sample          11.925           ms/op
ClientPb.getUser:getUser·p0.9999        sample          25.060           ms/op
ClientPb.getUser:getUser·p1.00          sample          27.558           ms/op
ClientPb.listUser                       sample  231286   4.151 ± 0.007   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.726           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.981           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.506           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.956           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.094           ms/op
ClientPb.listUser:listUser·p0.999       sample          17.194           ms/op
ClientPb.listUser:listUser·p0.9999      sample          23.855           ms/op
ClientPb.listUser:listUser·p1.00        sample          25.330           ms/op
