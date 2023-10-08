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
# Warmup Iteration   1: 1.062 ops/ms
# Warmup Iteration   2: 2.439 ops/ms
# Warmup Iteration   3: 4.620 ops/ms
Iteration   1: 5.368 ops/ms
Iteration   2: 5.603 ops/ms
Iteration   3: 5.645 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.538 ±(99.9%) 2.726 ops/ms [Average]
  (min, avg, max) = (5.368, 5.538, 5.645), stdev = 0.149
  CI (99.9%): [2.812, 8.265] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:06
# Fork: 1 of 1
# Warmup Iteration   1: 1.616 ops/ms
# Warmup Iteration   2: 4.956 ops/ms
# Warmup Iteration   3: 5.777 ops/ms
Iteration   1: 6.073 ops/ms
Iteration   2: 5.855 ops/ms
Iteration   3: 5.860 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.929 ±(99.9%) 2.273 ops/ms [Average]
  (min, avg, max) = (5.855, 5.929, 6.073), stdev = 0.125
  CI (99.9%): [3.656, 8.202] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:04
# Fork: 1 of 1
# Warmup Iteration   1: 1.556 ops/ms
# Warmup Iteration   2: 4.537 ops/ms
# Warmup Iteration   3: 5.538 ops/ms
Iteration   1: 5.510 ops/ms
Iteration   2: 5.569 ops/ms
Iteration   3: 5.690 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.589 ±(99.9%) 1.671 ops/ms [Average]
  (min, avg, max) = (5.510, 5.589, 5.690), stdev = 0.092
  CI (99.9%): [3.918, 7.261] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:59
# Fork: 1 of 1
# Warmup Iteration   1: 1.569 ops/ms
# Warmup Iteration   2: 4.039 ops/ms
# Warmup Iteration   3: 4.663 ops/ms
Iteration   1: 4.583 ops/ms
Iteration   2: 4.649 ops/ms
Iteration   3: 4.716 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.650 ±(99.9%) 1.212 ops/ms [Average]
  (min, avg, max) = (4.583, 4.650, 4.716), stdev = 0.066
  CI (99.9%): [3.437, 5.862] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:52
# Fork: 1 of 1
# Warmup Iteration   1: 19.062 ±(99.9%) 0.104 ms/op
# Warmup Iteration   2: 7.702 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 5.902 ±(99.9%) 0.009 ms/op
Iteration   1: 5.892 ±(99.9%) 0.010 ms/op
Iteration   2: 5.746 ±(99.9%) 0.016 ms/op
Iteration   3: 5.678 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.772 ±(99.9%) 1.993 ms/op [Average]
  (min, avg, max) = (5.678, 5.772, 5.892), stdev = 0.109
  CI (99.9%): [3.779, 7.765] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:46
# Fork: 1 of 1
# Warmup Iteration   1: 15.317 ±(99.9%) 0.062 ms/op
# Warmup Iteration   2: 6.298 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 5.774 ±(99.9%) 0.007 ms/op
Iteration   1: 5.521 ±(99.9%) 0.009 ms/op
Iteration   2: 5.751 ±(99.9%) 0.008 ms/op
Iteration   3: 5.449 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.573 ±(99.9%) 2.877 ms/op [Average]
  (min, avg, max) = (5.449, 5.573, 5.751), stdev = 0.158
  CI (99.9%): [2.696, 8.451] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:40
# Fork: 1 of 1
# Warmup Iteration   1: 17.295 ±(99.9%) 0.072 ms/op
# Warmup Iteration   2: 6.673 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 5.846 ±(99.9%) 0.011 ms/op
Iteration   1: 5.938 ±(99.9%) 0.008 ms/op
Iteration   2: 5.743 ±(99.9%) 0.010 ms/op
Iteration   3: 5.692 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.791 ±(99.9%) 2.374 ms/op [Average]
  (min, avg, max) = (5.692, 5.791, 5.938), stdev = 0.130
  CI (99.9%): [3.417, 8.165] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:33
# Fork: 1 of 1
# Warmup Iteration   1: 18.583 ±(99.9%) 0.076 ms/op
# Warmup Iteration   2: 7.501 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 6.850 ±(99.9%) 0.013 ms/op
Iteration   1: 6.721 ±(99.9%) 0.010 ms/op
Iteration   2: 6.724 ±(99.9%) 0.011 ms/op
Iteration   3: 6.620 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.688 ±(99.9%) 1.082 ms/op [Average]
  (min, avg, max) = (6.620, 6.688, 6.724), stdev = 0.059
  CI (99.9%): [5.607, 7.770] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:26
# Fork: 1 of 1
# Warmup Iteration   1: 19.395 ±(99.9%) 0.301 ms/op
# Warmup Iteration   2: 7.260 ±(99.9%) 0.047 ms/op
# Warmup Iteration   3: 6.201 ±(99.9%) 0.028 ms/op
Iteration   1: 5.824 ±(99.9%) 0.020 ms/op
                 createUser·p0.00:   2.548 ms/op
                 createUser·p0.50:   5.554 ms/op
                 createUser·p0.90:   7.094 ms/op
                 createUser·p0.95:   7.938 ms/op
                 createUser·p0.99:   10.791 ms/op
                 createUser·p0.999:  25.821 ms/op
                 createUser·p0.9999: 29.164 ms/op
                 createUser·p1.00:   29.426 ms/op

Iteration   2: 5.799 ±(99.9%) 0.019 ms/op
                 createUser·p0.00:   2.527 ms/op
                 createUser·p0.50:   5.587 ms/op
                 createUser·p0.90:   6.988 ms/op
                 createUser·p0.95:   7.684 ms/op
                 createUser·p0.99:   10.453 ms/op
                 createUser·p0.999:  17.433 ms/op
                 createUser·p0.9999: 29.653 ms/op
                 createUser·p1.00:   30.867 ms/op

Iteration   3: 5.821 ±(99.9%) 0.020 ms/op
                 createUser·p0.00:   2.396 ms/op
                 createUser·p0.50:   5.587 ms/op
                 createUser·p0.90:   7.062 ms/op
                 createUser·p0.95:   7.717 ms/op
                 createUser·p0.99:   10.417 ms/op
                 createUser·p0.999:  27.197 ms/op
                 createUser·p0.9999: 31.672 ms/op
                 createUser·p1.00:   33.456 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 164932
  mean =      5.815 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2 
    [ 2.500,  5.000) = 35409 
    [ 5.000,  7.500) = 119061 
    [ 7.500, 10.000) = 8338 
    [10.000, 12.500) = 1372 
    [12.500, 15.000) = 419 
    [15.000, 17.500) = 134 
    [17.500, 20.000) = 33 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 73 
    [27.500, 30.000) = 69 
    [30.000, 32.500) = 17 
    [32.500, 35.000) = 2 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.396 ms/op
     p(50.0000) =      5.579 ms/op
     p(90.0000) =      7.045 ms/op
     p(95.0000) =      7.791 ms/op
     p(99.0000) =     10.551 ms/op
     p(99.9000) =     19.449 ms/op
     p(99.9900) =     30.343 ms/op
     p(99.9990) =     33.435 ms/op
     p(99.9999) =     33.456 ms/op
    p(100.0000) =     33.456 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:20
# Fork: 1 of 1
# Warmup Iteration   1: 18.016 ±(99.9%) 0.281 ms/op
# Warmup Iteration   2: 6.473 ±(99.9%) 0.036 ms/op
# Warmup Iteration   3: 5.676 ±(99.9%) 0.020 ms/op
Iteration   1: 5.666 ±(99.9%) 0.020 ms/op
                 existUser·p0.00:   2.605 ms/op
                 existUser·p0.50:   5.292 ms/op
                 existUser·p0.90:   7.160 ms/op
                 existUser·p0.95:   8.323 ms/op
                 existUser·p0.99:   10.895 ms/op
                 existUser·p0.999:  23.714 ms/op
                 existUser·p0.9999: 27.364 ms/op
                 existUser·p1.00:   28.377 ms/op

Iteration   2: 5.641 ±(99.9%) 0.020 ms/op
                 existUser·p0.00:   2.789 ms/op
                 existUser·p0.50:   5.374 ms/op
                 existUser·p0.90:   6.734 ms/op
                 existUser·p0.95:   7.471 ms/op
                 existUser·p0.99:   11.125 ms/op
                 existUser·p0.999:  27.018 ms/op
                 existUser·p0.9999: 30.496 ms/op
                 existUser·p1.00:   31.392 ms/op

Iteration   3: 5.689 ±(99.9%) 0.019 ms/op
                 existUser·p0.00:   2.138 ms/op
                 existUser·p0.50:   5.374 ms/op
                 existUser·p0.90:   7.086 ms/op
                 existUser·p0.95:   7.971 ms/op
                 existUser·p0.99:   10.420 ms/op
                 existUser·p0.999:  19.753 ms/op
                 existUser·p0.9999: 29.006 ms/op
                 existUser·p1.00:   29.884 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 169255
  mean =      5.665 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6 
    [ 2.500,  5.000) = 49746 
    [ 5.000,  7.500) = 108162 
    [ 7.500, 10.000) = 8915 
    [10.000, 12.500) = 1593 
    [12.500, 15.000) = 492 
    [15.000, 17.500) = 88 
    [17.500, 20.000) = 42 
    [20.000, 22.500) = 35 
    [22.500, 25.000) = 43 
    [25.000, 27.500) = 71 
    [27.500, 30.000) = 51 
    [30.000, 32.500) = 11 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.138 ms/op
     p(50.0000) =      5.349 ms/op
     p(90.0000) =      6.971 ms/op
     p(95.0000) =      7.987 ms/op
     p(99.0000) =     10.830 ms/op
     p(99.9000) =     22.831 ms/op
     p(99.9900) =     29.637 ms/op
     p(99.9990) =     31.074 ms/op
     p(99.9999) =     31.392 ms/op
    p(100.0000) =     31.392 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:13
# Fork: 1 of 1
# Warmup Iteration   1: 18.428 ±(99.9%) 0.324 ms/op
# Warmup Iteration   2: 6.814 ±(99.9%) 0.036 ms/op
# Warmup Iteration   3: 5.869 ±(99.9%) 0.020 ms/op
Iteration   1: 5.671 ±(99.9%) 0.018 ms/op
                 getUser·p0.00:   2.433 ms/op
                 getUser·p0.50:   5.407 ms/op
                 getUser·p0.90:   6.701 ms/op
                 getUser·p0.95:   7.873 ms/op
                 getUser·p0.99:   10.469 ms/op
                 getUser·p0.999:  22.053 ms/op
                 getUser·p0.9999: 26.947 ms/op
                 getUser·p1.00:   27.558 ms/op

Iteration   2: 5.771 ±(99.9%) 0.020 ms/op
                 getUser·p0.00:   0.487 ms/op
                 getUser·p0.50:   5.423 ms/op
                 getUser·p0.90:   7.062 ms/op
                 getUser·p0.95:   8.225 ms/op
                 getUser·p0.99:   11.272 ms/op
                 getUser·p0.999:  17.454 ms/op
                 getUser·p0.9999: 26.076 ms/op
                 getUser·p1.00:   26.477 ms/op

Iteration   3: 6.007 ±(99.9%) 0.022 ms/op
                 getUser·p0.00:   1.968 ms/op
                 getUser·p0.50:   5.710 ms/op
                 getUser·p0.90:   7.381 ms/op
                 getUser·p0.95:   8.274 ms/op
                 getUser·p0.99:   11.815 ms/op
                 getUser·p0.999:  25.891 ms/op
                 getUser·p0.9999: 27.962 ms/op
                 getUser·p1.00:   28.410 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 165083
  mean =      5.813 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11 
    [ 2.500,  5.000) = 33849 
    [ 5.000,  7.500) = 118957 
    [ 7.500, 10.000) = 9456 
    [10.000, 12.500) = 1838 
    [12.500, 15.000) = 607 
    [15.000, 17.500) = 118 
    [17.500, 20.000) = 61 
    [20.000, 22.500) = 15 
    [22.500, 25.000) = 42 
    [25.000, 27.500) = 109 

  Percentiles, ms/op:
      p(0.0000) =      0.487 ms/op
     p(50.0000) =      5.513 ms/op
     p(90.0000) =      7.062 ms/op
     p(95.0000) =      8.125 ms/op
     p(99.0000) =     11.125 ms/op
     p(99.9000) =     22.837 ms/op
     p(99.9900) =     27.574 ms/op
     p(99.9990) =     28.325 ms/op
     p(99.9999) =     28.410 ms/op
    p(100.0000) =     28.410 ms/op


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
# Warmup Iteration   1: 18.355 ±(99.9%) 0.328 ms/op
# Warmup Iteration   2: 7.743 ±(99.9%) 0.040 ms/op
# Warmup Iteration   3: 6.722 ±(99.9%) 0.024 ms/op
Iteration   1: 6.808 ±(99.9%) 0.023 ms/op
                 listUser·p0.00:   2.417 ms/op
                 listUser·p0.50:   6.562 ms/op
                 listUser·p0.90:   7.987 ms/op
                 listUser·p0.95:   9.126 ms/op
                 listUser·p0.99:   11.567 ms/op
                 listUser·p0.999:  26.902 ms/op
                 listUser·p0.9999: 29.979 ms/op
                 listUser·p1.00:   32.014 ms/op

Iteration   2: 7.043 ±(99.9%) 0.028 ms/op
                 listUser·p0.00:   3.256 ms/op
                 listUser·p0.50:   6.726 ms/op
                 listUser·p0.90:   8.421 ms/op
                 listUser·p0.95:   9.388 ms/op
                 listUser·p0.99:   12.878 ms/op
                 listUser·p0.999:  30.821 ms/op
                 listUser·p0.9999: 36.564 ms/op
                 listUser·p1.00:   36.766 ms/op

Iteration   3: 6.958 ±(99.9%) 0.022 ms/op
                 listUser·p0.00:   1.823 ms/op
                 listUser·p0.50:   6.742 ms/op
                 listUser·p0.90:   8.159 ms/op
                 listUser·p0.95:   8.995 ms/op
                 listUser·p0.99:   11.485 ms/op
                 listUser·p0.999:  25.188 ms/op
                 listUser·p0.9999: 31.077 ms/op
                 listUser·p1.00:   32.047 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 138432
  mean =      6.935 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2 
    [ 2.500,  5.000) = 1513 
    [ 5.000,  7.500) = 108860 
    [ 7.500, 10.000) = 23689 
    [10.000, 12.500) = 3204 
    [12.500, 15.000) = 674 
    [15.000, 17.500) = 118 
    [17.500, 20.000) = 52 
    [20.000, 22.500) = 61 
    [22.500, 25.000) = 20 
    [25.000, 27.500) = 81 
    [27.500, 30.000) = 87 
    [30.000, 32.500) = 46 
    [32.500, 35.000) = 15 
    [35.000, 37.500) = 10 

  Percentiles, ms/op:
      p(0.0000) =      1.823 ms/op
     p(50.0000) =      6.676 ms/op
     p(90.0000) =      8.192 ms/op
     p(95.0000) =      9.159 ms/op
     p(99.0000) =     12.026 ms/op
     p(99.9000) =     28.508 ms/op
     p(99.9900) =     34.941 ms/op
     p(99.9990) =     36.741 ms/op
     p(99.9999) =     36.766 ms/op
    p(100.0000) =     36.766 ms/op


# Run complete. Total time: 00:13:19

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.538 ± 2.726  ops/ms
ClientPb.existUser                       thrpt       3   5.929 ± 2.273  ops/ms
ClientPb.getUser                         thrpt       3   5.589 ± 1.671  ops/ms
ClientPb.listUser                        thrpt       3   4.650 ± 1.212  ops/ms
ClientPb.createUser                       avgt       3   5.772 ± 1.993   ms/op
ClientPb.existUser                        avgt       3   5.573 ± 2.877   ms/op
ClientPb.getUser                          avgt       3   5.791 ± 2.374   ms/op
ClientPb.listUser                         avgt       3   6.688 ± 1.082   ms/op
ClientPb.createUser                     sample  164932   5.815 ± 0.011   ms/op
ClientPb.createUser:createUser·p0.00    sample           2.396           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.579           ms/op
ClientPb.createUser:createUser·p0.90    sample           7.045           ms/op
ClientPb.createUser:createUser·p0.95    sample           7.791           ms/op
ClientPb.createUser:createUser·p0.99    sample          10.551           ms/op
ClientPb.createUser:createUser·p0.999   sample          19.449           ms/op
ClientPb.createUser:createUser·p0.9999  sample          30.343           ms/op
ClientPb.createUser:createUser·p1.00    sample          33.456           ms/op
ClientPb.existUser                      sample  169255   5.665 ± 0.011   ms/op
ClientPb.existUser:existUser·p0.00      sample           2.138           ms/op
ClientPb.existUser:existUser·p0.50      sample           5.349           ms/op
ClientPb.existUser:existUser·p0.90      sample           6.971           ms/op
ClientPb.existUser:existUser·p0.95      sample           7.987           ms/op
ClientPb.existUser:existUser·p0.99      sample          10.830           ms/op
ClientPb.existUser:existUser·p0.999     sample          22.831           ms/op
ClientPb.existUser:existUser·p0.9999    sample          29.637           ms/op
ClientPb.existUser:existUser·p1.00      sample          31.392           ms/op
ClientPb.getUser                        sample  165083   5.813 ± 0.012   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.487           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.513           ms/op
ClientPb.getUser:getUser·p0.90          sample           7.062           ms/op
ClientPb.getUser:getUser·p0.95          sample           8.125           ms/op
ClientPb.getUser:getUser·p0.99          sample          11.125           ms/op
ClientPb.getUser:getUser·p0.999         sample          22.837           ms/op
ClientPb.getUser:getUser·p0.9999        sample          27.574           ms/op
ClientPb.getUser:getUser·p1.00          sample          28.410           ms/op
ClientPb.listUser                       sample  138432   6.935 ± 0.014   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.823           ms/op
ClientPb.listUser:listUser·p0.50        sample           6.676           ms/op
ClientPb.listUser:listUser·p0.90        sample           8.192           ms/op
ClientPb.listUser:listUser·p0.95        sample           9.159           ms/op
ClientPb.listUser:listUser·p0.99        sample          12.026           ms/op
ClientPb.listUser:listUser·p0.999       sample          28.508           ms/op
ClientPb.listUser:listUser·p0.9999      sample          34.941           ms/op
ClientPb.listUser:listUser·p1.00        sample          36.766           ms/op
