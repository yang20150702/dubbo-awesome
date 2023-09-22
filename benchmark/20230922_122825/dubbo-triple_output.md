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
# Warmup Iteration   1: 2.244 ops/ms
# Warmup Iteration   2: 5.948 ops/ms
# Warmup Iteration   3: 8.504 ops/ms
Iteration   1: 9.040 ops/ms
Iteration   2: 9.066 ops/ms
Iteration   3: 9.230 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.112 ±(99.9%) 1.878 ops/ms [Average]
  (min, avg, max) = (9.040, 9.112, 9.230), stdev = 0.103
  CI (99.9%): [7.234, 10.990] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:08
# Fork: 1 of 1
# Warmup Iteration   1: 3.063 ops/ms
# Warmup Iteration   2: 8.772 ops/ms
# Warmup Iteration   3: 9.504 ops/ms
Iteration   1: 9.767 ops/ms
Iteration   2: 9.946 ops/ms
Iteration   3: 9.814 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.842 ±(99.9%) 1.694 ops/ms [Average]
  (min, avg, max) = (9.767, 9.842, 9.946), stdev = 0.093
  CI (99.9%): [8.149, 11.536] (assumes normal distribution)


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
# Warmup Iteration   1: 2.678 ops/ms
# Warmup Iteration   2: 7.846 ops/ms
# Warmup Iteration   3: 8.867 ops/ms
Iteration   1: 9.340 ops/ms
Iteration   2: 9.312 ops/ms
Iteration   3: 9.315 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.322 ±(99.9%) 0.281 ops/ms [Average]
  (min, avg, max) = (9.312, 9.322, 9.340), stdev = 0.015
  CI (99.9%): [9.042, 9.603] (assumes normal distribution)


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
# Warmup Iteration   1: 3.077 ops/ms
# Warmup Iteration   2: 7.166 ops/ms
# Warmup Iteration   3: 7.566 ops/ms
Iteration   1: 7.695 ops/ms
Iteration   2: 7.661 ops/ms
Iteration   3: 7.733 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.697 ±(99.9%) 0.660 ops/ms [Average]
  (min, avg, max) = (7.661, 7.697, 7.733), stdev = 0.036
  CI (99.9%): [7.036, 8.357] (assumes normal distribution)


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
# Warmup Iteration   1: 9.208 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.804 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.583 ±(99.9%) 0.008 ms/op
Iteration   1: 3.534 ±(99.9%) 0.004 ms/op
Iteration   2: 3.596 ±(99.9%) 0.003 ms/op
Iteration   3: 3.530 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.553 ±(99.9%) 0.679 ms/op [Average]
  (min, avg, max) = (3.530, 3.553, 3.596), stdev = 0.037
  CI (99.9%): [2.874, 4.232] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 8.786 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 3.541 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.368 ±(99.9%) 0.006 ms/op
Iteration   1: 3.419 ±(99.9%) 0.004 ms/op
Iteration   2: 3.376 ±(99.9%) 0.003 ms/op
Iteration   3: 3.477 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.424 ±(99.9%) 0.918 ms/op [Average]
  (min, avg, max) = (3.376, 3.424, 3.477), stdev = 0.050
  CI (99.9%): [2.506, 4.342] (assumes normal distribution)


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
# Warmup Iteration   1: 10.493 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.612 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.542 ±(99.9%) 0.004 ms/op
Iteration   1: 3.435 ±(99.9%) 0.006 ms/op
Iteration   2: 3.422 ±(99.9%) 0.004 ms/op
Iteration   3: 3.507 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.455 ±(99.9%) 0.837 ms/op [Average]
  (min, avg, max) = (3.422, 3.455, 3.507), stdev = 0.046
  CI (99.9%): [2.618, 4.292] (assumes normal distribution)


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
# Warmup Iteration   1: 10.453 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 4.410 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.120 ±(99.9%) 0.008 ms/op
Iteration   1: 4.142 ±(99.9%) 0.007 ms/op
Iteration   2: 4.189 ±(99.9%) 0.006 ms/op
Iteration   3: 4.123 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.151 ±(99.9%) 0.616 ms/op [Average]
  (min, avg, max) = (4.123, 4.151, 4.189), stdev = 0.034
  CI (99.9%): [3.536, 4.767] (assumes normal distribution)


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
# Warmup Iteration   1: 9.610 ±(99.9%) 0.115 ms/op
# Warmup Iteration   2: 4.083 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.560 ±(99.9%) 0.010 ms/op
Iteration   1: 3.493 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.959 ms/op
                 createUser·p0.50:   3.367 ms/op
                 createUser·p0.90:   3.932 ms/op
                 createUser·p0.95:   4.243 ms/op
                 createUser·p0.99:   6.218 ms/op
                 createUser·p0.999:  21.287 ms/op
                 createUser·p0.9999: 23.724 ms/op
                 createUser·p1.00:   24.248 ms/op

Iteration   2: 3.526 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.534 ms/op
                 createUser·p0.50:   3.424 ms/op
                 createUser·p0.90:   4.080 ms/op
                 createUser·p0.95:   4.325 ms/op
                 createUser·p0.99:   5.505 ms/op
                 createUser·p0.999:  22.615 ms/op
                 createUser·p0.9999: 25.395 ms/op
                 createUser·p1.00:   26.247 ms/op

Iteration   3: 3.604 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.609 ms/op
                 createUser·p0.50:   3.494 ms/op
                 createUser·p0.90:   4.129 ms/op
                 createUser·p0.95:   4.383 ms/op
                 createUser·p0.99:   5.858 ms/op
                 createUser·p0.999:  19.209 ms/op
                 createUser·p0.9999: 26.808 ms/op
                 createUser·p1.00:   28.574 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 271401
  mean =      3.541 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4413 
    [ 2.500,  5.000) = 261867 
    [ 5.000,  7.500) = 3979 
    [ 7.500, 10.000) = 637 
    [10.000, 12.500) = 159 
    [12.500, 15.000) = 22 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 30 
    [20.000, 22.500) = 71 
    [22.500, 25.000) = 139 
    [25.000, 27.500) = 48 

  Percentiles, ms/op:
      p(0.0000) =      0.609 ms/op
     p(50.0000) =      3.420 ms/op
     p(90.0000) =      4.055 ms/op
     p(95.0000) =      4.334 ms/op
     p(99.0000) =      5.923 ms/op
     p(99.9000) =     19.766 ms/op
     p(99.9900) =     25.728 ms/op
     p(99.9990) =     27.558 ms/op
     p(99.9999) =     28.574 ms/op
    p(100.0000) =     28.574 ms/op


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
# Warmup Iteration   1: 8.622 ±(99.9%) 0.109 ms/op
# Warmup Iteration   2: 3.785 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.358 ±(99.9%) 0.008 ms/op
Iteration   1: 3.370 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.190 ms/op
                 existUser·p0.50:   3.260 ms/op
                 existUser·p0.90:   3.764 ms/op
                 existUser·p0.95:   4.076 ms/op
                 existUser·p0.99:   5.784 ms/op
                 existUser·p0.999:  22.051 ms/op
                 existUser·p0.9999: 25.788 ms/op
                 existUser·p1.00:   26.182 ms/op

Iteration   2: 3.369 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.448 ms/op
                 existUser·p0.50:   3.248 ms/op
                 existUser·p0.90:   3.637 ms/op
                 existUser·p0.95:   3.895 ms/op
                 existUser·p0.99:   6.822 ms/op
                 existUser·p0.999:  22.282 ms/op
                 existUser·p0.9999: 25.379 ms/op
                 existUser·p1.00:   25.887 ms/op

Iteration   3: 3.377 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.759 ms/op
                 existUser·p0.50:   3.273 ms/op
                 existUser·p0.90:   3.756 ms/op
                 existUser·p0.95:   4.010 ms/op
                 existUser·p0.99:   5.300 ms/op
                 existUser·p0.999:  19.997 ms/op
                 existUser·p0.9999: 27.598 ms/op
                 existUser·p1.00:   28.180 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 284702
  mean =      3.372 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6140 
    [ 2.500,  5.000) = 273515 
    [ 5.000,  7.500) = 4044 
    [ 7.500, 10.000) = 400 
    [10.000, 12.500) = 248 
    [12.500, 15.000) = 22 
    [15.000, 17.500) = 31 
    [17.500, 20.000) = 16 
    [20.000, 22.500) = 48 
    [22.500, 25.000) = 117 
    [25.000, 27.500) = 112 

  Percentiles, ms/op:
      p(0.0000) =      1.190 ms/op
     p(50.0000) =      3.260 ms/op
     p(90.0000) =      3.719 ms/op
     p(95.0000) =      4.006 ms/op
     p(99.0000) =      5.775 ms/op
     p(99.9000) =     20.319 ms/op
     p(99.9900) =     26.837 ms/op
     p(99.9990) =     28.092 ms/op
     p(99.9999) =     28.180 ms/op
    p(100.0000) =     28.180 ms/op


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
# Warmup Iteration   1: 8.893 ±(99.9%) 0.111 ms/op
# Warmup Iteration   2: 3.859 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.611 ±(99.9%) 0.011 ms/op
Iteration   1: 3.698 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   0.985 ms/op
                 getUser·p0.50:   3.510 ms/op
                 getUser·p0.90:   4.141 ms/op
                 getUser·p0.95:   5.005 ms/op
                 getUser·p0.99:   7.160 ms/op
                 getUser·p0.999:  20.809 ms/op
                 getUser·p0.9999: 23.670 ms/op
                 getUser·p1.00:   24.117 ms/op

Iteration   2: 3.517 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.743 ms/op
                 getUser·p0.50:   3.424 ms/op
                 getUser·p0.90:   3.895 ms/op
                 getUser·p0.95:   4.153 ms/op
                 getUser·p0.99:   5.898 ms/op
                 getUser·p0.999:  22.415 ms/op
                 getUser·p0.9999: 25.654 ms/op
                 getUser·p1.00:   27.001 ms/op

Iteration   3: 3.538 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.340 ms/op
                 getUser·p0.50:   3.424 ms/op
                 getUser·p0.90:   4.121 ms/op
                 getUser·p0.95:   4.399 ms/op
                 getUser·p0.99:   6.169 ms/op
                 getUser·p0.999:  12.747 ms/op
                 getUser·p0.9999: 30.342 ms/op
                 getUser·p1.00:   30.966 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 267787
  mean =      3.583 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4119 
    [ 2.500,  5.000) = 255372 
    [ 5.000,  7.500) = 7176 
    [ 7.500, 10.000) = 665 
    [10.000, 12.500) = 118 
    [12.500, 15.000) = 75 
    [15.000, 17.500) = 2 
    [17.500, 20.000) = 4 
    [20.000, 22.500) = 59 
    [22.500, 25.000) = 135 
    [25.000, 27.500) = 32 
    [27.500, 30.000) = 20 
    [30.000, 32.500) = 10 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.340 ms/op
     p(50.0000) =      3.445 ms/op
     p(90.0000) =      4.052 ms/op
     p(95.0000) =      4.399 ms/op
     p(99.0000) =      6.988 ms/op
     p(99.9000) =     13.396 ms/op
     p(99.9900) =     28.719 ms/op
     p(99.9990) =     30.811 ms/op
     p(99.9999) =     30.966 ms/op
    p(100.0000) =     30.966 ms/op


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
# Warmup Iteration   1: 12.035 ±(99.9%) 0.155 ms/op
# Warmup Iteration   2: 4.544 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.165 ±(99.9%) 0.012 ms/op
Iteration   1: 4.173 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.778 ms/op
                 listUser·p0.50:   4.043 ms/op
                 listUser·p0.90:   4.596 ms/op
                 listUser·p0.95:   4.891 ms/op
                 listUser·p0.99:   7.168 ms/op
                 listUser·p0.999:  20.917 ms/op
                 listUser·p0.9999: 25.395 ms/op
                 listUser·p1.00:   26.083 ms/op

Iteration   2: 4.091 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.325 ms/op
                 listUser·p0.50:   3.891 ms/op
                 listUser·p0.90:   4.628 ms/op
                 listUser·p0.95:   4.891 ms/op
                 listUser·p0.99:   7.012 ms/op
                 listUser·p0.999:  15.024 ms/op
                 listUser·p0.9999: 21.463 ms/op
                 listUser·p1.00:   21.692 ms/op

Iteration   3: 4.200 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.437 ms/op
                 listUser·p0.50:   4.112 ms/op
                 listUser·p0.90:   4.637 ms/op
                 listUser·p0.95:   4.923 ms/op
                 listUser·p0.99:   7.201 ms/op
                 listUser·p0.999:  15.678 ms/op
                 listUser·p0.9999: 19.117 ms/op
                 listUser·p1.00:   19.333 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 230934
  mean =      4.154 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 39 
    [ 2.500,  5.000) = 221221 
    [ 5.000,  7.500) = 7887 
    [ 7.500, 10.000) = 1045 
    [10.000, 12.500) = 141 
    [12.500, 15.000) = 235 
    [15.000, 17.500) = 199 
    [17.500, 20.000) = 41 
    [20.000, 22.500) = 88 
    [22.500, 25.000) = 26 
    [25.000, 27.500) = 12 

  Percentiles, ms/op:
      p(0.0000) =      1.325 ms/op
     p(50.0000) =      4.026 ms/op
     p(90.0000) =      4.620 ms/op
     p(95.0000) =      4.899 ms/op
     p(99.0000) =      7.168 ms/op
     p(99.9000) =     16.123 ms/op
     p(99.9900) =     23.810 ms/op
     p(99.9990) =     25.987 ms/op
     p(99.9999) =     26.083 ms/op
    p(100.0000) =     26.083 ms/op


# Run complete. Total time: 00:13:12

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.112 ± 1.878  ops/ms
ClientPb.existUser                       thrpt       3   9.842 ± 1.694  ops/ms
ClientPb.getUser                         thrpt       3   9.322 ± 0.281  ops/ms
ClientPb.listUser                        thrpt       3   7.697 ± 0.660  ops/ms
ClientPb.createUser                       avgt       3   3.553 ± 0.679   ms/op
ClientPb.existUser                        avgt       3   3.424 ± 0.918   ms/op
ClientPb.getUser                          avgt       3   3.455 ± 0.837   ms/op
ClientPb.listUser                         avgt       3   4.151 ± 0.616   ms/op
ClientPb.createUser                     sample  271401   3.541 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.609           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.420           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.055           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.334           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.923           ms/op
ClientPb.createUser:createUser·p0.999   sample          19.766           ms/op
ClientPb.createUser:createUser·p0.9999  sample          25.728           ms/op
ClientPb.createUser:createUser·p1.00    sample          28.574           ms/op
ClientPb.existUser                      sample  284702   3.372 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.190           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.260           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.719           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.006           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.775           ms/op
ClientPb.existUser:existUser·p0.999     sample          20.319           ms/op
ClientPb.existUser:existUser·p0.9999    sample          26.837           ms/op
ClientPb.existUser:existUser·p1.00      sample          28.180           ms/op
ClientPb.getUser                        sample  267787   3.583 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.340           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.445           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.052           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.399           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.988           ms/op
ClientPb.getUser:getUser·p0.999         sample          13.396           ms/op
ClientPb.getUser:getUser·p0.9999        sample          28.719           ms/op
ClientPb.getUser:getUser·p1.00          sample          30.966           ms/op
ClientPb.listUser                       sample  230934   4.154 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.325           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.026           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.620           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.899           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.168           ms/op
ClientPb.listUser:listUser·p0.999       sample          16.123           ms/op
ClientPb.listUser:listUser·p0.9999      sample          23.810           ms/op
ClientPb.listUser:listUser·p1.00        sample          26.083           ms/op
