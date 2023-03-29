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
# Warmup Iteration   1: 2.002 ops/ms
# Warmup Iteration   2: 5.081 ops/ms
# Warmup Iteration   3: 8.466 ops/ms
Iteration   1: 8.965 ops/ms
Iteration   2: 9.314 ops/ms
Iteration   3: 9.136 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.138 ±(99.9%) 3.188 ops/ms [Average]
  (min, avg, max) = (8.965, 9.138, 9.314), stdev = 0.175
  CI (99.9%): [5.950, 12.327] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:08
# Fork: 1 of 1
# Warmup Iteration   1: 2.831 ops/ms
# Warmup Iteration   2: 8.535 ops/ms
# Warmup Iteration   3: 9.186 ops/ms
Iteration   1: 9.746 ops/ms
Iteration   2: 9.561 ops/ms
Iteration   3: 9.003 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.437 ±(99.9%) 7.053 ops/ms [Average]
  (min, avg, max) = (9.003, 9.437, 9.746), stdev = 0.387
  CI (99.9%): [2.384, 16.489] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:57
# Fork: 1 of 1
# Warmup Iteration   1: 2.692 ops/ms
# Warmup Iteration   2: 7.640 ops/ms
# Warmup Iteration   3: 8.781 ops/ms
Iteration   1: 9.505 ops/ms
Iteration   2: 9.308 ops/ms
Iteration   3: 9.110 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.308 ±(99.9%) 3.604 ops/ms [Average]
  (min, avg, max) = (9.110, 9.308, 9.505), stdev = 0.198
  CI (99.9%): [5.703, 12.912] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 2.406 ops/ms
# Warmup Iteration   2: 7.037 ops/ms
# Warmup Iteration   3: 7.642 ops/ms
Iteration   1: 7.808 ops/ms
Iteration   2: 7.977 ops/ms
Iteration   3: 8.312 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.033 ±(99.9%) 4.680 ops/ms [Average]
  (min, avg, max) = (7.808, 8.033, 8.312), stdev = 0.257
  CI (99.9%): [3.352, 12.713] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:47
# Fork: 1 of 1
# Warmup Iteration   1: 10.488 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 3.831 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.450 ±(99.9%) 0.006 ms/op
Iteration   1: 3.366 ±(99.9%) 0.013 ms/op
Iteration   2: 3.487 ±(99.9%) 0.007 ms/op
Iteration   3: 3.331 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.394 ±(99.9%) 1.494 ms/op [Average]
  (min, avg, max) = (3.331, 3.394, 3.487), stdev = 0.082
  CI (99.9%): [1.900, 4.889] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 10.184 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.690 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.289 ±(99.9%) 0.004 ms/op
Iteration   1: 3.214 ±(99.9%) 0.009 ms/op
Iteration   2: 3.313 ±(99.9%) 0.005 ms/op
Iteration   3: 3.365 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.298 ±(99.9%) 1.408 ms/op [Average]
  (min, avg, max) = (3.214, 3.298, 3.365), stdev = 0.077
  CI (99.9%): [1.890, 4.705] (assumes normal distribution)


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
# Warmup Iteration   1: 9.795 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.706 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.477 ±(99.9%) 0.008 ms/op
Iteration   1: 3.448 ±(99.9%) 0.010 ms/op
Iteration   2: 3.411 ±(99.9%) 0.006 ms/op
Iteration   3: 3.453 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.437 ±(99.9%) 0.413 ms/op [Average]
  (min, avg, max) = (3.411, 3.437, 3.453), stdev = 0.023
  CI (99.9%): [3.024, 3.851] (assumes normal distribution)


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
# Warmup Iteration   1: 11.315 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 4.574 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 4.119 ±(99.9%) 0.011 ms/op
Iteration   1: 4.063 ±(99.9%) 0.009 ms/op
Iteration   2: 3.950 ±(99.9%) 0.017 ms/op
Iteration   3: 3.929 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.981 ±(99.9%) 1.310 ms/op [Average]
  (min, avg, max) = (3.929, 3.981, 4.063), stdev = 0.072
  CI (99.9%): [2.671, 5.291] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 9.542 ±(99.9%) 0.149 ms/op
# Warmup Iteration   2: 4.001 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.577 ±(99.9%) 0.011 ms/op
Iteration   1: 3.557 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.536 ms/op
                 createUser·p0.50:   3.396 ms/op
                 createUser·p0.90:   4.252 ms/op
                 createUser·p0.95:   4.694 ms/op
                 createUser·p0.99:   6.062 ms/op
                 createUser·p0.999:  15.716 ms/op
                 createUser·p0.9999: 25.330 ms/op
                 createUser·p1.00:   26.509 ms/op

Iteration   2: 3.590 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.548 ms/op
                 createUser·p0.50:   3.437 ms/op
                 createUser·p0.90:   4.108 ms/op
                 createUser·p0.95:   4.620 ms/op
                 createUser·p0.99:   6.144 ms/op
                 createUser·p0.999:  23.917 ms/op
                 createUser·p0.9999: 30.123 ms/op
                 createUser·p1.00:   32.440 ms/op

Iteration   3: 3.505 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.597 ms/op
                 createUser·p0.50:   3.412 ms/op
                 createUser·p0.90:   3.965 ms/op
                 createUser·p0.95:   4.219 ms/op
                 createUser·p0.99:   5.620 ms/op
                 createUser·p0.999:  21.996 ms/op
                 createUser·p0.9999: 28.475 ms/op
                 createUser·p1.00:   29.753 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 270347
  mean =      3.550 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3869 
    [ 2.500,  5.000) = 258840 
    [ 5.000,  7.500) = 6510 
    [ 7.500, 10.000) = 615 
    [10.000, 12.500) = 154 
    [12.500, 15.000) = 45 
    [15.000, 17.500) = 55 
    [17.500, 20.000) = 2 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 65 
    [25.000, 27.500) = 69 
    [27.500, 30.000) = 81 
    [30.000, 32.500) = 10 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.536 ms/op
     p(50.0000) =      3.412 ms/op
     p(90.0000) =      4.084 ms/op
     p(95.0000) =      4.506 ms/op
     p(99.0000) =      6.029 ms/op
     p(99.9000) =     16.586 ms/op
     p(99.9900) =     29.327 ms/op
     p(99.9990) =     31.394 ms/op
     p(99.9999) =     32.440 ms/op
    p(100.0000) =     32.440 ms/op


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
# Warmup Iteration   1: 8.422 ±(99.9%) 0.121 ms/op
# Warmup Iteration   2: 3.637 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.468 ±(99.9%) 0.008 ms/op
Iteration   1: 3.423 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.489 ms/op
                 existUser·p0.50:   3.330 ms/op
                 existUser·p0.90:   3.875 ms/op
                 existUser·p0.95:   4.252 ms/op
                 existUser·p0.99:   6.300 ms/op
                 existUser·p0.999:  21.529 ms/op
                 existUser·p0.9999: 23.811 ms/op
                 existUser·p1.00:   24.707 ms/op

Iteration   2: 3.366 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.319 ms/op
                 existUser·p0.50:   3.314 ms/op
                 existUser·p0.90:   3.699 ms/op
                 existUser·p0.95:   3.994 ms/op
                 existUser·p0.99:   5.865 ms/op
                 existUser·p0.999:  23.397 ms/op
                 existUser·p0.9999: 27.886 ms/op
                 existUser·p1.00:   28.836 ms/op

Iteration   3: 3.338 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.440 ms/op
                 existUser·p0.50:   3.330 ms/op
                 existUser·p0.90:   3.478 ms/op
                 existUser·p0.95:   3.678 ms/op
                 existUser·p0.99:   6.021 ms/op
                 existUser·p0.999:  22.698 ms/op
                 existUser·p0.9999: 31.203 ms/op
                 existUser·p1.00:   31.687 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 284311
  mean =      3.375 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18848 
    [ 2.500,  5.000) = 259470 
    [ 5.000,  7.500) = 4997 
    [ 7.500, 10.000) = 584 
    [10.000, 12.500) = 122 
    [12.500, 15.000) = 2 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 31 
    [22.500, 25.000) = 157 
    [25.000, 27.500) = 45 
    [27.500, 30.000) = 24 
    [30.000, 32.500) = 31 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.440 ms/op
     p(50.0000) =      3.326 ms/op
     p(90.0000) =      3.678 ms/op
     p(95.0000) =      4.059 ms/op
     p(99.0000) =      6.070 ms/op
     p(99.9000) =     21.551 ms/op
     p(99.9900) =     30.624 ms/op
     p(99.9990) =     31.490 ms/op
     p(99.9999) =     31.687 ms/op
    p(100.0000) =     31.687 ms/op


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
# Warmup Iteration   1: 9.797 ±(99.9%) 0.127 ms/op
# Warmup Iteration   2: 3.729 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.543 ±(99.9%) 0.012 ms/op
Iteration   1: 3.549 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.647 ms/op
                 getUser·p0.50:   3.396 ms/op
                 getUser·p0.90:   4.051 ms/op
                 getUser·p0.95:   4.604 ms/op
                 getUser·p0.99:   7.324 ms/op
                 getUser·p0.999:  18.246 ms/op
                 getUser·p0.9999: 26.605 ms/op
                 getUser·p1.00:   27.853 ms/op

Iteration   2: 3.606 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.339 ms/op
                 getUser·p0.50:   3.457 ms/op
                 getUser·p0.90:   4.202 ms/op
                 getUser·p0.95:   4.522 ms/op
                 getUser·p0.99:   6.291 ms/op
                 getUser·p0.999:  21.290 ms/op
                 getUser·p0.9999: 26.214 ms/op
                 getUser·p1.00:   26.968 ms/op

Iteration   3: 3.418 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.130 ms/op
                 getUser·p0.50:   3.269 ms/op
                 getUser·p0.90:   3.756 ms/op
                 getUser·p0.95:   4.104 ms/op
                 getUser·p0.99:   6.767 ms/op
                 getUser·p0.999:  22.381 ms/op
                 getUser·p0.9999: 26.989 ms/op
                 getUser·p1.00:   27.951 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 272566
  mean =      3.522 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8378 
    [ 2.500,  5.000) = 255172 
    [ 5.000,  7.500) = 7508 
    [ 7.500, 10.000) = 874 
    [10.000, 12.500) = 213 
    [12.500, 15.000) = 114 
    [15.000, 17.500) = 19 
    [17.500, 20.000) = 14 
    [20.000, 22.500) = 53 
    [22.500, 25.000) = 129 
    [25.000, 27.500) = 87 

  Percentiles, ms/op:
      p(0.0000) =      1.130 ms/op
     p(50.0000) =      3.375 ms/op
     p(90.0000) =      4.039 ms/op
     p(95.0000) =      4.489 ms/op
     p(99.0000) =      6.982 ms/op
     p(99.9000) =     20.972 ms/op
     p(99.9900) =     26.640 ms/op
     p(99.9990) =     27.853 ms/op
     p(99.9999) =     27.951 ms/op
    p(100.0000) =     27.951 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 11.625 ±(99.9%) 0.158 ms/op
# Warmup Iteration   2: 4.645 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.204 ±(99.9%) 0.014 ms/op
Iteration   1: 3.897 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.432 ms/op
                 listUser·p0.50:   3.797 ms/op
                 listUser·p0.90:   4.211 ms/op
                 listUser·p0.95:   4.481 ms/op
                 listUser·p0.99:   7.002 ms/op
                 listUser·p0.999:  21.998 ms/op
                 listUser·p0.9999: 30.827 ms/op
                 listUser·p1.00:   32.080 ms/op

Iteration   2: 4.023 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.380 ms/op
                 listUser·p0.50:   3.887 ms/op
                 listUser·p0.90:   4.702 ms/op
                 listUser·p0.95:   5.014 ms/op
                 listUser·p0.99:   7.389 ms/op
                 listUser·p0.999:  15.945 ms/op
                 listUser·p0.9999: 16.600 ms/op
                 listUser·p1.00:   17.039 ms/op

Iteration   3: 3.998 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.726 ms/op
                 listUser·p0.50:   3.842 ms/op
                 listUser·p0.90:   4.456 ms/op
                 listUser·p0.95:   4.825 ms/op
                 listUser·p0.99:   7.348 ms/op
                 listUser·p0.999:  14.483 ms/op
                 listUser·p0.9999: 19.136 ms/op
                 listUser·p1.00:   19.661 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 241701
  mean =      3.972 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 36 
    [ 2.500,  5.000) = 232676 
    [ 5.000,  7.500) = 6953 
    [ 7.500, 10.000) = 1224 
    [10.000, 12.500) = 278 
    [12.500, 15.000) = 176 
    [15.000, 17.500) = 209 
    [17.500, 20.000) = 40 
    [20.000, 22.500) = 30 
    [22.500, 25.000) = 35 
    [25.000, 27.500) = 12 
    [27.500, 30.000) = 3 
    [30.000, 32.500) = 29 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.432 ms/op
     p(50.0000) =      3.850 ms/op
     p(90.0000) =      4.448 ms/op
     p(95.0000) =      4.825 ms/op
     p(99.0000) =      7.307 ms/op
     p(99.9000) =     16.040 ms/op
     p(99.9900) =     30.452 ms/op
     p(99.9990) =     31.588 ms/op
     p(99.9999) =     32.080 ms/op
    p(100.0000) =     32.080 ms/op


# Run complete. Total time: 00:13:13

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.138 ± 3.188  ops/ms
ClientPb.existUser                       thrpt       3   9.437 ± 7.053  ops/ms
ClientPb.getUser                         thrpt       3   9.308 ± 3.604  ops/ms
ClientPb.listUser                        thrpt       3   8.033 ± 4.680  ops/ms
ClientPb.createUser                       avgt       3   3.394 ± 1.494   ms/op
ClientPb.existUser                        avgt       3   3.298 ± 1.408   ms/op
ClientPb.getUser                          avgt       3   3.437 ± 0.413   ms/op
ClientPb.listUser                         avgt       3   3.981 ± 1.310   ms/op
ClientPb.createUser                     sample  270347   3.550 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.536           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.412           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.084           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.506           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.029           ms/op
ClientPb.createUser:createUser·p0.999   sample          16.586           ms/op
ClientPb.createUser:createUser·p0.9999  sample          29.327           ms/op
ClientPb.createUser:createUser·p1.00    sample          32.440           ms/op
ClientPb.existUser                      sample  284311   3.375 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.440           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.326           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.678           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.059           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.070           ms/op
ClientPb.existUser:existUser·p0.999     sample          21.551           ms/op
ClientPb.existUser:existUser·p0.9999    sample          30.624           ms/op
ClientPb.existUser:existUser·p1.00      sample          31.687           ms/op
ClientPb.getUser                        sample  272566   3.522 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.130           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.375           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.039           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.489           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.982           ms/op
ClientPb.getUser:getUser·p0.999         sample          20.972           ms/op
ClientPb.getUser:getUser·p0.9999        sample          26.640           ms/op
ClientPb.getUser:getUser·p1.00          sample          27.951           ms/op
ClientPb.listUser                       sample  241701   3.972 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.432           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.850           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.448           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.825           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.307           ms/op
ClientPb.listUser:listUser·p0.999       sample          16.040           ms/op
ClientPb.listUser:listUser·p0.9999      sample          30.452           ms/op
ClientPb.listUser:listUser·p1.00        sample          32.080           ms/op
